# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
<img width="1085" height="384" alt="image" src="https://github.com/user-attachments/assets/a6646478-33ae-4567-bc18-e380cb22d4da" />


## AIM:
Write a Java program that prompts the user to enter a non-negative integer and then calculates and displays the factorial of the given number.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3. Input a non-negative integer n from the user.
4. Initialize a variable fact = 1.
5. Repeat a loop from 1 to n and multiply fact = fact × i.
6. Display the value of fact as the factorial of n.
7. Stop the program.





## PROGRAM:
 
## Developed by : B.VIMALRAJ
## RegisterNumber:  212224230304

## SOURCE CODE:

```
import java.util.*;
public class Main{
    public static void main(String[] arg){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        long fact=1;
        if(n==0){
            fact=1;
        }
        else{
            for(int i=n;i>=1;i--){
                fact*=i;
            }
        }
        System.out.println("Factorial of "+n+" is: "+fact);
    }
}
```




## OUTPUT:
<img width="602" height="213" alt="image" src="https://github.com/user-attachments/assets/a1a12f31-2e3e-4fb5-b1e3-0e3ca6924b0b" />

## RESULT:
Thus,the program was executed Successfully.

