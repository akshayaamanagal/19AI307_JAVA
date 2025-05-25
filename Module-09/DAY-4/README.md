# Ex.No:9(D) TRANSIENT ---SERILIZATION

## AIM:
 To implement a Java program to perform Transient in Employee details in Serializable interface to make its object serialized.

## ALGORITHM :
1.	Get employee name and designation from the user.
2.	Save the Employeeinfo object to emp.txt.
3.	Read the object back from emp.txt.
4.	Print employee name and designation (designation is null due to transient).
5.	Delete File: Delete emp.txt and handle any exceptions while trying to read it.




## PROGRAM:
 ```
/*
Program to implement a Transient using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009 
*/
```

## Sourcecode.java:
```java
import java.io.*;
class Employeeinfo implements Serializable
{
    String name;
    transient String desi;
    Employeeinfo(String n, String r)
    {
    this.name = n;
    this.desi = r;
   
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/990ef410-5694-47ce-b3c1-061d0a6255b1)


## RESULT:
Thus, implementation of a Java program to perform Transient in Employee details in Serializable interface to make its object serialized was executed and verified successfully.

