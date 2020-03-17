using System;

namespace GettingInput
{
  class Program
  {
    static void Main()
    {
    
      {
        Console.WriteLine("area, omkrets eller sektor");
     string calculator = Console.ReadLine();
        if (calculator == "omkrets")
        {
        Console.WriteLine("Skriv Diametern");
      int numOne = Convert.ToInt32(Console.ReadLine());

      double numTwo = 3.14;

      Console.WriteLine("Omkretsen blir");
                        Console.WriteLine(numOne*numTwo);
      }
        if (calculator == "area")
        {
          Console.WriteLine("Skriv Radien");
          int numOne = 
Convert.ToInt32(Console.ReadLine());
            
      double numTwo = 3.14;
      Console.WriteLine("Arean blir");
          
         Console.WriteLine(numOne*numOne*numTwo);
          
        }
        
        if (calculator == "sektor")
        {
          Console.WriteLine("Skriv Radien");
          int Radie = 
Convert.ToInt32(Console.ReadLine()); 
          Console.WriteLine("Skriv Vinkeln");
          int vinkel = 
Convert.ToInt32(Console.ReadLine());
        int oneTurn = 360;    
      double pi = 3.14;
      Console.WriteLine("Arean blir");
       double angleThing = vinkel/oneTurn;
          double areaThing = Radie*Radie*pi;
         Console.WriteLine(angleThing*areaThing);
         
          
        }
        
    
    
      }
    }
  }
}
