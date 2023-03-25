# Projeto C# tutorial

## Constru��o de um programa console

* Programa console � um programa bem b�sico (minimalista) para testar coisas simples.

### Passo 1 - Criar Projeto

- Iremos usar o Visual Studio Enterprise 2022 para construirmos o projeto.
- Assim que abrir o programa, v� em:

```text
File > New > Project...
```

<img src="images\1_criar_projeto.png">

- Vai aparecer v�rios tipos de Projetos que pode criar, procure por:

```text
Console App
```

<img src="images\2_escolha_console.png">

- Coloque o nome do projeto e o diret�rio a qual ele pertence

<img src="images\3_define_nome.png">

- Selecione a vers�o do .NET, a atual nesse projeto � a `.NET 6`

<img src="images\4_define_versao.png">


### Passo 2 - Classe Inicial

- Agora depois do .NET 6 normalmente � criado um arquivo chamado `Program.cs` que vem com a seguinte estrutura:

```csharp
// See https://aka.ms/new-console-template for more information
Console.WriteLine("Hello, World!");
```

- A estrutura antiga e que ainda vale para aprender bem � a seguinte:

```csharp
using System;

namespace MyApp // Note: actual namespace depends on the project name.
{
    public class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
        }
    }
}
```

- Ambas formas de construir uma Classe funcionam, a �ltima � melhor para estrutura e para o aprendizado

#### Entendendo a Classe inicial

- `using` = 
- `namespace` = 
- `public` = 
- `class` = 
- `static` = 
- `void` = 
- `Main` = 
- `string[]` = 
-  `args` = 
- `Console` = 
- `Console.WriteLine()` = 

### Passo 3 - Estrutura de arquivos

