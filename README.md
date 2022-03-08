# C---SHARP
PRAVIN
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using static System.Console;
using System.Threading.Tasks;

namespace pravinform
{
    public class employee
    {
        public void addtion()
        {
            int a, b, c, d, e, f, g;
            a = 100;
            b = 200;
            c = 300;
            d = 400;
            e = 500;
            f = 600;
            g = 700;
            {
                int z = a + b + c + a * d * e / 50;
                Console.WriteLine(z);

            }

        }
        public void contronstetment()
        {
            int a = 50; int b = 60;
            if (a >= b)
            {
                Console.WriteLine("pravin kumar");
            }
            else if (a <= b)
            {
                Console.WriteLine("ramkumae");

            }
            else
            {
                Console.WriteLine("makip");
            }

        }
        public void Result()
        {
            int mark = 60;
            if (mark >= 60 && mark <= 100)
            {
                Console.WriteLine("Popper");
            }
            else if (mark >= 50 && mark <= 100)
            {
                Console.WriteLine("fist deveson");

            }
            else if (mark >= 80 && mark <= 100)
            {
                Console.WriteLine("SECEND DEVESON");
            }
            else if (mark <= 700 && mark <= 100)
            {
                Console.WriteLine("THIRD DEVESIN");
            }
            else
            {
                Console.WriteLine("fial");
            }
        }
        public void oddnumaber()
        {
            for (int i = 1; i <= 50; i++)
            {
                if (i % 2 == 1)
                {
                    Console.WriteLine(i);
                }
            }
        }
        public void singalbreck(string color)
        {
            switch (color)
            {
                case "Red":
                    Console.WriteLine("stop");
                    break;
                case "Blue":
                    Console.WriteLine("up");
                    break;
                case "yellow":
                    Console.WriteLine("on");
                    break;
                default:
                    Console.WriteLine("over");
                    break;


            }
        }


    }
    public class year
    {
        public void leapyear()
        {

            Write("Enter a four digit year :");
            int year = Convert.ToInt32(ReadLine());
            if (year % 400 == 0 || year % 4 == 0)
            {
                WriteLine("year it is leap year");
            }
            else
            {
                WriteLine("nomber it not leap yeas");
            }


        }

    }
    public class Emplyee
    {
        string firsName;
        string lastName;
        int salaryee;
        private int r;

        public string FinrsName

        {
            get { return firsName; }
            set { firsName = value; }

        }
        public string Lastname
        {
            get { return lastName; }
            set { lastName = value; }

        }
        public int salary
        {
            get { return salaryee; }
            set { salaryee = value; }
        }
        public double add
        {
            get { return add; }
            set { add = value; }

        }
        public string FullName
        {
            get { return FullName + "  " + lastName; }

        }
        public int anualseleyee
        {
            get { return anualseleyee * 23; }
        }

        public void loop()
        {
            for (int a = 1; a < 20; a++)
            {
                for (int q = a; q < 20; q++)
                {
                    Console.WriteLine(" ");
                }

            }
            for (int j = 1; j < add; j++)
            {
                Console.WriteLine("*");
                Console.WriteLine("  ");
                {
                    Console.WriteLine();
                }
            }
            for (int r = 20; r > 1; r--)
            {
                for (int p =r; p < 20; p++)
                {
                    Console.WriteLine("  ");
                }
            }
            for (int j = 1; j < r; j++) 
            {
                Console.WriteLine("*");
                Console.WriteLine(" ");
                {
                    Console.WriteLine();
                }
            }


        }
    }
}  
   
