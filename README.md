//# JAVA_core2
//in this repository I added entry level logical coding 
//task: Enter any number by taking user input and print the last digit of that number on screen.

import java.util.*;
	
	public class Q1 {
	static int LastDigit(int N){
	  int rem=N%10;
	  return rem;
	}
	public static void main(String arg[]){
	  Scanner sc= new Scanner(System.in);
	  int N=sc.nextInt();
	  if(N>=1 && N<=10000){
	    Q1 a=new Q1();
	    System.out.println(a.LastDigit(N));
	  }
	  else {
		  System.out.println("Enter the value of N range between 1 to 10000");
	  }
	}
	}

