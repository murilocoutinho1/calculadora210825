using System;
using System.Collections.Generic;
using System.Diagnostics;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using static System.Console;

namespace _4auka
{
    internal class Program
    {
        static void Main(string[] args)
        {
            char op;
            float n1, n2, resultado;

            inicio:

            WriteLine("Digite o primeiro número");
            n1 = Convert.ToSingle(ReadLine());
            WriteLine("Digite o segundo número");
            n2 = Convert.ToSingle(ReadLine());
            WriteLine("Digite a operação (+, -, *, /): ");
            op = Convert.ToChar(ReadLine());
            switch (op)
            {
                case '+':
                    resultado = n1 + n2;
                    WriteLine("{0} + {1} = {2}", n1, n2, resultado);
                    break;
                case '-':
                    resultado = n1 - n2;
                    WriteLine("{0} - {1} = {2}", n1, n2, resultado);
                    break;
                case '*':
                    resultado = n1 * n2;
                    WriteLine("{0} * {1} = {2}", n1, n2, resultado);
                    break;
                case '/':
                    resultado = n1 / n2;
                    WriteLine("{0} / {1} = {2}", n1, n2, resultado);
                    break;
                default:
                    WriteLine("Operação inválida!");
                    goto inicio;
                    break;
            }
            ReadKey();
        }
    }
}