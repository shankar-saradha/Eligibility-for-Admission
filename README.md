# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:

## Program:
'''c#
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp2
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int m;
            int p;
            int c;
            int total;
            int total2;
            Console.WriteLine("Enter maths marks;");
            m= Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter physics marks;");
            p = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter chemistry marks");
            c = Convert.ToInt32(Console.ReadLine());
            total = m + p + c;
            total2 = m + p;
            if(m>=65 && p>=55 && c >= 50)
            {
                if (total >= 180 || total2 >= 140)
                {
                    Console.WriteLine("The student is eligible");

                }
                else
                {
                    Console.WriteLine("The student is not eligibile");
                }
            }
            else
            {
                Console.WriteLine("The student is not eligibile");
            }

            Console.Read();

        }
    }
}
'''


## Output:



## Result:
