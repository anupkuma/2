2
=

Program to reverse a String.



Here we will create an empty string named reverse. Now using For loop, we scan through the user input in reverse order, taking each character one by one and adding the characters to variable reverse.
import java.util.Scanner;

public class Program1 {

  public static void main(String args[]) {
		
		Scanner in = new Scanner(System.in);
		System.out.println("Enter a string");
		String str = in.nextLine();
		System.out.println("You enterd " + str);

		String reverse=" ";
		int len = str.length();
		for(int i= len-1;i>=0;i--){
			reverse = reverse + str.charAt(i);
		}

		System.out.println("String in reverse is " + reverse);

	}
}
