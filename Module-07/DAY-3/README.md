# Ex.No:7(C)             THREAD IN JAVA
## AIM:
 To Develop a Java program to create Thread using Thread class.


## ALGORITHM :
1.  Start the Program
2.	Import necessary classes: `java.util.*`
3.	Define a class `Multi` that extends `Thread`:
-	a) Create a `Scanner` instance for user input.
-	b) Override the `run` method:
-	i) Read a string from user input.
-	ii) Print "Thread Name:" followed by the input string.
4.	In the `main` method:
-	a) Create an instance of `Multi`.
-	b) Create a new `Thread` instance using the `Multi` object.
-	c) Start the thread with `t1.start()`.
5.	End





## PROGRAM:
 ```
/*
Program to implement a Thread concepts using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
import java.util.*;
public class Threadrun extends Thread{
    private String name;
    Threadrun(String name)
    {
        this.name=name;
    }
    public void run()
    {
        Thread.currentThread().setName(name);
        System.out.print("Thread Name:"+Thread.currentThread().getName());
    }
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        String name=sc.nextLine();
        Threadrun t=new Threadrun(name);
        t.start();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/3b92cb5e-17da-436b-ba0a-dc865e665537)


## RESULT:
Thus the Java program for the creation of Thread using Thread class was executed successfully.







