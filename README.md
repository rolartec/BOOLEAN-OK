BOOLEAN-OK
==========

BOOLEAN PERFECT PROGRAM


//By  Reina Olarte


//	Guessing Number using BOOLEAN

import java.util.Scanner;

import java.util.Random;

public class BooleanFinal2

{
	public static void main( String[]args)
{
//Create the Scanner to input the number
Scanner input = new Scanner(System.in);
//Create the Random number
Random randomNumber = new Random();

//Declaring the variables
int UserNumber;
int computerNumber;
computerNumber = 0 + (int)(Math.random() *10);
boolean GameWon = true;
boolean ResultLow = true;
boolean ResultHigh = true;

System.out.println("Welcome to the Guessing game\nPlease enter a digit from 0 to 10:");
UserNumber = input.nextInt();


if(GameWon=computerNumber == UserNumber)
{
	System.out.println("You Guessed the right number");
	System.out.printf("Your number %d, Random number %d" , UserNumber, computerNumber);
}
else if (ResultHigh=computerNumber < UserNumber)
{
	System.out.println("You Guessed to High");
	System.out.printf("Your number %d, Random number %d" , UserNumber, computerNumber);
}
else if (ResultLow=computerNumber > UserNumber)
{
	System.out.println("You Guessed to Low");
	System.out.printf("Your number %d, Random number %d" , UserNumber, computerNumber);
}

	
}//End main

}//End class
