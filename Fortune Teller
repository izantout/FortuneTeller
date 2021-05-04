import java.util.Scanner;
public class FortuneTellerProject {
			public static void main(String[] args) {
				
				//Ask the user for inputs
				
				Scanner keyBoard = new Scanner (System.in);
				System.out.println("Please enter an integer from 1 to 10: ");
				int myInt = keyBoard.nextInt();
				System.out.println("Please enter a character from A to I:");
				char myChar = (keyBoard.next()).charAt(0);
				System.out.println("Please enter another integer from 1 to 11:");
				int myInt2 = keyBoard.nextInt();
				String string1 = "";
				String string2 = "";
				String string3 ="";
				
				//Start identifying the cases
				
				//Start by identifying the 1st integer
				
				switch(myInt) {

				case 1:
					System.out.print(":-J ");
					string1 = "have your tongue in your cheek ";
					break;
					
				case 2:
					System.out.print(":-& ");
					string1 = "have your tongue tied ";
					break;
					
				case 3:
					System.out.print("=^_^= ");
					string1 = "are blushing ";
					break;
					
				case 4:
					System.out.print(":-o ");
					string1 = "are alarmed ";
					break;
					
				case 5:
					System.out.print("=-D ");
					string1 = "are laughing out loud ";
					break;
					
				case 6:
					System.out.print(">_< ");
					string1 = "are angry ";
					break;
					
				case 7:
					System.out.print("(*_*) ");
					string1 = "are in love ";
					break;
					
				case 8:
					System.out.print("(-_-) ");
					string1 = "are bored ";
					break;
					
				case 9:
					System.out.print(">_<* ");
					string1 = "are annoyed ";
					break;
					
				case 10:
					System.out.print("(*^_^*) ");
					string1 = "are shy ";
					break;
				
				default:
					System.out.println(myInt + " is an invalid entry.");
					string1 = "";
					
				}
				
				//Identify the character
				switch(myChar) {
				case 'A','a' : //(myChar == 'A' || myChar == 'a');
					System.out.print("*<:) ");
					string2 = "you are wearing your birthday hat ";
					break;
					
				case 'B','b' : //(myChar == 'B' || myChar == 'b');
					System.out.print("0_ ");
					string2 = "you are in bed ";
					break;
					
				case 'C','c' : //(myChar == 'C' || myChar == 'c');
					System.out.print("@~)~~~~ ");
					string2 = "holding a rose ";
					break;
					
				case 'D','d' : //(myChar == 'D' || myChar == 'd');
					System.out.print("<.> ");
					string2 = "putting an eye drop in someones eye ";
					break;
					
				case 'E','e' : //(myChar == 'E' || myChar == 'e');
					System.out.print("-|' ");
					string2 = "in an airplane ";
					break;
					
				case 'F','f' : //(myChar == 'F' || myChar == 'f');
					System.out.print("*<<<<= ");
					string2 = "standing infront of a christmas tree ";
					break;
					
				case 'G','g' : //(myChar == 'G' || myChar == 'g');
					System.out.print("8[+] ");
					string2 = "opening a gift ";
					break;
					
				case 'H','h' : //(myChar == 'H' || myChar == 'h');
					System.out.print("%% ");
					string2 = "searching for a four leaf clover ";
					break;
					
				case 'I','i' : //(myChar == 'I' || myChar == 'i');
					System.out.print("(*)/(*) ");
					string2 = "riding a bicycle ";
					break;
				
				default:
					System.out.println(myChar + " is an invalid entry.");
					string2 = "";
					
				}
				
				switch(myInt2) {
				
				case 1:
					System.out.println("(*V*)");
					string3 = "bird ";
					break;
					
				case 2:
					System.out.println("=^.^=");
					string3 = "cat ";
					break;
					
				case 3:
					System.out.println(":o3");
					string3 = "dog ";
					break;
					
				case 4:
					System.out.println("<><");
					string3 = "fish ";
					break;
					
				case 5:
					System.out.println("<:3)~");
					string3 = "mouse ";
					break;
					
				case 6:
					System.out.println("=8)");
					string3 = "pig ";
					break;
					
				case 7:
					System.out.println(":(|||)");
					string3 = "bee ";
					break;
					
				case 8:
					System.out.println("^o,o^");
					string3 = "owl ";
					break;
					
				case 9:
					System.out.println("(*)>");
					string3 = "penguin ";
					break;
					
				case 10:
					System.out.println("('.')");
					string3 = "rabbit ";
					break;
					
				case 11:
					System.out.println("_@_v");
					string3 = "snail ";
					break;
				
				default:
					System.out.println(myInt2 + " is an invalid entry.");
					string3 = "";
				}
				
				//output the messages and add to them string1, string2, and string3
				if (string1 == "" || string2 == "" || string3 == "" ) {
					System.out.println("\nError message: Invalid entry, here's your money back.");
				}
				else {	
					System.out.println("I see the following:");
					System.out.println("You " + string1 + "while " + string2 + ", " + "and you got a " + string3 + "as a gift.");
				}
				
				keyBoard.close();
			}


		}
