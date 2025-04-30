# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :

1. Define a class `Vehicle` with a constructor that prints `"I am a Vehicle"`.  
2. Define a class `Car` that extends the `Vehicle` class (i.e., inherits from it).  
3. In the `Car` constructor, call the `super()` method to invoke the `Vehicle` constructor.  
4. After calling the parent constructor, print `"I am a Car"` from the `Car` constructor.  
5. In the `Main` class, define the `main()` method.  
6. Inside `main()`, create an instance of the `Car` class named `c`.  
7. The creation of the `Car` object triggers both the `Vehicle` and `Car` constructors in order.  
8. As a result, `"I am a Vehicle"` is printed first, followed by `"I am a Car"`.  


## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
class Vehicle {

  Vehicle()
  {
      System.out.println("I am a Vehicle");
  }
}

class Car extends Vehicle {
    
    Car()
    {
        super();
        System.out.println("I am a Car");
    }
}
public class Main {
  public static void main(String[] args) {
      
      Car c = new Car();
  
  }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/007e2086-5c91-4215-9aca-065ea6b9b956)


## RESULT:
Thus the java program for constructor chaining was executed successfully.




