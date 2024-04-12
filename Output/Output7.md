Claro! Vou criar uma função em **C#** que faz exatamente isso. Primeiro, vou gerar um array de **1000 inteiros aleatórios** e, em seguida, vou ordená-lo. Utilizarei a classe `Random` para gerar os números aleatórios e o método `Array.Sort()` para ordenar o array.

```csharp
using System;

class Program
{
    static int[] GerarEOrdenarArray()
    {
        int[] randomNumbers = new int[1000];
        Random random = new Random();

        // Preencher o array com inteiros aleatórios entre 1 e 1000
        for (int i = 0; i < randomNumbers.Length; i++)
        {
            randomNumbers[i] = random.Next(1, 1001);
        }

        // Ordenar o array
        Array.Sort(randomNumbers);

        return randomNumbers;
    }

    static void Main(string[] args)
    {
        int[] arrayOrdenado = GerarEOrdenarArray();

        // Imprimir o array ordenado
        foreach (int numero in arrayOrdenado)
        {
            Console.Write(numero + " ");
        }
    }
}
```

Execute o programa para obter o array de inteiros aleatórios ordenado! 🎲🔢