# Ex.No:1(D) USER DEFINED METHOD.

## AIM:
To create a Java program print area of square by defining instance method and local variable.[Class Name is ‘Area’ function name is ‘calculateArea()’ and return type of function is ’void’]

## ALGORITHM :

1.	Start the program.
2.	Define a class named 'Area'
3.	Declare a void method named 'calculateArea' with no parameters
4.	Inside the 'calculateArea' method:
a)	Declare a Double variable 'side' 
b)	Declare a Double variable 'cirarea'
c) Create an instance for the 'Scanner' class called 'sc' 
d) Assign the user input to the Double variable 'side'
e)	Calculate the area by multiplying 'side' and 'side' and store the result in a Double variable 'cirarea'
f)	Print the calculated area using the System.out.println statement
6.	Define the 'main' method as static
7.	Inside the 'main' method:
a)	Create an instance of the 'Area' class called 'obj'
b)	Call the 'calculateArea' method on the 'obj' object

## PROGRAM:
 ```
/*
Program to implement a User Defined Method using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
import java.util.*;
public class Area {
        void calculateArea()
       {
        double side,cirarea;
        Scanner sc=new Scanner(System.in);
        side=sc.nextDouble();
        cirarea=side*side;
        System.out.println("Area of Square is "+cirarea);
        }
        public static void main(String [] args)
        {
            Area obj = new Area();
            obj.calculateArea();
        }
    
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/48b96bc3-d0c3-40a9-8dbe-571d00d6cd69)


## RESULT:
Thus, the Java program to print area of square by defining instance method and local variable was created successfully.

