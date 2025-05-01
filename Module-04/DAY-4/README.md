# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program to perform final & static keyword for below situation: a final class 'Class' with  Name,Id and Year as its member, make  Year as final variable with value "3th Year" and write  print() to display its member in the Output.Create a Main class and access print() of Company class.[Name- David, Id- S201]
 
## ALGORITHM :

1. Define a `final` class named `Student`, which means it cannot be extended/inherited.
2. Declare a `final` variable `year` with the value `"3th Year"` (note: should be `"3rd Year"` for correct grammar).
3. Declare instance variables `name` and `Id` (not used in logic but declared).
4. Define a method `print(String Id, String name)` to display student details.
5. Inside the `print` method, print the ID, name, and the final year using `this.year`.
6. In the `Main` class, define the `main()` method as the program's entry point.
7. Create an object `obj` of the `Student` class.
8. Call the `print` method with arguments `"S201"` and `"David"`.
9. Output will display the student details, including the hardcoded year.


## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java

final class Student
{
    final String year="3th Year";
    String name;
    String Id;
    void print(String Id,String name)
    {
        System.out.println("Student Details are,");
        System.out.println("Id is "+Id);
        System.out.println("Name is "+name);
        System.out.println("Year of Studying is "+this.year);
        
    }
}
public class Main{
public static void main(String[] args)
{
    Student obj=new Student();
    obj.print("S201","David");
    
}
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/2b75b9bd-1f43-4681-8a32-d32d8f220bfd)


## RESULT:
Thus, the java program to perform final & static keyword was executed successfully.
