# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To demonstrate how to remove and display the first element from a Deque using the pollFirst() method in Java Collections with String values.
## ALGORITHM :

1.	Import java.util.*.
2.	Create a Deque using LinkedList.
3.	Add several string elements to the deque.
4.	Use pollFirst() to remove and return the first element.
5.	Print the removed element.
6.	Display the remaining elements in the deque.

## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: AKSHAYAA M
RegisterNumber: 212222230009 
*/
```

## Sourcecode.java:
```java
import java.util.*;
public class main
{
    public static void main(String args[])
    {
        Deque<String> dq=new ArrayDeque<>();

       Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            String a=sc.next();
            dq.add(a);
        }
        System.out.println("Display the element of Dequeue:");
        System.out.println(dq);
        dq.removeLast();
        System.out.println(dq);
     
        
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/8fb16a4d-a2c4-437a-9d60-f9af04c66625)


## RESULT:

Thus the java program successfully demonstrates how to use pollFirst() to remove and display the first element from a Deque of strings.


