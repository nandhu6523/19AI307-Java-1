# Exp No - 1

## TITLE : Introduction to Java Programming, Data types , Variables and Operators

### AIM :
To read four integer values from the user and generate a “treasure code” by performing a combination of arithmetic operations.

### ALGORITHM :
STEP 1 : Start the program.

STEP 2 : Read four integers a, b, c, d

STEP 3 : Compute (a+b), (c-d), (b*d), (c%a)

STEP 4 : Concatenate the results into a string

STEP 5 : Display the treasure code

STEP 6 : End the program.

### PROGRAM :
```
import java.util.Scanner;
public class Main
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        int c=sc.nextInt();
        int d=sc.nextInt();
        System.out.print("The treasure code is: "+(a+b)+(c-d)+(b*d)+(c%a));
        
    }
}
```

### OUTPUT :

<img width="689" height="352" alt="image" src="https://github.com/user-attachments/assets/a24483a3-feb9-40b4-84c4-026ab2dbbade" />

### RESULT :

Thus the four integer values from the user and generate a “treasure code” by performing a combination of arithmetic operations was successfully created.
 

