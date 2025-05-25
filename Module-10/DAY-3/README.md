# Ex.No:10(C)             JAVA LIST INTERFACE
 ## AIM :

To Create a List interface implemented arraylist class , adding n elements to object of two List interface and print all the elements inside the List interface object.Check the two lists are equal or not.


## ALGORITHM :

1. Create a `Scanner` to take input.
2. Read integer `n` (size of first list) and store `n` integers in `list1`.
3. Read integer `m` (size of second list) and store `m` integers in `list2`.
4. Print both lists.
5. Compare `list1` and `list2` using `.equals()` method.
6. If equal, print `"Equal"`; otherwise, print `"Not equal"`.


## PROGRAM:
 ```
/*
Program to implement a JAVA LIST INTERFACE using Java
Developed by: AKSHAYAA M
RegisterNumber:  212222230009
*/
```

## Sourcecode.java:
```java
import java.util.*;
public class main{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        ArrayList<Integer>list1=new ArrayList<>();
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            list1.add(sc.nextInt());
        }
        ArrayList<Integer>list2=new ArrayList<>();
        int m=sc.nextInt();
        for(int i=0;i<m;i++)
        {
            list2.add(sc.nextInt());
        }
        System.out.println(list1);
        System.out.println(list2);
        if(list1.equals(list2))
          System.out.print("Equal");
        else
          System.out.print("Not equal");
}
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/3b84ce63-2094-49df-9653-b08595e154e9)


## RESULT:
Thus the java program implemented a List interface for array list was executed and verified successfully.










