## Manipulando strings ##

+ Strings possuem diversos métodos associados
+ Indexação, concatenação, comparação, formatação..
+ Pode ser concatenada com plus/+
+ também é tratada como uma array de Char

**Indexação**

+ String como array
+ First(, last(), String.lenght, String[index]

O comando plus irá apenas juntar os valores, para juntar valores respeitando uma estrutura pré determinada utiliza-se ${} (não se utiliza chave se a expressão nao for atrelada a um método) 

capitalize() torna maiúscula a primeira letra da string
toUpperCase() caixa alta
toLowerCase() caixa baixa
decapitalize() torna minúscula a primeira letra da string

trimEnd(), trimStart() e trim() removem espaços vazios e caracteres inadequados para impressão

replace(x, y) substituí caracteres por outros, sendo X o caractere a ser econtrado e substituído e Y o caractere para substitiução

"padrão
$(valor)".format(valor) formara valores para um padrão de string, fazendo a conversão  

## Diferença entre Empty e Blank ##

+ Metodo de comparação que indica se a string está em branco ou é nula

Se o tamanho da string (s.length) for 0 está empty e blank
Se o tamanho for >0 mas todos os caracteres são espaços em branco está blank mas não empty (os 'caracteres' de espaço contam como lenght) 

"" empty e blank || "    " não está empty mas está blank
