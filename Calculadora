class Calculadora
{
    public static double Operacao(double num1, double num2, string opcao)
    {
        double resultado = double.NaN; // "not-a-number"
        switch (opcao)
        {
        case "a":
            resultado = num1 + num2;
            break;
        case "s":
            resultado = num1 - num2;
            break;
        case "m":
            resultado = num1 * num2;
            break;
        case "d":
            if (num2 != 0)
                resultado = num1 / num2;
            break;           
        default:
            Console.WriteLine("Opção Inválida");     
            break;
        }    
        return resultado;    
    }
}
