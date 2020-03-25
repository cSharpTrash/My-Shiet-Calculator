using System;

namespace GettingInput
{
  class Program
  {
    static void Main()
    {
    
      {

        Console.ForegroundColor = ConsoleColor.Yellow;
        Console.WriteLine("area, omkrets eller sektor");
     string calculator = Console.ReadLine();
        if (calculator == "omkrets")
        {
        Console.WriteLine("Skriv Diametern");
      int Diameter = Convert.ToInt32(Console.ReadLine());

      double pi = 3.14;

      Console.WriteLine("Omkretsen blir");
                        Console.WriteLine(Diameter*pi);
      }
        if (calculator == "area")
        {
          Console.WriteLine("Skriv Radien");
          int Radie = 
Convert.ToInt32(Console.ReadLine());
            
      double pi = 3.14;
      Console.WriteLine("Arean blir");
          
         Console.WriteLine(Radie*Radie*pi);
          
        }
        
        if (calculator == "sektor")
        {
          Console.WriteLine("Skriv Radien");
          int Radie = 
Convert.ToInt32(Console.ReadLine()); 
          Console.WriteLine("Skriv Vinkeln");
          double vinkel = 
Convert.ToInt32(Console.ReadLine());
        double oneTurn = 360;    
      double pi = 3.14;
      Console.WriteLine("Arean blir");
       double angleThing = vinkel/oneTurn;
          double areaThing = Radie*Radie*pi;
         double answer = angleThing*areaThing;
          Console.WriteLine(answer);
         
          
        }
        
    
    
      }
    }
  }
}
