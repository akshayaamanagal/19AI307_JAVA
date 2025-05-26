# Ex.No:11(A)         JAVA TREESET
## AIM:
 To develop a Java program to iterate through all elements in a tree set.


## ALGORITHM :
1.	Start
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `TreeSet` named `set` to store integers in sorted order
4.	Use a loop to read `n` integers and add each to `set`
5.	Use an enhanced `for` loop to print each element in `set`
6.	End


## PROGRAM:
 ```
/*
Program to implement a JAVA TREESET using Java
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
        TreeSet <Integer> ts=new TreeSet<>();
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            ts.add(sc.nextInt());
        }
        for(Integer ele : ts)
        {
            System.out.println(ele);
        }
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/294b2233-904b-4872-832f-2851e97b6958)


## RESULT:
Thus the java program to iterate through all elements in a tree set was executed successfully.

