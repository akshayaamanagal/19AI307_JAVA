# Ex.No:9(B) BYTE ARRAY I/O
## AIM:
To create a java program to write data using ByteArrayOutputStream.


## ALGORITHM :

1. Define a string `input` with some text.
2. Create a `ByteArrayOutputStream` object.
3. Convert the input string into bytes using `getBytes()`.
4. Write the byte data into the byte array output stream.
5. Convert the output stream back to a string and print it.
6. If an exception occurs, display an error message.

## PROGRAM:
 ```
/*
Program to implement a BYTE ARRAY I/O using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
import java.io.ByteArrayOutputStream;
import java.io.IOException;
import java.util.Scanner;

public class ByteArrayOutputExample {
    public static void main(String[] args) {

        String input = "This is a line of text inside the string.";
        ByteArrayOutputStream byteArrayOutputStream = new ByteArrayOutputStream();

        try {
            byteArrayOutputStream.write(input.getBytes());

            System.out.println("Output stream: " + byteArrayOutputStream.toString());
        } catch (IOException e) {
            System.out.println("An error occurred while writing to the output stream.");
        } 
    }
}
```

## OUTPUT:

![image](https://github.com/akshayaamanagal/19AI307_JAVA/blob/7bece0e2c914fbc82b10781ffe29407ea778523e/Module-09/DAY-2/image.png)

## RESULT:
Thus, java program to write data using ByteArrayOutputStream was executed and verified successfully.





