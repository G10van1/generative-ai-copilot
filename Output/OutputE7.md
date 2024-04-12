Sure! I'll create a function in **C#** that does exactly that. First, I'll generate an array of **1000 random integers** and then I'll sort it. I'll use the `Random` class to generate random numbers and the `Array.Sort()` method to sort the array.

```csharp
using System;

class Program
{
    static int[] GenerateAndSortArray()
    {
        int[] randomNumbers = new int[1000];
        Random random = new Random();

        // Fill the array with random integers between 1 and 1000
        for (int i = 0; i < randomNumbers.Length; i++)
        {
            randomNumbers[i] = random.Next(1, 1001);
        }

        // Sort the array
        Array.Sort(randomNumbers);

        return randomNumbers;
    }

    static void Main(string[] args)
    {
        int[] sortedArray = GenerateAndSortArray();

        // Print the sorted array
        foreach (int number in sortedArray)
        {
            Console.Write(number + " ");
        }
    }
}
```

Run the program to get the sorted array of random integers! 🎲🔢