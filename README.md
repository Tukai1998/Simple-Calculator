# Simple-Calculator
Java Program to Make a Simple Calculator
import java.util.Scanner;
--------------------------------------------------------------------------------------------------------------------------------------------------------------
class MainRunner {
  public static void main(String[] args) {
        
    Scanner sc = new Scanner(System.in); // create an object of Scanner class  
    System.out.println("Choose an operator: +, -, *, or /");  // ask users to enter operator
    char op= sc.next().charAt(0);
    
    System.out.println("Enter first number"); // ask users to enter numbers
      Double n1 = input.nextDouble();
    System.out.println("Enter second number");
      Double n2 = input.nextDouble();
    
      Double result;
    switch (op) {
      case '+':
        result = n1 + n2;   // performs addition between numbers
        System.out.println(n1 + " + " + n2 + " = " + result);  
        break;
        
      case '-':
        result = n1 - n2;  // performs subtraction between numbers
        System.out.println(n1 + " - " + n2 + " = " + result);
        break;
        
      case '*':
        result = n1 * n2;  // performs multiplication between numbers
        System.out.println(n1 + " * " + n2 + " = " + result);
        break;
   
      case '/':
        result = n1 / n2;  // performs division between numbers
        System.out.println(n1 + " / " + n2 + " = " + result);
        break;

      default:
        System.out.println("Invalid operator!");
        break;
    }

    input.close();
  }
}
