# Ex.No:1(D) ARRAYS

## QUESTION:
<img width="680" height="375" alt="image" src="https://github.com/user-attachments/assets/1853b602-0e93-4ad0-a3c9-683a968e777a" />


## AIM:
To write a Java Program to Find the Average of Array Elements.

## ALGORITHM :
1️.Start
2️. Declare variables:
    • Integer n for number of elements
    • Integer array arr[]
    • Integer sum = 0
    • Double average

3️. Input the number of elements n.

4️. Create an array arr of size n.

5️. Read n elements from the user and store them in the array.

6️. Repeat for each element in the array:
    • Add the element to sum.

7️. Calculate the average using the formula:
    average = sum / n

8️. Print the result as:
    The average of elements is {average}

9️. Stop	.

## PROGRAM:

## Developed by: B.VIMALRAJ
## RegisterNumber: 212224230304 


## SOURCE CODE:

```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner s = new Scanner(System.in);
        int n = s.nextInt();
        int a[] = new int[n];
        for(int i=0;i<n;i++){
            a[i] = s.nextInt();
        }
        double sum=0;
        double avg=0;
        for(int num:a){
            sum+=num;
        }
        avg = sum/n;
        System.out.printf("The average of elements is %.2f",avg);
    }
}
```
## OUTPUT:

<img width="977" height="686" alt="image" src="https://github.com/user-attachments/assets/6d4bdab4-d82d-47f1-bad2-8b5e6369bdf2" />


## RESULT:

Thus,the program was executed Successfully.
