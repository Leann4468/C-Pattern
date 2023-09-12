# Pattern

## Aim:
### To write a C# program for a pascal's triangle.

## Equipment Required:
### Hardware:pc software:Visual Studio.

## Algorithm:
### Step 1: Start the program.

### Step 2: Create a class and declare two variables rows,Val using integer datatype.

### Step 3: Using nested for loop create a pascal's triangle.

### Step 4: Stop the execution.
## Program:
```python

using System;
public class pattern
{
    public static void Main()
    {
        int rows, c = 1, a, i, j;

        Console.Write("rows: ");
        rows = Convert.ToInt32(Console.ReadLine());
        for (i = 0; i < rows; i++)
        {
            for (a = 1; a <= rows - i; a++)
            {
                Console.Write(" ");
            }
            for (j = 0; j <= i; j++)
            {
                if (j == 0 || i == 0)
                {
                    c = 1;
                }
                else
                {
                    c = c * (i - j + 1) / j;
                }
                Console.Write("{0} ", c);
            }
            Console.Write("\n");
        }
    }
}
```
## Output:
![Screenshot 2023-09-12 090420](https://github.com/Leann4468/C-Pattern/assets/121165979/69bef528-d88c-47df-820e-f763086c1eca)

## Result:
### Thus the c# code for a pascal's traingle was executed successfully.
