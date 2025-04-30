# Ex.No:3(E)  STRINGTOKENIZER IN JAVA

## AIM:
To write a Java program that calculate the number of tokens present in the tokenizer string.

## ALGORITHM :


1. The program imports `java.util.*` and `java.util.StringTokenizer` to use classes like `Scanner` and `StringTokenizer`.
2. The `java` class is defined (although naming it `java` is not recommended, as it can be confused with the Java language itself).
3. Inside the `main()` method:
   - A `Scanner` object is used to read an entire line of input from the user and store it in the variable `str`.
   - A `StringTokenizer` object `st` is created using `str`, which splits the string into tokens (words) based on default delimiters (like spaces).
   - The number of tokens is printed using `st.countTokens()`.

## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
import java.util.*;
import java.util.StringTokenizer;
public class java
{
    public static void main(String [] args)
    {
        Scanner sc = new Scanner(System.in);
        String str = sc.nextLine();
        StringTokenizer st = new StringTokenizer(str);
        
        System.out.println("Total number of Tokens: "+st.countTokens());
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/01764030-b283-4e18-a3fb-5097f770fbb7)


## RESULT:
Thus the  Java program successfully creates a StringTokenizer object using the given string and calculate the number of tokens.

