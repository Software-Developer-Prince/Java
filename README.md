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

  class Main {
    public static void main(String[] args) {
        int n = 5;
        int spaces = 4 * n - 4;
        for (int i = 0; i < n; i++) {
            System.out.print("* ");
        }
        System.out.println();
        for (int i = 2; i < n; i++) {
            for (int j = 0; j < spaces / 2; j++) {
                System.out.print(" ");
            }
            System.out.println("*");
        }
        for (int i = 0; i < spaces / 2; i++) {
            System.out.print(" ");
        }
        for (int i = 0; i < n; i++) {
            System.out.print("* ");
        }
        System.out.println();
        for (int i = 2; i < n; i++) {
            for (int j = 0; j < spaces; j++) {
                System.out.print(" ");
            }
            System.out.println("*");
        }
        for (int i = 0; i < spaces; i++) {
            System.out.print(" ");
        }
        for (int i = 0; i < n; i++) {
            System.out.print("* ");
        }
        System.out.println();
    }
}


output
* * * * * 
          *
          *
          *
          * * * * * 
                    *
                    *
                    *
                    * * * * *   

 class Main {
    public static void main(String[] args) {
        int n = 5;

       
        int spaces = 4 * n - 2;

       
        for (int i = 0; i < spaces; i++) {
            System.out.print(" ");
        }
        for (int i = 0; i < n; i++) {
            System.out.print("* ");
        }
        for (int i = 0; i < n; i++) {
            System.out.print("# ");
        }
        System.out.println();

        
        for (int i = 0; i < n; i++) {
            for (int j = 0; j < spaces; j++) {
                System.out.print(" ");
            }
            System.out.println("*");
        }

        for (int i = 0; i < n; i++) {
            for (int j = 0; j < spaces; j++) {
                System.out.print(" ");
            }
            System.out.println("#");
        }

        for (int i = 0; i < n; i++) {
            System.out.print("* ");
        }
        for (int i = 0; i < n; i++) {
            System.out.print("# ");
        }
        System.out.println();
    }
}

output
                  * * * * * # # # # # 
                  *
                  *
                  *
                  *
                  *
                  #
                  #
                  #
                  #
                  #
* * * * * # # # # #
       
public class Main {
    public static void main(String[] args) {
        int n = 5;

        // Calculate the number of spaces needed for indentation
        int spaces = 4 * n - 2;

        // Print the bottom row of stars and hashes without additional indentation
        for (int i = 0; i < n; i++) {
            System.out.print("* ");
        }
        for (int i = 0; i < n; i++) {
            System.out.print("# ");
        }
        System.out.println();

        // Print the middle section of vertical hashes with dynamic indentation
        for (int i = 0; i < n; i++) {
            for (int j = 0; j < spaces; j++) {
                System.out.print(" ");
            }
            System.out.println("#");
        }

        // Print the middle section of vertical stars with dynamic indentation
        for (int i = 0; i < n; i++) {
            for (int j = 0; j < spaces; j++) {
                System.out.print(" ");
            }
            System.out.println("*");
        }

        // Print the top row of stars and hashes with dynamic indentation
        for (int i = 0; i < spaces; i++) {
            System.out.print(" ");
        }
        for (int i = 0; i < n; i++) {
            System.out.print("* ");
        }
        for (int i = 0; i < n; i++) {
            System.out.print("# ");
        }
        System.out.println();
    }
}
                 


