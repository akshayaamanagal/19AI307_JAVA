# Ex.No:1(E)  Instance Method

## AIM:
To write a Java program using instance method  to find out if given number is multiples of 3 or not. 

## ALGORITHM:

1. A class named `Age` is defined.
2. An integer variable `n` is declared in the class.
3. The method `check()` is defined to perform the logic.
4. Inside `check()`, a `Scanner` object is created to read input from the user.
5. The input is stored in variable `n`.
6. It checks whether `n` is divisible by 3 using `n % 3 == 0`.
7. If the condition is true, it prints `"Yes"`; otherwise, it prints `"No"`.
8. The `main()` method is defined to create an object `obj` of the class `Age`.
9. The `check()` method is called using the object to execute the logic.

## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: AKSHAYAA M
RegisterNumber:  212222230009
*/
```

## Sourcecode.java:
```java
import java.util.*;
public class Age {
    int n;
    void check()
    {
        Scanner sc = new Scanner(System.in);
        n= sc.nextInt();
        if(n%3==0)
        {
           System.out.println("Yes");
        }
        else
        {
           System.out.println("No");
        }
    }
    public static void main(String[] args) {
       Age obj=new Age();
       obj.check();
    }
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/3a79ed8b-6b56-4e55-818a-f1445cfe6fef)


## RESULT:
Thus, the Java program for the concept of using instance method  to find out if given number is multiples of 3 or not was correctly implemented and verified successfully. 

