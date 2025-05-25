# Ex.No:9(E) DATA I/O

## AIM:
To write a Java program to displaying number of bytes & read the integer and character data in the  file "OutputFile.txt" using DataInputStream.
## ALGORITHM :

a.	Start the program.
b.	Import java.io.* and java.util.Scanner.
c.	Create a Scanner object to read input from the user.
d.	Read a string from the user.
e.	Create a StringWriter object.
f.	Write the string to the StringWriter object.
g.	Convert the StringWriter content to a string using .toString().
h.	Print the result on the output screen.
i.	Close the writer.
j.	End the program.


## PROGRAM:
 ```
/*
Program to implement a DATA I/O
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
FileInputStream f1 = new FileInputStream("OutputFile.txt");
DataInputStream di = new DataInputStream(f1);
System.out.println("Available number of bytes to read: "+di.available());
System.out.println("Read UFT: "+di.readUTF());
System.out.println("Read int: "+di.readInt());
System.out.println("Read char: "+di.readChar());
di.close();
f1.close();
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/d79bdfad-cf0f-455b-a4db-5fcd18d7777c)


## RESULT:
Thus, implementation of  a Java program was successfully executed.

