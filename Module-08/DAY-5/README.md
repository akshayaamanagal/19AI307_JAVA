# Ex.No:8(E)  INPUT STREAM READER.

## AIM:
To write a Java program for Reading data from console by InputStreamReader and BufferedReader
## ALGORITHM :

1. Import required classes (`java.io.*` and `java.util.*`).
2. Define the main class `display`.
3. In the `main` method:

   * Create a `BufferedReader` to read input from the user.
   * Read a line of text and store it in string `s`.
   * Print `"Welcome: "` followed by the input string.

## PROGRAM:
 ```
/*
Program to implement a INPUT STREAM READER
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
import java.io.*;
import java.util.*;
public class display
{
    public static void main(String [] args)throws IOException
    {
        BufferedReader b = new BufferedReader(new InputStreamReader(System.in));
        String s = b.readLine();
        System.out.println("Welcome: "+s);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/41b7f96c-a10f-4017-b038-b5dd52a7914b)


## RESULT:
Thus, the java program uses InputStreamReader and BufferedReader to read input and print it. 

