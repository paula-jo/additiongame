
package addition.game;

import java.util.Scanner; // Importing the Scanner

public class AdditionGame
{
    public static void main(String[] args)
    {
       // Create a scanner 
        Scanner input = new Scanner(System.in);
        int problems;
        int count;
        int correctCount;
        int number1;
        int number2;
        int answer;
        String output = " ";
        
        // Ask user how many addition problems do you want to attempt
        System.out.print("How many problems do you want to attempt to solve? ");
        problems = input.nextInt();
        
        correctCount = 0;
        count = 0;
        while (count < problems) {
        // Generate 2 random number in the range between 10 and 50 inclusive 
        number1 = (int)(Math.random() * 40 + 10);
        number2 = (int)(Math.random() * 40 + 10);
        
        // Prompt the user to enter the sum of these two integers
        System.out.print("What is " + number1 + " + " + number2 + "? ");
        answer = input.nextInt();
        
        // Show correct or incorrect
        if (number1 + number2 == answer) {
            System.out.println("Correct");
            correctCount++;
        }
        else 
            System.out.println("Incorrect. The correct sum is " + (number1 + number2));
        
        //Increase the question count 
        count++;
        
        // Display a running total of how many correct out of how many total problems 
        System.out.println(correctCount + " correct out of " + problems);
        
               
        }
        
    }
    
}
