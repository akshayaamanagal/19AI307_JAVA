# Ex.No:7(E) THREADS IN JAVA

## AIM:
To implement thread in Java to calculate sum of two numbers. 
## ALGORITHM :

1. Import Scanner to take input.

2. Create a class `Multi` that extends `Thread`.

3. Inside the class:

   * Create a `Scanner` object for input.
   * Override the `run()` method:

     * Take two numbers from the user.
     * Calculate their sum.
     * Print the result.

4. In the `main()` method:

   * Create a `Multi` object.
   * Create a `Thread` and pass the object.
   * Start the thread using `start()` → This calls the `run()` method.



## PROGRAM:
 ```
/*
Program to implement a Method Overloading in Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Multi extends Thread
    {  
        Scanner sc = new Scanner(System.in);
        public void run()
        {
           int n1 = sc.nextInt();
           int n2= sc.nextInt();
           int sum = n1+n2;
           System.out.println("Result: "+sum);
        }
        
        
    
    public static void main(String args[])
    {  
        Multi m1 = new Multi();
        Thread t1 = new Thread(m1);
        t1.start();
    }  
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/44df6594-f79d-439e-9768-ca63c9bb6b1a)


## RESULT:

Thus the  java program successfully demonstrates threads in java for calculating sum of two numbers.


