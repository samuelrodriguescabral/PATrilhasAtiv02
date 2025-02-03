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



c)
using System;

namespace ATVI2
{
	class Program
	{
		public static void Main(string[]args)
		
		{
	

			Console.Write("Digite um Número: ");
						
			int numero = Convert.ToInt32(Console.ReadLine());
			
		}
		
		
	}
}






D)
using System;

namespace ATVI2
{
	class Program
	{
		public static void Main(string[]args)
		{
	

			Console.Write("Digite um Número: ");
			int numero= Convert.ToInt32(Console.ReadLine());
	
			int quadrado = numero * numero;
			Console.WriteLine("o quadrado de" + numero +"é:"+ quadrado);
			Console.Write("Press any key to continue...");
			Console.ReadKey(true);
		}
		
	}

}













e)
    using System;

namespace ATVI2
{
	class Program
	{
		public static void Main()
		{
			Console.WriteLine("Digite um número");
			double num1 = double.Parse(Console.ReadLine());
			Console.WriteLine("Digite outro número");
			double num2 = double.Parse(Console.ReadLine());
			double resultado = num1/num2;
            Console.WriteLine("A divisão de "+num1+" por "+num2+" tem o resultado "+ resultado);
            Console.ReadKey(true);
		}
	}
}

			
		}
	}
}




