import java.util.Scanner;
import java.lang.Math;
public class Lab2 {
	public static void main(String[] args) {
	    Scanner keyBoard = new Scanner (System.in);//we need to import the java scanner utility
	    System.out.println("Please enter your values starting with Byte, then Short, Int, Long, Float, Double, Boolean and finally Char");
		Byte myByte = keyBoard.nextByte();
		System.out.println("My byte is " + myByte + " its type is Byte");
		
	    short myShort = keyBoard.nextShort();
	    System.out.println("My short is " + myShort + " its type is Short");
	    
	    int myInt = keyBoard.nextInt();
	    System.out.println("My int is " + myInt + " its type is Integer");
	    
	    long myLong = keyBoard.nextLong();
	    System.out.println("My long is " + myLong + " its type is Long");

			// The floating-point types: float, double

		float myFloat = keyBoard.nextFloat();
		System.out.println("My float is " + myFloat + " its type is Float");
		
		double myDouble = keyBoard.nextDouble();
		System.out.println("My double is " + myDouble + " its type is Double");

			// The other types: boolean, char

	    boolean myBoolean = keyBoard.nextBoolean();
	    System.out.println("My boolean is " + myBoolean + " its type is Boolean");
	    
	    char myChar = (keyBoard.next()).charAt(0);
	    System.out.println("My char is " + myChar + " its type is Char");

			// Arithmetic operators:
			// +, -, *, /, %
			
			// When an expression involves two values of different types, the 
			// higher-precision type is used as the result. The less-precise value
			// is "up-cast" or COERCED into the higher-precision.
			
			double pi = 3.14159;
			
			
			double twoPi = pi * 2;
			// pi is of type double; 2 is of type int
			// 2 is coerced to a double, and the product is evaluated as a double.
			
			/*
			 * WARNING!!!
			 * Integer division in Java by default drops remainders, like Python's
			 * two-slash (//) operator. 
			 * 
			 * Floating-point division is like Python.
			 */
			int x = 17 / 3; // What is x?

	    System.out.println("x is " + x);

			int y = 17 % 3; // What is y?

	    System.out.println("y is " + y);
		
			
			// We can convert from one type to another with a "cast", similar to 
			// converting in Python with functions like float() or int().
			double z = (double)x / y; // What is z?

	    System.out.print("z is " + z);
	    keyBoard.close();
	}
}

