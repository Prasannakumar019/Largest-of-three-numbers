# Largest-of-three-numbers
## Aim:
To find the largest of three numbers
## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop
## Program:
```
using System;  
public class Exercise8  
{  
    public static void Main()
{
    int num1, num2, num3;
    Console.Write("\n\n");
    Console.Write("Find the largest of three numbers:\n");
    Console.Write("------------------------------------");
    Console.Write("\n\n");

    Console.Write("Input the 1st number :");
    num1 = Convert.ToInt32(Console.ReadLine());
    Console.Write("Input the  2nd number :");
    num2 = Convert.ToInt32(Console.ReadLine());
    Console.Write("Input the 3rd  number :");
    num3 = Convert.ToInt32(Console.ReadLine());
 
  if (num1 > num2)
    {
        if (num1 > num3)
        {
            Console.Write("The 1st Number is the greatest among three. \n\n");
        }
        else
        {
            Console.Write("The 3rd Number is the greatest among three. \n\n");
        }
    }
    else if (num2 > num3)
        Console.Write("The 2nd Number is the greatest among three \n\n");
    else
        Console.Write("The 3rd Number is the greatest among three \n\n");
}
}
```

## Output:
![Screenshot from 2022-04-13 04-10-42](https://user-images.githubusercontent.com/75235090/163098831-43226b0f-c1d9-4140-bb9a-647c489617bc.png)

## Result:
Thusthe largest of three numbers is found using C#
