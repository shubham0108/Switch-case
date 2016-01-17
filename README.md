# Switch-case

import java.util.*;
public class Switch {
	public static void main(String args[])
	{
		String choice;
		Scanner in =new Scanner(System.in);
		
		System.out.println("Enter your choice");
		System.out.println("B->Bombay");
		System.out.println("M->Madras");
		System.out.println("D->Delhi");
		System.out.println("K->Kolkata");
		
		choice=in.nextLine();
		
		switch(choice)
		{
			case "M":
			case "m":System.out.println("Go south for Madras");
				break;
				
			case "b":
			case "B":System.out.println("Go west for Bombay");
				break;
				
			case "d":
			case "D":System.out.println("Go north for Delhi");
				break;
				
			case "k":
			case "K":System.out.println("Go east for Kolkata");
				break;
				
			default:System.out.println("Incorrect choice");
				
		}
		
	}
}
