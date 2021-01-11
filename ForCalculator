using System;

namespace For_Calculator
{
    class Program
    {
        static void Main(string[] args)
        {
            
            Console.Write("You may type 'HELP' now for info. Otherwise press ENTER to proceed: ");
            string help = Console.ReadLine();


            if (help == "HELP" | help == "help")
            {
                Console.WriteLine("\nYou will be asked to enter a number. Then an operator, EG: + - * or /. Then another number.\n\nPress ENTER to proceed.");
                Console.ReadLine();
            }
            else if (String.IsNullOrEmpty(help))
            {
                Console.WriteLine("");
            }

            while (true)
            {

                Console.Write("Enter a number: ");
                double num1 = Convert.ToDouble(Console.ReadLine());

                Console.Write("Enter Operator: ");
                string op = Console.ReadLine();

                Console.Write("Enter a number: ");
                double num2 = Convert.ToDouble(Console.ReadLine());


                if (op == "+")
                {
                    Console.WriteLine("");
                    Console.WriteLine("Your answer: ");
                    Console.WriteLine(num1 + num2);
                }
                else if (op == "-")
                {
                    Console.WriteLine("");
                    Console.WriteLine("Your answer: ");
                    Console.WriteLine(num1 - num2);
                }
                else if (op == "*")
                {
                    Console.WriteLine("");
                    Console.WriteLine("Your answer: ");
                    Console.WriteLine(num1 * num2);
                }
                else if (op == "/")
                {
                    Console.WriteLine("");
                    Console.WriteLine("Your answer: ");
                    Console.WriteLine(num1 / num2);
                }
                else
                {
                    Console.WriteLine("\nPlease enter a valid operator. Valid operators are: + - * /. Restart program to retry.");
                }

                Console.WriteLine("");
                Console.WriteLine("You may repeat this as many times as you like.\n");

            }

            

        }
    }
}
