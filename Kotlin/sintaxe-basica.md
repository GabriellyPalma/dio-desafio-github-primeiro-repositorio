## Kotlin, Sintaxe básica ##

**Tipos de dado**

1. printIn(Int.MAX_VALUE): Para saber o valor max. que pode ser atribuído, neste exemplo, a um valor inteiro.
2. toInt(): Para fazer a conversão entre valores.

**Declaração de variável**

+ Var (valor motável, CamelCase): Pode ter seu valor alterado durante o código, valor definido e alterado durante execução.
+ Val (valor imutável, CamelCase): Variável que terá somente o valor atribuído, valor definido durante a execução.
+ Const Val (Valor imutável, SNAKE_CASE): Constante cujo valor é atribuído durante compilação, construção, pode apenas ser consultado.

## Nullability ##

+ Qualquer tipo pode ser nulo, porém deve ser explicitado na declaração de variável através de (?)
+ Inferência de tipo não atribui nullability

## Operadores aritméticos ##

Função/Expressão/Comando/Atribuição

Soma: A + b / a.plus(b) / a+=b 
Subtração: A - B / a.minus(b) / a-=b
Multiplicação: A * B / a.times(b) / a*=b
Divisão: A / B / a.div(b) / a /=b
Resto: A % B / a.mod(b) / a%=b

+ Os operadores porem ser chamados como expressão ou comando, o serultado será o mesmo
+ A função de soma também funciona para concatenar Strings (unir duas Strings em uma única)

## Operadores Comparativos ##

Função/Expressão/Comando

**Maior/menor:** a > b ou a < b / a.compare.To(b)
**maior/menor igual:** a>=b ou a<=b / a.compareTo(b) >= 0
**Igual:** a == b / a.equals(b)
**Diferente:** a != b / (!a.equals(b)

+ Os comandos **compareTo** retornam os valores -1 (menor que), 0 (igual) ou 1 (maior). Já os operadores retornam **valores booleanos** (verdadeiro ou falso)
+ O comando **equals** retorna um **booleano**