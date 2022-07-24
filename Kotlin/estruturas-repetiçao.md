## Introdução a funções ##

+ Prefixo Fun nomeDaFunção(nome:Tipo):TipoRetorno{} (apenas se for desejado um retorno)

## Funções ordem superior ##

+ Recebem outra função ou lambda por parâmetro
+ úteis para generalização de funções e tratamento de erros

## Funções single-line ##

+ Prefixo 'Fun nomeDaFunção(nome:tipo) = retorno'
+ Função de uma única linha
+ infere o tipo de retorno

**Funções/extensões**

+ Prefixo 'Fun Tipo.nomeDaFuncao()'
+ Cria uma função que só pode ser chamada por um tipo específico, cujo o valor pode ser referenciado dentro da função através da palavra **this**

## Estruturas de controle ##

+ if/else, when, elvis operator
+ Pode ser utilizado tanto para controle quanto para atribuição
+ Pode ser encadeado com múltiplas estruturas 
+ Alt ENTER converte if em when

## Atribuições, when e Elvis operator ##

   **Atribuições**

+ O valor atribuído tem que estar na ultima linha do bloco
+ A condicional pode não usar chaves se só fizer a atribuição

   **When**

+ Equivalente ao switch de outras linguagens
+ Aceita tanto valores quanto condicionais
+ Aceita range como case

  **Elvis Operator**
  
  + O mais próximo que a linguagem possui de um operador ternário
  + Verifica se um valor é nulo e apresenta uma opção caso seja
  + Pode ser encadeado
  
## Estruturas de reperição ##

  **For**
  
  + For (variavel indexadora in/until/downTo faixa de valores/condicional step intervalo)
  + In: Conta do valor inicial até o valor final
  + Until: Conta do valor atual até o valor estabelecido menos 1
  + DownTo: Conta de maneira decrescente
  + Step: Determina o intervalo da contagem
  








