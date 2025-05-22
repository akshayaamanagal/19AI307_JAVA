# Ex.No:8(D) BUFFER INPUT/OUTPUT STREAM

## AIM:
 To create a java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream.

## ALGORITHM :
1.	Import java.io.* and java.util.* for file handling and user input.
2.	Create a file named sample.txt and write "This is a line of text inside the file." using FileWriter.
3.	Close the FileWriter to save the content to sample.txt.
4.	Open sample.txt with a FileInputStream wrapped in a BufferedInputStream for efficient reading.
5.	Prompt the user to enter the number of bytes to skip using Scanner.
6.	Skip the specified number of bytes in the file and print the remaining content.
7.	Close the BufferedInputStream and FileInputStream to release system resources.




## PROGRAM:
 ```
/*
Program to implement a Buffer Input/Output Stream using Java
Developed by: AKSHAYAA M 
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
     FileInputStream f=new FileInputStream("sample.txt");
       BufferedInputStream b=new BufferedInputStream(f);
       Scanner sc=new Scanner(System.in);
       int s=sc.nextInt();
       b.skip(s);
    
    System.out.println("Contents after skipping"+" "+s+" "+"bytes:");
    int a=0;
    while((a=b.read())!= -1)
    System.out.print((char)a);
    b.close();
    f.close();
```

## OUTPUT:


![Screenshot 2025-05-22 112246](https://github.com/user-attachments/assets/ad345ba5-39bc-4239-a0bc-2ecee944b09f)

## RESULT:
Thus, the java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream was executed and done successfully.


