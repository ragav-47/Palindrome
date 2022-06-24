### EX NO : 02
### DATE  : 06.04.2022
# <p align="center">Palindrome</p>


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare two variable with string datatype
### Step3:
Loop over the entire string and reverse it
### Step4:
Use if condition to check whether the string and the reversed string is equal or not
### Step5:
print palindrome if it's equal else print not a palindrome.
### Step6:
stop

<br/><br/><br/><br/><br/><br/><br/>

## Program:
```c#
using System;
namespace palindrome
{
    class Program
    {
        static void Main(string[] args)
        {
            string s, revs = "";
            Console.WriteLine(" Enter string");
            s = Console.ReadLine();
            s=s.ToLower();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                revs += s[i];
            }
            if (revs == s)
            {
                Console.WriteLine("String is Palindrome");
            }
            else
            {
                Console.WriteLine("String is not Palindrome");
            }
        }
    }
}
```
## Output:

![image](https://user-images.githubusercontent.com/75235488/175523746-8de182d7-6c15-4e02-b88d-ed480fb5ad71.png)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
