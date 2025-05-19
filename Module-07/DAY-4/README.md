# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To Develop a Java Program to perform static synchronization method for the below Scenario Create a Class Display with synchronized void wish method in that perform "Welcome : Message. Note :Assume Sleep as 400 ms i.e Thread.Sleep(400)
 
## ALGORITHM :
1.	1.	Start the Program.
2.	Define class `Display`:
-	a) Create a `Scanner` object `sc` for input
-	b) Define a synchronized method `wish(String str)`:
- i) Print "Welcome :: " followed by `str` (twice)
3.	End



## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
class Display{
    void wish(String n){
        synchronized (this){
            for(int i=1;i<=2;i++)
            System.out.println("Welcome :: "+n);
            try{
                Thread.sleep(400);
            }
            catch(Exception e){
                System.out.println(e);
            }
        }
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/a1f1bce6-5672-4a0a-91c8-a98bd911c9a0)


## RESULT:
Thus the java program for synchronization was executed successfully.

