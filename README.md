# firstC

using System;

namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {
            string str1;
            string str2;

            Console.WriteLine("Напишите первое число");

            str1 = Console.ReadLine();

            Console.WriteLine("Напишите второе число");

            str2 = Console.ReadLine();

            int a = Convert.ToInt32(str1);
            int b = Convert.ToInt32(str2);

            double result1 = (double) a + b;
            double result2 = result1 / 2;

            Console.WriteLine("Среднее арифметическое: " + result2);

        }
    }
}
