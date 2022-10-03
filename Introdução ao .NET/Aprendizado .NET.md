# Tudo que Aprendi nesse Curso :computer:
.NET é uma plataforma de desenvolvimento unificado open source e multiplataforma.

# Etapa 1
## Introdução ao .NET
### Tipo de APP's
- Desktop: WPF, Windows Forms e UWP
- WEB: ASP .NET
- Cloud: Azure
- Mobile: Xamarin
- Gaming: Unity
- IoT: ARM32 e ARM64
- AI: ML.NET e .NET for Apache Spark

### Ferramentas .NET 
- Visual Studio
- Visual Studio MAC
- Visual Studio CODE
- Command Line Interface (CLI)

### Linguagens .NET Suporta
- C#
- F#
- Visual Basic

# Etapa 2
## Diferenças entre .NET Framework (Legado) e .NET
- .NET Framework (Legado) apenas Windows
- .NET multiplataforma

# Etapa 3
## Compilador .NET e seu funcionamento
- Linguaguem de alto nível: a linguagem que programamos, facil de entender.
- Linguagem de baixo nível: muito mais complexa.
- Compilador: converte linguagem de alto nível para baixo nível.
- Transpilador: alto nível para alto nível.

# Etapa 4
## Introdução as IDEs e Configuração de Ambiente .NET
- IDE: programa que utilizamos para desenvolver.
- Quais IDEs podemos utilizar: Visual Studio, Visual Studio Code e Rider.
## Comandos CLI .NET
- dotnet new console: cria o projeto na pasta especificada.
- dotnet run: compila e executa seu código. 

# Etapa 5
## Sintaxe e Indetação
- Sempre que nao estiver reconhecendo a classe, verificar se esta usando using e verificar se o namespace esta correto.
- Sempre fechar com ;
- \n quebra de linha
- Classe (nome.variavel) = new Classe();
- Sintaxe é um conjunto de regras que deve obedecer, se nao o C# nao compila o código.
- Case: Padrão de escrita para nomes ( camelCase, PascalCase, snake_case e spinal-case).
- camelCase e PascalCase se usa no C#.
- Nome de classe sempre em PascalCase.
- não pode ter espaços nas classes, propriedades e métodos, espaços apenas em textos nas "".
- Nome de propriedades e métodos maiuscula a primeira letra.
- JavaScript utiliza camelCase.
- toda variavel inicia em minusculo utilizando camelCase.
- Sintaxe são regras que devem seguir senão o programa não compila.
- Conveções regras definidas pela comunidade, que são identificados padrões para legibilidade do código.
- Cada linguagem tem sua convenção.

# Etapa 6
## Tipos de Dados
- string: cadeia de caracteres, um texto.(representado por "")
- char: caracter unicode.
- bool: valor booleano Verdadeiro ou Falso(um dos mais utilizados na programação).
- int: valor representa um número que não tem casas decimais(Ex: Idade), (int é uma variavel de 32 bits que representa um número de 2kk).
- (u) antes da palavra significa unsigned
- long, uint, short e ulong: números inteiros que não tem casas decimais.
- int e long: mais utilizados.
- decimal, double e float: números com casas decimais.
- decimal: valores decimais com 28-29 digitos significativos (recomendavel para valores monetarios).
- double e float: valores decimais.
- Valores mais utilizados: string, object, bool, decimal, double e int.
- variavel: valor alocado na memoria para utilizar no programa.
- Trabalhar com data: usar DateTime.

# Etapa 7
## Operadores de Atribuição
- Operador de atribuição: serve para atribuir valor a uma determinada variavel.
- Sinal de (=): valor de atribuição
- Cast - Casting: conversão de um tipo string para inteiro.
- Parse: converter uma string para um int 32 bits.
- Todo tipo que tem no C# pode ser convertido para outro tipo, conhecido com Cast/Casting.
- Converter string: não precisa utilizar Parse porque não existe para string e não precisa usar o Convert, utilizar (.ToString()).
- TryParse: conversão segura.
- quando quiser prioridade usar ().

# Etapa 8
## Operadores Condicionais
- Um operador condicional possibilita mudar o fluxo de execução de seu código, indicando um caminho que ele deve percorrer.
- if: só executa se a condição for verdadeira.
- else: só executa se todas condições acima falhar.
- if aninhado: varias condições que são possiveis de percorrer.
- else if: continuação.(opcional).
- ==: comparação.
- switch: significa que esta olhando uma variavel, alternativa caso tenha if aninhado(caso tenha varios if's preferivel utilizar switch).
- case: igual if.
- break: para sair do switch.
- default: igual else.

# Etapa 9
## Operadores Lógicos
- utilizar principalmente no if, para realizar verificação de uma determinada condição do código.
- OR(Pipe, ||):verifica se uma das condições são verdadeiras.
- AND (&&): ao contrario do OR, ele só é verdadeiro se todas as condições forem verdadeiras.
- NOT (!): nega um  valor booleano, se ele é true ele vai ser falso e se for falso vai ser true.(utilizar com &&).

# Etapa 10
## Operadores Aritméticos e a classe Math
- operadores aritméticos são oque usamos na matemática e tambem podemos usar no c# para realizar calculos.
- ++: aumentar valor em 1.
- --: diminuir valor em 1.
- quando estiver passando parametros colocar virgula.
- Sqrt: raiz quadrada.
- Round: arredondar.

# Etapa 11
## Estruturas de Repetição
- FOR: 3 sintaxes básicas: declaraçao de variavel, condição e incremento.
- Exemplo: for(int contador = 0; contador <= 10; contador++).
- While: while apenas verifica a condição, voce responsavel por declarar a variavel antes e incrementar no final do laço(não esquecer da quebra de retorno para nao ter looping infinito.)
- Exemplo: while (contador <=10).
- break: quebrar uma condição independente se for verdadeira.
- DO While: o do executa o código independente da condição. (do {...........}while(true);)
- pode declarar varias variaveis do mesmo tipo em uma unica linha.(tem que ser do mesmo tipo).
- !=: diferente.
- diferença entre While e DO While: o while faz so a verificação no começo e se nao for verdadeira nao executa, o DO While executa o código primeiro independente da condição e depois re verifica a condição e executa novamente caso seje verdadeira.

# Etapa 12
## Estrutura de um programa e método principal.
Estudar quais são os arquivos principais de um projeto .NET, como identificar e para que serve.
- .csproj: Contém informações referente a um projeto (build, debug, versão)
- .sln: Contém informações que carregam um agrupamento de projetos.






















