# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: SINGARAVETRIVEL S
RegisterNumber: 212222220048 
*/
```

## Sourcecode.java:
```
import java.util.*;

public class Distance
{
    int feet,inches;
    public static void main(String[] args)
    {
        Distance obj1=new  Distance();
        Distance obj2=new  Distance();
        Distance obj3=new  Distance();
        Scanner sc=new Scanner(System.in);
        obj1.feet=sc.nextInt();
        obj1.inches=sc.nextInt();
        obj2.feet=sc.nextInt();
        obj2.inches=sc.nextInt();
        
        
        obj3.feet=(obj1.feet+obj2.feet);
        obj3.inches=(obj1.inches+obj2.inches);
        System.out.println("Total Distance is "+obj3.feet+" feet and "+obj3.inches+" inches");
        
    }
}
```
## OUTPUT:
![{4409D395-7C76-439B-B004-FAD388BCA5B4}](https://github.com/user-attachments/assets/95a9c506-b39d-4144-8b4f-3c9c052cd9a5)



## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
