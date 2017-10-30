# programming-c-
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication2
{
    class Program
    {
        static void Main(string[] args)
        {
            string hexValue;
            Console.WriteLine("enter the hexadecimal number");
            hexValue = Console.ReadLine();
            int Y = Convert.ToInt32(hexValue, 16);
            Console.WriteLine("{0}", Y);
            Console.ReadLine();
        }
    }
}

