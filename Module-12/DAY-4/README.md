# Ex.No:12(D) JAVA QUEUE
## AIM:
To Write a java program to create vector and read the elements for two vector in java collection.(Use equals method )


## ALGORITHM :
1.	Start the Program
2.	Import `PriorityQueue` and `Scanner`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` to read input
-	b) Create a `PriorityQueue` of integers
4.	Read integer `n` from user input for the number of elements
5.	Use a loop to:
-	a) Read integers and add them to the `PriorityQueue`
6.	Check if the `PriorityQueue` is not empty:
-	a) Remove and display the highest-priority element using `poll()`
7.	Display the remaining elements in the `PriorityQueue`
8.	End.





## PROGRAM:
 ```
/*
Program to implement a JAVA QUEUE using Java
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
        Scanner sc=new Scanner(System.in);
        PriorityQueue <Integer> q=new PriorityQueue<>();
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            q.add(sc.nextInt());
        }
        System.out.println("Display the element of Queue:");
        System.out.println(q);
        System.out.println("Display the element of Queue after clear method:");
        q.clear();
        System.out.println(q);
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/a98b6e93-6d9b-48cf-8554-48c20306f897)


## RESULT:
Thus the java program to create vector and read the elements for two vector in java collection.(Use equals method )was executed successfully.


