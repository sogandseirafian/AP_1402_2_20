# AP_1402_2_20
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace AP_1402_2_3.CS
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //برنامه ای بنویسید که 3 عدد را از ورودی دریافت و مشخص کند باهم تشکیل مثلث میده یا نه
            int num1 = Convert.ToInt32((Console.ReadLine()));
            int num2 = Convert.ToInt32((Console.ReadLine()));
            int num3 = Convert.ToInt32((Console.ReadLine()));
               if(num1+num2>num3   &&  num1 + num3 > num2  &&  num2 + num3 > num1)

            {
                Console.WriteLine("Triangel");
            }
               else
            {
                Console.WriteLine("not triangel");
            }
        }
    }
}
