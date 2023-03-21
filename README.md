# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:

## Program:
```
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
            s = s.ToLower();
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
![ex2 c#](https://user-images.githubusercontent.com/94165415/226587386-db109886-ecd0-4d76-97b6-e61df1a6a132.png)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
