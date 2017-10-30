# section
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication4
{
    class Program
    {
        static void Main(string[] args)
        {
            string hex;
            int dec;
            Console.WriteLine("enter the hexa number");
            hex = Console.ReadLine();
            dec = Convert.ToInt32(hex, 16);
            Console.WriteLine("{0}", dec);
            Console.Read();
        }
    }
}
