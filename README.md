# First GitHub Repository


using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace nameBackwards
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("What is your name? ");

            var Name = Console.ReadLine();

            int NameDigits = Name.Length;

            Console.WriteLine("There are " + NameDigits + " digits in your name");

            Console.Read();

            //separation for neatness!
            //separation for neatness!
            //separation for neatness!

            for (int i = NameDigits; i > 0; i--)
            {
                Console.WriteLine(Name[i - 1]);
            }
            Console.WriteLine("Is your name Backwards!");
            Console.ReadKey();

        }
    }
}
