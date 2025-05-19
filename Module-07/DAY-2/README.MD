# Ex.No:7(B) EXCEPTION HANDLING-FINALLY
## AIM:
To Write a Java program to demonstrate control flow of try-catch-finally clause when ArrayIndexOutOfBounds Exception occur in try block and handled in catch block


## ALGORITHM :

1. Create an integer array of size 4 → `int[] arr = new int[4];`

2. Inside `try` block:

   * Try to access `arr[4]` (invalid index)
   * This throws an `ArrayIndexOutOfBoundsException`.

3. Control moves to the `catch` block:

   * It catches the exception and prints:
      `"Exception caught in catch block"`

4. `finally` block is always executed:

   * It prints:
      `"finally block executed"`

5. After try-catch-finally, the program continues:

   * It prints:
      `"Outside try-catch-finally clause"`

## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Finally using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009 
*/
```

## Sourcecode.java:

```java
import java.util.*;
public class HelloWorld {
    public static void main(String[] args) 
    {
      // array of size 4.
        int[] arr = new int[4];
         
        try
        {
            int i = arr[4];
            System.out.println("Inside try block");
        }
         
        catch(ArrayIndexOutOfBoundsException ex)
        {
            System.out.println("Exception caught in catch block");
        }
         
        finally
        {
            System.out.println("finally block executed");
        }
         
        System.out.println("Outside try-catch-finally clause");
    }
}

```

## OUTPUT:

![image](https://github.com/akshayaamanagal/19AI307_JAVA/blob/88c0aa692eb41a2ec8115d49dd268cc7809ea4a4/Module-07/DAY-2/image.png)
## RESULT:
Thus the Java program to demonstrate control flow of try-catch-finally clause when ArrayIndexOutOfBoundsException occur in try block and handled in catch block was executed successfully.



