# Volume-Of-Hemisphere
Using C# console application, calculate the volume of the hemisphere.

using System;

namespace VolumeHemisphere
{
    class Program
    {
        static void Main(string[] args)
        {
            //Variables.
            double r;
            double pi = Math.PI;
            double V;

            //Ask user for input.
            Console.Write("Enter a number for the radius: ");
            r = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine();

            //Calculate volume of hemisphere.
            V = (((4 * (pi * Math.Pow(r, 3)) )/ 3) / 2 ) ;

            //Display answers to user.
            Console.WriteLine($"Volume = {V}");
            Console.ReadLine();
            Console.WriteLine();
        }
    }
}
