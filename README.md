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



F)



using System;
namespace Atv02._6
{
class Program
{
public static void Main(string[] args)
{
Console.Write("Digite um número: ");
double numero = Convert.ToDouble(Console.ReadLine());

if (numero >= 0)
{
double raizQuadrada = Math.Sqrt(numero);
Console.WriteLine("A raiz quadrada de " + numero + " é: " +
raizQuadrada);
}
else
{
Console.WriteLine("Não é possível calcular a raiz quadrada de um
número negativo.");
}

Console.Write("Press any key to continue . . . ");
Console.ReadKey(true);

}
}
}



G)


using System;
namespace Atv02._7
{
class Program
{
public static void Main(string[] args)
{
Console.Write("Digite o primeiro número: ");
int numero1 = Convert.ToInt32(Console.ReadLine());

Console.Write("Digite o segundo número: ");
int numero2 = Convert.ToInt32(Console.ReadLine());

int subtracao = numero2 - numero1;

Console.WriteLine("A subtração de " + numero2 + " por " + numero1 + "
é: " + subtracao);

Console.Write("Press any key to continue . . . ");
Console.ReadKey(true);
}
}
}
H)



using System;
namespace Atv02._8
{
class Program
{
public static void Main(string[] args)
{
Console.Write("Digite um número: ");
int numero = Convert.ToInt32(Console.ReadLine());

int absoluto = Math.Abs(numero);

Console.WriteLine("O valor absoluto de " + numero + " é: " + absoluto);

Console.Write("Press any key to continue . . . ");
Console.ReadKey(true);
}
}
}
I)


using System;
namespace Atv02._9
{
class Program
{
public static void Main(string[] args)
{

Console.Write("Digite o primeiro número: ");
int numero1 = Convert.ToInt32(Console.ReadLine());

Console.Write("Digite o segundo número: ");
int numero2 = Convert.ToInt32(Console.ReadLine());

int multiplicacao = numero1 * numero2;

Console.WriteLine("A multiplicação de " + numero1 + " e " + numero2 +
" é: " + multiplicacao);

Console.Write("Press any key to continue . . . ");
Console.ReadKey(true);
}
}
}

J)

using System;
namespace Atv02._10
{
class Program
{
public static void Main(string[] args)
{
Console.Write("Digite um número: ");
int numero = Convert.ToInt32(Console.ReadLine());

int resto = numero % 2;

Console.WriteLine("O resto da divisão de " + numero + " por 2 é: " +
resto);

Console.Write("Press any key to continue . . . ");
Console.ReadKey(true);
}
}
}




