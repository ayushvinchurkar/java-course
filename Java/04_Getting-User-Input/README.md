## Reading Data from the Keyboard

The `Scanner` class of the `java.util` package is used to take input from the user's keyboard.  
The `Scanner` class has many methods for taking input from the user depending on the type of input.

To use any of the methods of the `Scanner` class, you first need to create an object of the `Scanner` class, as shown in the example below:

```java
// Importing the Scanner class
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        // Creating an object named "sc" of the Scanner class
        Scanner sc = new Scanner(System.in);

        // Reading an integer input from the keyboard
        System.out.print("Enter an integer: ");
        int a = sc.nextInt(); // Reads an integer from the user

        // Displaying the entered integer
        System.out.println("You entered: " + a);
    }
}
