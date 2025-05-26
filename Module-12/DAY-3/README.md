# Ex.No:12(C)             JAVA STACK & VECTOR
 ## AIM :

To Write a java program to create vector and read the elements for two vector in java collection.(Use equals method )
## ALGORITHM :

1.	Start the Program
2.	In `main`:
-	a) Create a `Scanner` object to read input.
-	b) Read an integer `n1` (the size of the first vector).
-	c) Initialize `Vector<String> vector1`.
-	d) Use a `for` loop to read `n1` strings and add each to `vector1`.
3.	Repeat similar steps for a second vector:
a)	Read an integer `n2` (size of the second vector).
b)	Initialize `Vector<String> vector2`.
c)	Use a `for` loop to read `n2` strings and add each to `vector2`.
4.	Use `equals()` to compare `vector1` and `vector2` and print whether they are equal.
5.	End.



## PROGRAM:
 ```
/*
Program to implement a JAVA STACK & VECTOR  using Java
Developed by: AKSHAYAA M
RegisterNumber:  212222230009
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
        Vector<String> v=new Vector<>();
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            v.add(sc.next());
            v.add(sc.next());

        }
        System.out.println("The vector is: "+v);
        Enumeration e=v.elements();
        System.out.println("The enumeration of values are:");
        while(e.hasMoreElements())
        {
            System.out.println(e.nextElement());
        }
       
    }
    
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/dad713c3-4954-4379-bab9-35adc11301e9)


## RESULT:

Thus the java program to create vector and read the elements for two vector in java collection.(Use equals method ) was executed successfully.








