
# Exp No - 5 

## TITLE :  Strings and Math Operations

### AIM : To calculate the power of a number using the built-in Math.pow() function.

### ALGORITHM :

STEP 1 : Start

STEP 2 : Read base and exponent values

STEP 3 : Calculate result = base^exponent using Math.pow()

STEP 4 : Display the result

STEP 5 : End

### PROGRAM :
```
import java.util.Scanner;
public class PowerCalculator {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        double base = sc.nextDouble();
        double exponent = sc.nextDouble();
        double result = Math.pow(base, exponent);
        System.out.println(base + " raised to the power of " + exponent + " is: " + result);
    }
}
```

### OUTPUT :

<img width="914" height="251" alt="image" src="https://github.com/user-attachments/assets/61520c93-4445-4aa7-9c1e-a4bad0cc2a1b" />

### RESULT :

Thus to calculate the power of a number using the built-in Math.pow() function was successfully created.
