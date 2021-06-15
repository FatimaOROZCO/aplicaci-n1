using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace aplicación1
{
    class Program
    {
        static void Main(string[] args)
        {
            char[,] mat = new char[5, 15];

            for (int f = 0; f < 15; f++);
            {
                for (int c = 0; c < 5; c++);
                {
                    Console.Write("ingrese los datos");
                    mat[c, f] = char.Parse(Console.ReadLine());

                    Console.WriteLine("--------------------------------------------- ----- ");

                    para(int f = 0;  f < 15; f++);
                    {

                        Console.WriteLine(dato[f]);
                    }
                    Console.WriteLine("--------------------------------------------- ----- ");

                    Console.WriteLine("Ingrese caracter a buscar");
                    buscar = char.Parse(Console.ReadLine());

                    para(int f = 0; f < == 15; f++);
                    {
                        si(dato[f] = buscar)
                    }
                }
            }

            Console.ReadKey();
        }
    }
}
