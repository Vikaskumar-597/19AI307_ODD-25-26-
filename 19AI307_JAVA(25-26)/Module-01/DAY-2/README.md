# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
<img width="787" height="431" alt="image" src="https://github.com/user-attachments/assets/b4b21d78-dadc-4089-986d-5e832ca4f289" />


## AIM:
To write a Java program to simulate this elevator logic for a given floor number.


## ALGORITHM :
```
1.Start
2️. Declare an integer variable floor.
3️. Input the floor number from the user.
4️. Check if the floor number is divisible by both 3 and 5
    • If floor % 3 == 0 and floor % 5 == 0 → Print "Skipped"
5️. Else check if the floor number is divisible by 3 only
    • If floor % 3 == 0 → Print "Beware!"
6️. Else check if the floor number is divisible by 5 only
    • If floor % 5 == 0 → Print "Blessings!"
7️. Else
    • Print "Floor {floor}"
8️. Stop
```




## PROGRAM:

## Developed by: B.VIMALRAJ
## RegisterNumber:  212224230304



## SOURCE CODE:

```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner in = new Scanner(System.in);
        int floor = in.nextInt();
        if (floor%3==0 && floor%5==0)
         System.out.println("Skipped");
        else if(floor%3==0)
         System.out.println("Beware!");
        else if (floor%5==0)
         System.out.println("Blessings!");
        else
         System.out.println("Floor "+floor);
    }
}
```

## OUTPUT:

<img width="569" height="462" alt="image" src="https://github.com/user-attachments/assets/1cb8849f-a7e4-401c-824f-0a79c45bd1ae" />


## RESULT:

Thus,the program was executed Successfully.

