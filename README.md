# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course.

## Algorithm:
### Step1:
Start by creating a new class.

### Step2:
Initiate the integer variables to assign the marks of Maths, Physics and Chemistry and read the input from the user.

### Step3:
Calculate the first total that sums all the 3 subject marks; and the second total that sums maths and physics marks.

### Step4:
Based on the condition given, check whether the student is eligible for the engineering admission.

### Step5:
Display the output for the input read from the user.

### Step6:
Stop the execution.
## Program:
```
Developed by: Paul Andrew D
Reg no: 212221230075
```
```c#
using System;
namespace Exp1
{
    class Program
    {
        static void Main(string[] args)
        {
            int maths,physics,chemistry,total;
            Console.Write("Enter the marks in maths: ");
            maths=Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter the marks in physics: ");
            physics = Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter the marks in chemistry: ");
            chemistry = Convert.ToInt32(Console.ReadLine());
            total = maths + physics + chemistry;
            if (maths>=65 && physics>=55 && chemistry>=50) {
                
                if(total >= 180 || (maths + physics) >= 140)
                {
                    Console.WriteLine("Candidate is eligible for engineering admission");
                }
                else
                {
                    Console.WriteLine("Candidate is not eligible for engineering admission");
                }
            }
            else
            {
                Console.WriteLine("You have not acquired the minimum criteria");
            }
        }
    }
}


```

## Output:

![image](https://github.com/Paul-Andrew-15/Eligibility-for-Admission/assets/94279791/63a5e982-4ece-4488-85c0-55554a881625)

![image](https://github.com/Paul-Andrew-15/Eligibility-for-Admission/assets/94279791/94992195-2494-458e-be35-57efc5dd1917)


## Result:
Thus, a C# program to check the eligibility of a student on engineering admission has been executed successfully.
