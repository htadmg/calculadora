# Projeto Calculadora

Este é um projeto de uma calculadora simples implementada em C#.

## Funcionalidades

A calculadora possui as seguintes funcionalidades:

- `Somar(int a, int b)`: Retorna a soma de dois números inteiros.
- `Subtrair(int a, int b)`: Retorna a subtração de dois números inteiros.
- `Multiplicar(int a, int b)`: Retorna o produto de dois números inteiros.
- `Dividir(int a, int b)`: Retorna a divisão de dois números inteiros.

## Testes

O projeto inclui testes unitários para garantir o correto funcionamento das operações matemáticas.

### Testes Incluídos

- `Somar`: Verifica se a função `Somar` retorna o resultado esperado.
- `Subtrair`: Verifica se a função `Subtrair` retorna o resultado esperado.
- `Multiplicar`: Verifica se a função `Multiplicar` retorna o resultado esperado.
- `Dividir`: Verifica se a função `Dividir` retorna o resultado esperado.

## Como Usar

Para utilizar a calculadora em seu próprio projeto, siga os passos abaixo:

1. Copie os arquivos `Calculadora.cs` para o seu projeto.
2. Importe o namespace `Calculadora` no arquivo onde deseja utilizar a calculadora.
3. Utilize as funções de acordo com suas necessidades.

### Exemplo de Uso

```csharp
using Calculadora;

class Program
{
    static void Main()
    {
        int resultadoSoma = Calculadora.Somar(10, 10);
        Console.WriteLine("A soma de 10 e 10 é: " + resultadoSoma);
    }
}
