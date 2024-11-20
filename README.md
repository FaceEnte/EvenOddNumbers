# Even or Odd Number

This project involves creating a Java program that reads a number from the console and determines whether the number is even or odd. The program will provide feedback based on the input.

## Objective

Create a Java program that:

- Defines a class with a `main` method.
- Reads an integer from the console.
- Determines if the number is even or odd.
- Outputs the result to the console.

### Example Usage

If the user inputs the number `4`, the program should output:

```
4 is an even number.
```

If the user inputs the number `7`, the program should output:

```
7 is an odd number.
```

### Example Implementation

```java
import java.util.Scanner;

public class EvenOrOdd {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int number = scanner.nextInt();

        if (number % 2 == 0) {
            System.out.println(number + " is an even number.");
        } else {
            System.out.println(number + " is an odd number.");
        }

        scanner.close();
    }
}
```

## Hints

- Use the modulo operator `%` to determine if the number is even or odd.
- Remember to import the `Scanner` class for reading input from the console.
- Ensure to handle invalid inputs (e.g., non-integer values) gracefully.

## Notes

- Document your code with comments to explain the logic behind determining even or odd numbers.
- Test the program with various inputs to ensure it behaves as expected.

Happy coding! 🎉