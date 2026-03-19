
# Exp No - 4

## TITLE : Arrays

### AIM : To calculate the average of n elements using an array.

### ALGORITHM :

STEP 1 : Start

STEP 2 : Read integer n

STEP 3 : Create an array of size n

STEP 4 : Initialize sum = 0

STEP 5 : Read n elements and add each to sum

STEP 6 : Compute avg = sum / n

STEP 7 : Display the average (formatted to 2 decimal places)

STEP 8 : End

### PROGRAM :
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int n= sc.nextInt();
        int[] arr = new int[n];
        int sum=0;
        for(int i=0;i<n;i++)
        {
            arr[i]=sc.nextInt();
            sum+=arr[i];
        }
        double avg=(double) sum/n;
        System.out.printf("The average of elements is %.2f",avg);
    }
}
```

### OUTPUT :

<img width="796" height="491" alt="image" src="https://github.com/user-attachments/assets/06e2b2d5-d9b1-4b71-9d74-c2c42a226940" />

### RESULT :

Thus to calculate the average of n elements using an array was successfully created.
