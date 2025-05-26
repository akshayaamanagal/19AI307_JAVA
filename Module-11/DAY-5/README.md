# Ex.No:11(E)  JAVA HASHMAP

## AIM:
To demonstrate removing a key from a HashMap and printing all remaining key-value pairs
## ALGORITHM :

a.	Import java.util.*.
b.	Create a HashMap and add some key-value pairs.
c.	Use remove(key) to delete the entry with key 100.
d.	Iterate through the map using a for-each loop and display the entries

## PROGRAM:
 ```
/*
Program to implement a HASHMAP
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
        HashMap<Integer,String> map=new HashMap<Integer,String>();
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            int a=sc.nextInt();
            String b=sc.next();
            map.put(a,b);
            
        }
        for(Map.Entry<Integer,String> entry :  map.entrySet())
        {
            System.out.println(entry.getKey()+" "+entry.getValue());
        }
        String result=map.get(100);
        System.out.println("value: "+result);
    }
}
```

## OUTPUT:


![image](https://github.com/user-attachments/assets/a741299b-d92b-4c03-9d2d-d50eee67e53c)

## RESULT:
Thus the java program was successfully removes the key 100 from the HashMap and displays the remaining key-value pairs.




