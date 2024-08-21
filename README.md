# Java
Java Programming
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter an odd number: ");
        int n = scanner.nextInt(); 
       
        if (n % 2 == 0) {
            System.out.println("Error: The number is not odd.");
            return; 
        }
       
       
        for (int i = 2; i < n; i++) {
            System.out.println("e");
        }
        System.out.print("e");
        for (int i = 0; i < n - 1; i++) {
            System.out.print(" ");
        }
        for (int i = 0; i < n; i++) {
            System.out.print("*");
        }
        System.out.println();

        for (int i = 0; i < n; i++) {
            System.out.print("e");
        }
        for (int i = 0; i < n; i++) {
            System.out.print("*");
        }
        for (int i = 0; i < n; i++) {
            System.out.print("e");
        }
        System.out.println();

        for (int i = 0; i < n; i++) {
            System.out.print(" ");
        }
        for (int i = 0; i < n; i++) {
            System.out.print("*");
        }
        for (int i = 0; i < n - 1; i++) {
            System.out.print(" ");
        }
        System.out.println("e");

        int zSpaces = 3 * n -1;
         for (int i = 2; i < n; i++) {
            for (int j = 0; j < zSpaces; j++) {
                System.out.print(" ");
            }
            System.out.println("e");
        }
       
        
    }
}


output 
e
e
e
e        *****
eeeee*****eeeee
          *****        e
                         e
                         e
                         e


