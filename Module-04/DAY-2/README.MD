# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To create  a Java program to perform the inheritance concept for employee details.

## ALGORITHM :
1.	Start the Program
2.	Define class `Person`:
-	a) Declare `emp_id`, `name`, and `dept` as instance variables
3.	Define class `Employee` that extends `Person`:
-	a) Define method `getDetails()`:
-	i) Create a `Scanner` object `sc`
-	ii) Read `name`, `emp_id`, and `dept` from user input
-	b) Define method `display()`:
-	i) Print the `name`, `emp_id`, and `dept`
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `getDetails()` to input employee details
-	c) Call `display()` to output employee details
5.	End


## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
import java.util.Scanner;
class Person
{
    String name;
    }
    class Employee extends Person
{
    int Emp_ID;
    String Dept;
    
    void getDetails()
    {
        Scanner sc=new Scanner(System.in);
        name=sc.nextLine();
        Emp_ID=sc.nextInt();
        Dept=sc.next();
   
       
    }
    void display()
    {
       System.out.print("Name: "+name+"Emp_ID: "+Emp_ID+"Department: "+Dept);
    }
}
public class Main
{
    public static void main(String[] args)
    {
        Employee obj=new Employee();
        obj.getDetails();
        obj.display();
    }
}
```

## OUTPUT:

![image](https://github.com/akshayaamanagal/19AI307_JAVA/blob/f2a5f3e569b5d692ba1bce63c0e30cde42c9dd68/Module-04/DAY-2/Screenshot%202025-04-30%20211707.png)

## RESULT:
Thus the Java program to implement the inheritance concept for employee details was  executed successfully.

