// Lab06Ast.java
// Arithmetic with Math Class Methods
// This is the student, starting version, of Lab 06A.


public class Lab06Ast
{
	public static void main(String args[])
	{
		System.out.println("Lab 06A, 100 Point Version");
      	System.out.println();
      	System.out.println("Arithmetic with Math Class Methods");
      	System.out.println();
        System.out.println("By: Daniel nyaga");  
        System.out.println("\n==================================\n");

		double w = 10.0;
		double x = 5.0;
		double y = 77.77;
		double z = 1.21;

		double s1 = Math.sqrt(25);
		System.out.println("s1 = " + s1);
      double s2 = Math.sqrt(100);
      System.out.println("s2 = " + s2);
      double s3 = Math.sqrt(3);
      System.out.println("s3 = " + s3);
      double s4 = Math.sqrt(x);
      System.out.println("s4 =" + s4);
      double s5 = Math.sqrt(y);
      System.out.println("s5 = " + s5);
      double s6 = Math.sqrt(x*y);
      System.out.println(" s6 =" + s6);
      double s7 = Math.sqrt(Math.E * Math.PI);
      System.out.println("s7 = " + s7);
      double a1 = Math.abs(7);
      System.out.println("The absolute value of 7 is" + Math.abs(7));
      double a2 = Math.abs(-7);
      System.out.println(" The absolute value of -7 is " + Math.abs(-7));
      double a3 = Math.abs(-x);
      System.out.println(" The absolute value of -x is " + Math.abs(-x));
      double a4 = Math.abs(y-x);
      System.out.println(" The absolute value of y-x is " + Math.abs(y-x));
      double a5 = Math.abs(z-y);
      System.out.println(" The absolute value of z-y is " + Math.abs(z-y));
      double a6 = Math.abs(Math.E - Math.PI);
      System.out.println(" The absolute value of Math.E - Math.PI is " + Math.abs( Math.E - Math.PI));
      double p1 = Math.pow(7,2);
      System.out.println("7 to the power of 2 is" + p1);
      double p2 = Math.pow(2,7);
      System.out.println("2 to the power of 7 is " + p2);
      double p3 = Math.pow(z,3);
      System.out.println(" z to the power of 3 is " + p3);
      double p4 = Math.pow(3,z);
      System.out.println(" 3 to the power of z is " + p4);
      double p5 = Math.pow(w,x);
      System.out.println(" w to the power of x is " + p5);
      double p6  = Math.pow(x,w);
      System.out.println("x to the power of w is " + p6);
      double p7 = Math.pow(-x,2);
      System.out.println(" (-x) to the power of 2 is " + p7);
      double p8 = Math.pow(w,-1);
      System.out.println(" w to the power of -1 is " + p8);
      double p9 = Math.pow(Math.PI,Math.E);
      System.out.print("Math.PI to the power of Math.E is " + p9);
      double r1 = Math.ceil(2.0001);
      System.out.println("2.0001 rounded up is" + Math.ceil(2.001));
      double r2 = Math.floor(2.9999);
      System.out.println("2.9999 roounded down is " + Math.floor(2.9999));
      double r3 = Math.round(2.5);
      System.out.println("2.5 rounded to the nearest integer is" + Math.round(2.5));
      double r4 = Math.round(2.4999);
      System.out.println("2.4999 rounded to tthe nearesr integer is " + Math.round(2.4999));
      double r5 = Math.round(Math.PI);
      System.out.println(" Math.PI rrounded to the nearest integer is " + Math.round(Math.PI));
      double r6 = Math.round(Math.E);
      System.out.println("Math.E rounded to the nearest integer is " + Math.round(Math.E));
      
      
      
     
      
      
      






		System.out.println();
	}
}
