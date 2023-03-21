# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
### Step 1:
Create a new Class named admission.
### Step 2:
Create variable of respective data types to store marks & name.
### Step 3:
Calculate the total and store it.
### Step 4:
The Conditions for admission are:
1. Marks in maths >= 65 & Marks in physics >=55 & Marks in chemistry >=50
2. Total marks in all three subjects >= 180 or total in maths and physics >= 140
### Step 5:
Using Nested if check whether the person is eligible or not for admission based on above conditions.
### Step 6:
Print the status for admission.
### Step 7:
End of the Program.

## Program:
Developed by: Shankar Saradha
Register Number: 212221240052
```c#
using System;

namespace exp1
{
    class Eligibility
    {
        static void Main(string[] args)
        {
            string name;
            int math, phy, chem;
            Console.Write("Enter your name:");
            name = Console.ReadLine();
            Console.Write("Enter Maths Marks:");
            math = Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter Physics Marks:");
            phy = Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter Chemistry Marks:");
            chem = Convert.ToInt32(Console.ReadLine());
            int Sum = math + phy + chem;
            int MPTot = math + phy;
            if (math >= 65 && phy >= 55 && chem >= 50)
            {
                if (Sum >= 180 || MPTot >= 140)
                {
                    Console.WriteLine(name + " is eligible for admission to an engineering course.");
                }
                else
                {
                    Console.WriteLine(name + " is not eligible for admission to an engineering course due to insufficient marks.");
                }
            }
            else
            {
                Console.WriteLine(name + " is not eligible for admission to an engineering course due to insufficient marks.");
            }
            Console.Read();
        }
    }
}
```




## Output:

![c# output](https://user-images.githubusercontent.com/93978702/225874408-7d24472b-0c5e-43fb-82a3-49f63fbe7b92.png)


## Result:
Hence the output for the c# program has been executed and run successfully.
