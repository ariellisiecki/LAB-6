using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication4
{
    class Program
    {
        static void Main()
        {
            for (int year = 2017; year <=2100; year++)
                if(DateTime.IsLeapYear(year))
                {
                    Console.WriteLine("{0} is a leap year.",year);
                    DateTime leapDay = new DateTime(year, 2, 29);
                }
        }
    }
}
