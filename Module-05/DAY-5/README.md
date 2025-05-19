# Ex.No:5(E) GETTER AND SETTER METHOD
## AIM:
To implement a java program for square of given numbers using getter and setter method.
## ALGORITHM :

1. Import Scanner for taking user input.

2. Create a class named `Square`.

3. Inside `Square`, make:

   * A variable to store a number.
   * A method to set the number.
   * A method to print its square.

4. In the `main` class:

   * Take input from the user.
   * Set the number using the `Square` object.
   * Print the square using the `get()` method.
   * 
## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
import java.util.*;
class Square
{
    private int n;
    
    public void set(int n)
    {
        this.n=n;
    }
    
    public void get()
    {
        int sqr = n * n;
        System.out.println("Square of "+n+" is: "+sqr);
    }
}
public class main
{
    public static void main(String [] args)
    {
        Scanner sc = new Scanner(System.in);
        Square s = new Square();
        s.set(sc.nextInt());
        s.get();
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/a19e4497-13ef-40ae-a4a0-97f7e661cbea)


## RESULT:
Thus the java program for square of given numbers using getter and setter method was executed successfully. 

