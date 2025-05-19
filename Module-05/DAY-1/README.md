# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
To Create a java program to display name and location of the employee and use the encapsulation concepts

## ALGORITHM :
1.Start

2.Create the vehicles class:

3.Declare two private variables: vName (vehicle name) and vlocation (vehicle location).

4.Define getter and setter methods for both vName and vlocation.

5.Create the EmployeMain class:

6.Create a Scanner object sc to take user input.

7.Create an object employee of the vehicles class.

8.Use sc.nextLine() to take input for the vehicle name and location, then set these values using setvName() and setLocation() methods.

9.Call getvName() and getLocation() to print the vehicle name and location.

10.End

## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
import java.util.*;
class vehicles {
 private String vName;
 private String vlocation;
 public String getvName() {
  return vName;
 }
 public void setvName(String vName) {
  this.vName = vName;
 }
 public String getLocation() {
  return vlocation;
 }
 public void setLocation(String vlocation) {
  this.vlocation = vlocation;
 }
}

public class EmployeMain {
 public static void main(String[] args) {
    Scanner sc=new Scanner(System.in);
  vehicles employee = new vehicles();
  employee.setvName(sc.nextLine());
  employee.setLocation(sc.nextLine());
  System.out.println(employee.getvName());
  System.out.println(employee.getLocation());
 }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/2b236635-c27f-44be-9b5e-d9c8bc6c22bb)



## RESULT:
Thus , the  java program to display name and location of the employee and use the encapsulation concepts executed successfully.
