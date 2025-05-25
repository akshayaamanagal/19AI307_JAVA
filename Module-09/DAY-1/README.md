# Ex.No:9(A)          DATA I/O STREAM
## AIM:
To create a Java Program to write a integer '65' in a file "testout.txt" using DataOutputStream.

## ALGORITHM :

1. Create a `FileOutputStream` to write to `"testout.txt"`.
2. Wrap it with a `DataOutputStream`.
3. Write the integer value `65` to the file using `writeInt()`.
4. Close the `DataOutputStream` and `FileOutputStream` to release resources.
5. Print a success message: `"Successfully Completed"`.

## PROGRAM:
 ```
/*
Program to implement a DATA I/O STREAM using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
FileOutputStream fout=new FileOutputStream("testout.txt");    
DataOutputStream dout=new DataOutputStream(fout);
                 dout.writeInt(65);    
                 dout.close();    
                 fout.close();
                 System.out.println("Successfully Completed");
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/7b3f84d9-65ee-4505-abba-bab25225cdee)


## RESULT:
Thus the Java Program to write a integer '65' in a file "testout.txt" using DataOutputStream was executed and verified successfully.

