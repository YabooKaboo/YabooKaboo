import java.util.Scanner;
public class Calculator {
   public static void main(String[] args) {
      double num1;
      double num2;
      double ans;
      char user;
      Scanner reader = new Scanner(System.in);
      System.out.print("Enter two numbers: ");
      num1 = reader.nextDouble();
      num2 = reader.nextDouble();
      System.out.print("\nEnter an operator (+, -, *, /): ");
      user = reader.next().charAt(0);
      switch(user) {
         case '+': ans = num1 + num2;
            break;
       //Type the cases for the other operators here
         default:  System.out.printf("Not an operator!\n");
            return;

      }
   System.out.print("\nThe result is given as follows:\n");
   System.out.printf(num1 + " " + user + " " + num2 + " = " + ans);
   }
}
