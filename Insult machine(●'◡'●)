using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Insult_machine_______
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("how many people you insulting?");
            string numins = Console.ReadLine();
            int numinsint = Convert.ToInt32(numins);

            while (numinsint > 0)
            {
                insults();
                Console.WriteLine(" ");
                numinsint--;

            }
            
        }


        static void insults()
        {

            //ask for name
            Console.WriteLine("Whats ya name");
            string name = Console.ReadLine();

            //array of insults
            string[] insult = {"you're a loser, lil loser","what do you call a lil idiot who smells? YOU heehehehe","what do you call a person with no coolness... YOU", "YOU ARE A WASTE OF AIR"};

            //gets random number for insults
            int lensult = insult.Length;
            Random rnd = new Random();
            int rand = rnd.Next(1, lensult);

            //outputs an insult
            Console.Write("hey " + name + ", ");
            Console.Write(insult[rand]);

            Console.ReadLine();

        }



    }



}

