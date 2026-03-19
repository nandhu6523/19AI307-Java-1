
# Exp No - 2

## TITLE : Conditional Statement

### AIM :
To check a number and display different messages based on its divisibility by 3 and 5.

### ALGORITHM :
STEP 1 : Start

STEP 2 : Read an integer n

STEP 3 : If n is divisible by both 3 and 5 → print "Skipped"

STEP 4 : Else if n is divisible by 3 → print "Beware!"

STEP 5 : Else if n is divisible by 5 → print "Blessings!"

STEP 6 : Else → print "Floor n"

STEP 7 : End

### PROGRAM :
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner (System.in);
        int n=sc.nextInt();
        if(n%3==0 && n%5==0)
        {
            System.out.println("Skipped");
        }
        else if (n%3==0)
        {
            System.out.print("Beware!");
        }
        else if (n%5==0)
        {
            System.out.println("Blessings!");
        }
        else
        {
            System.out.println("Floor "+n);
        }
    }
}
```

### OUTPUT :

<img width="459" height="289" alt="image" src="https://github.com/user-attachments/assets/e5324256-7f60-4310-abe0-1d9df840385d" />

### RESULT :

Thus To check a number and display different messages based on its divisibility by 3 and 5 the was successfully created.
