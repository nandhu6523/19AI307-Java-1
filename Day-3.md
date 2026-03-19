
# Exp No - 3

## TITLE : LOOPING STATEMENT 

### AIM : To calculate the factorial of a given number using a loop.

### ALGORITHM :

STEP 1 : Start

STEP 2 : Read integer n

STEP 3 : Initialize fact = 1

STEP 4 : Repeat from i = 1 to n:

STEP 5 : Multiply fact = fact × i

STEP 6 : Display factorial value

STEP 7 : End

### PROGRAM :
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int fact=1;
        int n=sc.nextInt();
        for(int i=1;i<=n;i++)
        {
            fact*=i;
        }
        System.out.println("Factorial of "+n+" is: "+fact);
    }
}
```

### OUTPUT :

<img width="702" height="248" alt="image" src="https://github.com/user-attachments/assets/59bce02e-3e17-4c67-8f55-1ede8b3c06a6" />


### RESULT :

Thus to calculate the factorial of a given number using a loop was successfully created.
