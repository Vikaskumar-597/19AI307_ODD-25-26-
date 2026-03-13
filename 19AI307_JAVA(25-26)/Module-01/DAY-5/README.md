# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:

<img width="545" height="193" alt="image" src="https://github.com/user-attachments/assets/fd6e9d9c-123e-4200-a1ce-148df5388e0b" />

## AIM:

To write a Java program to reverse a given string.

## ALGORITHM :

```
1️.Start
2️. Declare a string variable str.
3️. Declare another string variable rev and initialize it as an empty string.
4️. Input the string from the user.
5️. Find the length of the string.
6️. Repeat from the last character of the string to the first character:
    • Add each character to the variable rev.
7️. Store the reversed characters in rev.
8️. Print the result as:
    Reversed string: + rev
9️. Stop

```

## PROGRAM:

### Developed by:  Vikaskumar M
### RegisterNumber:  212224220122


## SOURCE CODE:

```
import java.util.Scanner;

public class ReverseString {

    public static String reverse(String str) {
        String reversed = "";
        for (int i = str.length() - 1; i >= 0; i--) {
            reversed += str.charAt(i);
        }
        return reversed;
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String input = sc.nextLine();

        String result = reverse(input);
        System.out.println("Reversed string: " + result);
    }
}

```
## OUTPUT:

<img width="818" height="399" alt="image" src="https://github.com/user-attachments/assets/0bb03b45-6bdb-4e12-9f87-10d030216cd5" />

## RESULT:
Thus , the program was executed Successfully.



