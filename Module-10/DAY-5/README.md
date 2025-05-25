# Ex.No:10(E)  JAVA LIST INTERFACE

## AIM:
To write a Java program using LinkedList to implement the hashcode in list interface.Create a list and read 5 elements and display the 5 elements , hashcode for the list.
## ALGORITHM :

1. Create a `Scanner` to read input.
2. Initialize a `LinkedList` of integers.
3. Read 5 integers from user input and add them to the list.
4. Print the contents of the list.
5. Compute the hash code of the list using `.hashCode()`.
6. Print the hash code value.


## PROGRAM:
 ```
/*
Program to implement a LINKEDHASH SET
Developed by: AKSHAYAA M
RegisterNumber:  212222230009
*/
```

## Sourcecode.java:
```java
import java.util.*;

public class Main {
  public static void main(String[] args) {
   Scanner sc=new Scanner(System.in);
    List<Integer> l=new LinkedList<>();
    for(int i=0;i<5;i++)
    {
     l.add(sc.nextInt());
    }
    
    System.out.println(l);
    int hash = l.hashCode();
    System.out.println(hash);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/721c930b-6e55-4d2f-92d3-d45080ac0537)


## RESULT:

Thus the java program to implement the hashcode in list interface.Create a list and read 5 elements and display the 5 elements , hashcode for the list was successfully executed.
