# Operadores
Os operadores são símbolos ou palavras-chave que permitem realizar operações sobre valores e variáveis. Eles são fundamentais para manipular dados, realizar cálculos, fazer comparações e construir a lógica de um programa.
## Tipos de operadores
### Operadores aritméticos
Usados para realizar cálculos matemáticos padrão.
* `+` Adição.
* `-` Subtração.
* `*` Multiplicação.
* `/` Divisão.
* `%` Módulo (retorna o resto da divisão).
* `//` Divisão inteira.
* `**` Exponenciação.  
  
> 💡 **Nota:** Módulo geralmente é utilizado para verificar se um número é multiplo de outro e verificar se um número é ímpar ou par (`num % 2 == 0`).  

### Operadores de atribuição
Usados para definir ou atualizar o valor de uma variável de forma compacta.
* **Atribuição simples (`=`):** Atribui um valor a variável(*x = value*).
* **Adição e atribuição (`+=`):** Soma um valor ao valor atual da variável e atribui o resultado de volta à própria variável (*x += valor* é equivalente a *x = x + valor*).
* **Subtraction assignment (`-=`):** Subtrai um valor do valor atual da variável e atribui o resultado de volta à própria variável (*x -= valor* é equivalente a *x = x - valor*).
* **Multiplicação e atribuição (`*=`):** Multiplica o valor atual da variável por outro valor e atribui o resultado de volta à própria variável (*x *= valor* é equivalente a *x = x * valor*).
* **Divisão e atribuição (`/=`):** Divide o valor atual da variável por outro valor e atribui o resultado de volta à própria variável (*x /= valor* é equivalente a *x = x / valor*).
* **Módulo e atribuição (`%=`):** Calcula o resto da divisão entre o valor atual da variável e outro valor, atribuindo o resultado de volta à própria variável (*x %= valor* é equivalente a *x = x % valor*).
* **Divisão inteira e atribuição (`//=`):** Realiza a divisão inteira entre o valor atual da variável e outro valor e atribui o resultado de volta à própria variável (*x //= valor* é equivalente a *x = x // valor*).
* **Exponenciação e atribuição (`**=`):** Eleva o valor atual da variável a uma potência e atribui o resultado de volta à própria variável (*x **= valor* é equivalente a *x = x ** valor*).

### Operadores de comparação
São fundamentais em estruturas condicionais (*if*/*else*), pois retornam valores booleanos `True` ou `False`.
* **Igual a (`==`):** Verifica se dois valores são iguais (*1 == 1* retorna `True`).
* **Diferente de (`!=`):** Verifica se dois valores são diferentes (*1 != 1* retorna `False`).
* **Maior que (`>`):** Verifica se o valor da esquerda é maior que o valor da direita (*1 > 2* retorna `False`).
* **Menor que (`<`):** Verifica se o valor da esquerda é menor que o valor da direita (*1 < 2* retorna `True`).
* **Maior ou igual a (`>=`):** Verifica se o valor da esquerda é maior ou igual ao valor da direita (*1 >= 1* retorna `True`).
* **Menor ou igual a (`<=`):** Verifica se o valor da esquerda é menor ou igual ao valor da direita (*1 <= 1* retorna `True`).  
  
> 💡 **Nota:** Em algumas linguagens, como JavaScript e TypeScript, existem os operadores de igualdade estrita `===` e desigualdade estrita `!==`, que comparam tanto o valor quanto o tipo dos operandos, evitando conversões implícitas e possíveis bugs.

### Operadores lógicos
Usados para combinar múltiplas condições.
* **And** (`&&`): Retorna `True` só se todas condições forem `True`.
* **Or** (`||`): Retorna `True` se pelo menos uma condição for `True`.
* **Not** (`!`): Inverte o valor booleano. Por exemplo, `!True` retorna o valor `False`.  
    
> 💡 **Nota:** Algumas linguagens, como Java, JavaScript, e TypeScript utilizam `&&`, `||` e `!`, enquanto Python utiliza as palavras-chave `and`, `or` e `not`.

### Operadores de incremento e decremento
Aumenta ou diminui o valor da variável em 1, sendo muito comuns em loops (*for*/*while*).
* **Incrementa (`++`):** Aumenta o valor da variável em 1 (*x++* ou *++x*).
* **Decrementa (`--`):** Diminui o valor da variável em 1 (*x--* ou *--x*).  
  
> 💡 **Nota:** Python não possui os operadores `++` e `--`. O incremento e decremento são normalmente realizados com operadores de atribuição `+=` e `-=`.

### Operadores de identidade
Usados para verificar se duas variáveis fazem referência ao mesmo objeto.
* **Is (`is`):** Retorna *True* se referencia o mesmo objeto (*x is y*).
* **Is Not (`is not`):** Retorna *True* se as variáveis referenciam objetos diferentes (*x is not y*).  
  
> 💡 **Nota:** Não confunda identidade (`is`) com a atribuição simples (`==`). Enquanto `==` verifica se os objetos possuem o mesmo valor, `is` verifica se as variáveis apontam para o mesmo objeto.

### Operadores de pertencimento
Usados para verificar se um elemento pertence a uma coleção.

* **In (`in`):** Retorna *True* se o elemento pertencer a coleção (*x in lista*).
* **Not In (`not in`):** Retorna *True* se o elemento não pertencer a coleção (*x not in lista*).