# segitigabintang
Looping segitiga bintang dengan C#



using System;
namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {
            int banyak, baris,  k;
            int karakter;
            Console.Write("masukan banyak tampilan:");
            banyak = Convert.ToInt16(Console.ReadLine());
            Console.Write("masukan karakter: ");
            karakter = Convert.ToChar(Console.ReadLine());
            for (baris = 1; baris <= banyak; baris++)
            {
                for (karakter = 1; karakter <= baris; karakter++)
                {
                    Console.Write(karakter +"*"+  "");
                }
                Console.WriteLine("");
            }
            Console.ReadKey();
        }
    }
}
        
    

