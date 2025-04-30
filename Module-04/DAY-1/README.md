# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create a Java program using constructor to print the area of rectangle.[l=5,w=6]

## ALGORITHM :

1. Define a `Rectangle` class with two integer attributes: `length` and `breadth`.  
2. Create a parameterized constructor to initialize the rectangle’s dimensions.  
3. Create a copy constructor that copies dimensions from another `Rectangle` object.  
4. Define a method `area()` that returns the product of `length` and `breadth`.  
5. In the `CopyConstructor` class, create an object `firstRect` using the parameterized constructor.  
6. Create another object `secRect` by copying `firstRect` using the copy constructor.  
7. Print the area of `firstRect` using the `area()` method.  
8. Print the area of `secRect` using the `area()` method.  


## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: AKSHAYAA M
RegisterNumber: 212222230009
*/
```

## Sourcecode.java:
```java
class Rectangle 
 { 
         int length; 
         int breadth; 
         
         Rectangle(int l, int b) 
         {  
             this.length = l;
             this.breadth = b;
         } 
        
         Rectangle(Rectangle obj) 
         { 
             this.length = obj.length;
             this.breadth = obj.breadth;
    
         } 
        
        int area() 
        { 
           return length*breadth;
        } 
 } 
        //class to create Rectangle object and calculate area 
public class CopyConstructor 
 { 
           public static void main(String[] args) 
           { 
             Rectangle firstRect = new Rectangle(5,6);
             Rectangle secRect = new Rectangle(firstRect);
             System.out.println("Area  of First Rectangle : "+firstRect.area());
             System.out.println("Area of First Second Rectangle : "+secRect.area());
             
             
           } 
 } 
 
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/0994c773-3a4f-4807-81fe-070ff954b4c1)

## RESULT:
Thus the Java program using constructor to print the circumference of rectangle was executed successfully.
