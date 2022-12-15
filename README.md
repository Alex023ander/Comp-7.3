# Comp-7.3

public static void main(String[] args) {
        Address school = new Address("800 Lancaster Ave.", "Villanova", "PA", 19085);
        Address jHome = new Address("21 Jump Street", "Blacksburg", "VA", 24551);
        Student jake = new Student("Jake", "January", jHome, school, 95,55,100);
        Address mHome = new Address("123 Main Street", "Euclid", "OH", 44132);
        Student michael = new Student("Michael", "McGriddy", mHome, school);
        Course math = new Course("math");
   
        michael.setTestScore(1, 90.5);
        michael.getTestScore(0);
    
        math.addStudent(michael);
	math.addStudent(jake);
	System.out.println(math.roll());
	System.out.println(math.average());
    }
}
