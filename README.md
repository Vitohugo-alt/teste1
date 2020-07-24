# teste1
using System;

namespace teste1
{
    class Program
    {
        static void Main(string[] args)
        {
            decimal decimalX = 19;
            decimal decimalY = 2755;
            decimal decimalsoma = decimalX + decimalY;
            //Console.WriteLine($"{decimalX} + {decimalY} = {decimalsoma}");


            double doubleB = -477;
            double doublesubtracao = doubleB - Convert.ToDouble(decimalX);
            decimal decimalmultiplicacao = Convert.ToDecimal(doubleB) * decimalY;
            Console.WriteLine($"{doubleB} - {decimalX} = {doublesubtracao} | decimal = {doubleB} * {decimalY} = {decimalmultiplicacao}");


            Console.WriteLine("--- Etapa2");

            double n1 = 7, n2 = 88, n3 = 793, n4 = 94, n5 = -226, n6 = 4;
            double r1 = n1 * n3 / n2 + n4;
            double r2 = (n1 * n3 / n2) + n4;
            double r3 = n1 * n3 / (n2 + n4);
            double r4 = (((n1 * n3 / n2) + n4) - n5) / n6;

            Console.WriteLine($"{n1} * {n3} / {n2} + {n4} = {r1}");
            
            Console.WriteLine($"({n1} * {n3} / {n2}) + {n4} = {r2}");

            Console.WriteLine($"{n1} * {n3} / ({n2} + {n4}) = {r3}");

            Console.WriteLine($"((({n1} * {n3} / {n2}) + {n4}) - {n5}) / {n6} = {r4}");

            


            Console.WriteLine("--- Etapa 3");

            int x = 9;
            int y = 2;
            int teste1 = x / y;
            int teste2 = x % y;

            Console.WriteLine($"{x} / {y} = {teste1}");
            Console.WriteLine($"{x} % {y} = {teste2}"); // % = Módulo

            Console.WriteLine("--- Etapa4"); //utilazar o Math. para operações Matematicas

            //Pow = numeros elevados
            //Sqrt = Criar raizes quadradas

            double elevado = Math.Pow(3, 6);
            double elevado2 = Math.Pow(7, 8);
            double raiz = Math.Sqrt(9);
            double raiz2 = Math. Sqrt(120);

            Console.WriteLine($"{3, 6} = {elevado}");
            Console.WriteLine($"{7, 8} = {elevado2}");
            Console.WriteLine($"{9} = {raiz}");
            Console.WriteLine($"{120} = {raiz2}");

            Console.WriteLine("--- etapa5");

            //Funções trigonométricas
            //para converter o angulo tem que * por PI e / por 180

            double pi = Math.PI;
            double sen90 = Math.Sin(90 * pi / 180);
            double cos45 = Math.Cos(45 * pi / 180);
            double tan30 = Math.Tan(30 * pi / 180);

            Console.WriteLine($"pi = {pi}");
            Console.WriteLine($"tan de 30 = {tan30}");
            Console.WriteLine($"seno de 90 = {sen90}");
            Console.WriteLine($"cosse de 45 = {cos45}");

            Console.WriteLine("---Etapa6");

            //Arredondamento
            //A operação Math.Round arrendonda o número.

            double piarredondado9 = Math.Round(pi, 9);
            double piarredondado4 = Math.Round(pi, 4); 
            double piarredondado12 = Math.Round(pi, 12);

            Console.WriteLine($"9 casas = {piarredondado9:N10}");
            Console.WriteLine($"4 casas = {piarredondado4:N7}");
            Console.WriteLine($"12 casas = {piarredondado12:N15}");





        }
    }
}
