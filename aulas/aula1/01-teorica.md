# Aula 1

A instalação do Ruby pode ser um pouco complicada para iniciantes e não que isso seja uma barreita, então nesse primeiro momento iremos utilizar um console online.

## Utilizando o TryRuby

Acesse http://tryruby.org/

Lá sempre, que vocês digitar uma linha de comando, automaticamente na linha de baixe teremos o resultado da execução do código ao apertarmos `enter`.

Interpretem o símbolo `=>` como sendo o retorno do que foi executado.

Exemplo:
```ruby
2 + 1
=> 3
```

## Operadores aritiméticos:
+ Soma
- Subtração
* Multiplicação
/ Divisão
% Apenas o resto da divisão
** Exponencial

## Tipos básicos:

### Inteiro (int ou integer)
São número inteiros, logo sem decimal.
```ruby
10 + 5
=> 15
```

```ruby
6 - 1
=> 5
```

### Número 'decimal' (float)
Pense neles como se fossem números decimal, embora tenha alguns detales, no momento isso não é nem um pouco relevante.

```ruby
10.5
=> 10.5
```

```ruby
10 / 3 # inteiro divido por inteiro
=> 3  # O retorno é 3 pois a divisão não considera casas decimais
```

```ruby
10.0 / 3 # float divido por inteiro
=> 3.3333333333333335 # Como um dos números da operação é decimal, logo o resultado é decimal também
```

### Texto (string)
Sempre que o nosso dado for um texto, ele será uma string. Para isso o texto em questão deve estar envolto de aspas ou aspas duplas, explicarei a diferença quando for relevante.

```ruby
'Olá'
=> 'Olá'
```
```ruby
'Olá ' + 'mundo'
=> 'Olá mundo'
```

### Booleano
Só pode ter dois valores, verdadeiro ou falso.

```ruby
true # true quando for verdadeiro
=> true # Como não realizamos nenhuma operação, então a execução retorna o seu próprio valor.
```

```ruby
false # true quando for falso
=> false
```

### Operadores de comparação

== # Retorna verdadeiro se o valor da esquerda e o direita foram iguais. Caso contrário retorna falso.

```ruby
5 == 5
=> true
```

```ruby
4 == 5
=> false
```

!= # Retorna verdadeiro se o valor da esquerda é diferente forem diferentes. Caso contrário retorna falso.

```ruby
4 != 5
=> true
```

```ruby
4 != 4
=> false
```

> # Retorna verdadeiro apenas se o valor da ESQUERDA for MAIOR que o da direita. Caso contrário retorna falso, mesmo que sejam iguais.

```ruby
5 > 4
=> true
```

```ruby
5 > 5
=> false
```

```ruby
5 > 6
=> false
```

< # É o oposto do anterior, apenas retorna verdadeiro se o da ESQUERDA for MENOR.

```ruby
5 < 6
=> true
```

```ruby
5 < 2
=> false
```

```ruby
5 < 5
=> false
```

>= # Retorna verdadeiro se o valor da ESQUERDA for MAIOR OU IGUAL ao da direita.

```ruby
5 >= 4
=> true
```

```ruby
5 >= 5
=> true
```

```ruby
5 >= 6
=> false
```

### <= A mesma coisa do anterior, mas considera que o da ESQUERDA deve ser MENOR OU IGUAL ao da direita

```ruby
5 <= 6
=> true
```

```ruby
5 <= 5
=> true
```

```ruby
5 <= 4
=> false
```

Existem outros, mas por hora vamos nos concetrar nesses seis principais.
