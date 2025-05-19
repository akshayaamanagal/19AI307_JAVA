# Ex.No:8(B) IO-FILE READER/WRITER
## AIM:
To create a java program to append a String in a file “testout.txt” using Writer.


## ALGORITHM :

1. Use a `try` block to safely handle file operations.

2. Create a `FileWriter` object for the file `"testout.txt"` with `true` to enable append mode.

3. Use `write()` to add the text `"Hi Everybody"` at the end of the file.

4. Print a success message.

5. Close the `FileWriter` using `close()` to save changes.

6. If any error occurs, the `catch` block will print the exception message.

## PROGRAM:
 ```
/*
Program to implement a IO File Reader/Writer using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009  
*/
```

## Sourcecode.java:
```java
try
{
  FileWriter w1=new FileWriter("testout.txt",true);
  w1.write("Hi Everybody");
  System.out.println("Append the character in the File Successfully");
  w1.close();
}
catch(Exception e)
{
    System.out.println(e);
}
```

## OUTPUT:

![image](
## RESULT:
Thus, the java program to append a String in a file “testout.txt” using Writer.was executed and verified successfully



