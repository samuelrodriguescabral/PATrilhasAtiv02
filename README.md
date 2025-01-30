# PATrilhasAtiv02


A)
using System;

namespace ATIV2
{
	class Program
	{
		static void Main()

		{
			 Console.Write("Digite o primeiro número: ");
        double numero1 = Convert.ToDouble(Console.ReadLine());

			
			Console.Write("Digite o segundo número: ");
        double numero2 = Convert.ToDouble(Console.ReadLine());
        
        double soma = numero1 + numero2;
			
			 Console.WriteLine("A soma dos dois números é: " + soma);
		}
	}
}



b)

using System;

namespace ATIV2
{
	class Program
	{
		
		static void Main()
    {

			 Console.Write("Digite um número: ");
        double numero = Convert.ToDouble(Console.ReadLine());
        

			  double dobro = numero * 2;

			 Console.WriteLine("O dobro de {0} é {1}.", numero, dobro);

			
		}
	}
}




