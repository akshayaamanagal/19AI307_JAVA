# Ex.No:12(A)         JAVA TREE MAP
## AIM:
 To implement a Java program to associate the specified value with the specified key in a Tree Map.

## ALGORITHM :

1.	Start the Program
2.	Import `java.util.*` and `java.util.Map.Entry`
3.	Define `Example6` class with `main` method:
-	a) Initialize `TreeMap<String, String> tree_map1`
-	b) Read integer `size` for entries count.
4.	Use a loop to:
-	a) Read `String` values `n1` and `s1`
-	b) Insert each pair into `tree_map1`
5.	Print `tree_map1` as `"Original TreeMap content: "`
6.	Define `sort_key` class that implements `Comparator<String>`:
-	Override `compare` method to compare `String` values `str1` and `str2` using
`compareTo`
7.	End



## PROGRAM:
 ```
/*
Program to implement a JAVA TREE MAP using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
import java.util.*;
public class java
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        TreeMap<Integer,String> tm=new TreeMap<Integer,String>();   
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            Integer a=sc.nextInt();
            String b=sc.next();
            tm.put(a,b);
        }
        for(Map.Entry m:tm.entrySet())
        {
            System.out.println(m.getKey()+"=>"+m.getValue());
        }

    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/0f1056f1-3c26-460a-95ff-d7459f77ca18)


## RESULT:
Thus the Java program to associate the specified value with the specified key in a Tree Map was executed successfully.
