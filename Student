package lab2;

import java.util.Scanner;

class Student {
	
	Scanner scan = new Scanner(System.in);
	private String name;
	private int ssn;
	private int numOfCourses;
	private Date birthDate;
	protected char gender;
	  
	  
	public Student(){
	}
	  
    private void readData() {  // reads data for instance variables 
	  		       // from console window
	    System.out.println("Please input the name: ");
	    name = scan.nextLine();

	    System.out.println("\nPlease input the ssn: ");
	    ssn = scan.nextInt();

	    System.out.println("\nMale/Female (m/f): ");
	    gender =  scan.next().charAt(0);

	    System.out.println("\nHow many courses is he taking: ");
	    numOfCourses = scan.nextInt();

	    System.out.println("\nPlease input his birth date: ");
		    System.out.println("\n	Please input the month: ");
		    month = scan.nextInt();
		    System.out.println("\n	Please input the day: ");
		    day = scan.nextInt();
		    System.out.println("\n	Please input the year: ");
		    year = scan.nextInt();
	    birthDate = new Date(month,day,year);

	    System.out.println("\nPlease input his research topic: ");
	    researchTopic = scan.nextLine();

	    System.out.println("\nPlease input his research advisor: ");
	    researchAdvisor = scan.nextLine();

	    System.out.println("\nPlease input his TA course: ");
	    taCourse = scan.nextLine()

	    System.out.println("\nPlease input his TA instructor: ");
	    taInstructor = scan.nextLine();

	    System.out.println("\nPlease input his hire date: ");
		    System.out.println("\n	Please input the month: ");
		    month = scan.nextInt();
		    System.out.println("\n	Please input the day: ");
		    day = scan.nextInt();
		    System.out.println("\n	Please input the year: ");
		    year = scan.nextInt();
	    hireDate = new Date(month,day,year);
	    System.out.println("\n");
    }
	  
	public void print() {  //  prints values of instance variables 
		  	       //  to the standard output
		System.out.println("The information you input was");
		System.out.printf("\n%s's  ssn is %d.", name, ssn);
		System.out.printf("\nHe is taking %d courses.", numOfCourses);
		System.out.printf("\nHis birth date is %d/%d/%d", month, day, year);
		System.out.printf("\nHis research topic is %s.", researchTopic);
		System.out.printf("\nHis advisor is %s.", advisor);
		System.out.printf("\nHis TA course is %s.", taCourse);
		System.out.printf("\nHis TA instructor is %s.", taInstructor);
		System.out.printf("\nHis hire date is %d/%d/%d", month, day, year);
	}
	
}
