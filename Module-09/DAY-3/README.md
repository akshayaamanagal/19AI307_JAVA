# Ex.No:9(C)             STRING READER
## AIM:
 To Create a Java Program to display and skip the specified number of characters using the predefined Method Skip in StringReader


## ALGORITHM :
1.  The user enters a string (data) and an integer (skipnumber) indicating the number of characters to skip.
2.	The original string is displayed for reference.
3.	A StringReader object, input, is created to read from data.
4.	The program skips the specified number of characters (skipnumber) in the string.
5.	It reads and displays the remaining characters one by one until the end of the string.
6.	Any exceptions are caught, and stack trace information is generated if an error occurs.


## PROGRAM:
 ```
/*
Program to implement a String Reader using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
import java.util.*;
import java.io.*;
public class main{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        String data=sc.nextLine();
        try{
            StringReader sd=new StringReader(data);
            System.out.println("Original data: "+data);
            sd.skip(5);
            System.out.println("Data after skipping");
            int i=sd.read();
            while(i!=-1)
            {
                System.out.print((char)i);
                i=sd.read();
            }
        }
        catch(Exception e)
        {
            System.out.println(e);
        }
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/110d4c92-3f44-4149-9722-c8613ca54ff6)


## RESULT:
Thus the Java Program to display and skip the specified number of characters using the predefined Method Skip in StringReader was executed and verified successfully.











