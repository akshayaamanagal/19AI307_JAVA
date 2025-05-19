# Ex.No:7(A)           EXCEPTION HANDLING-RUN TIME EXCEPTION
## AIM:
  To Develop a Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism.

## ALGORITHM :
1.  Start the Program
2.	Import `java.util.*` for input handling
3.	Define class `Example1`:
-	a) In `main` method, create `Scanner` object `sc` for input
4.	Use `try` block to:
-	a) Read integers `num1` and `num2` from user input
-	b) Calculate `output = a / b` and print "Result: " followed by `output`
5.	Use `catch` block to handle `ArithmeticException`:
-	a) If division by zero occurs, print "You Shouldn't divide a number by zero"
6.	End

## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Run Time Exception using Java
Developed by: AKSHAYAA M 
RegisterNumber: 212222230009 
*/
```

## Sourcecode.java:
```java
import java.util.*;
public class Example1
{
   public static void main(String args[])
   {
      Scanner sc=new Scanner(System.in);
      try{
         int num1=sc.nextInt();
         int num2=sc.nextInt();
         int output=num1/num2;
         System.out.println ("Result: "+output);
      }
      catch(ArithmeticException e){
         System.out.println ("You Shouldn't divide a number by zero");
      }
   }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/e1f51416-4fc6-4199-9448-a796a098638c)


## RESULT:
Thus the Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism was executed successfully.

