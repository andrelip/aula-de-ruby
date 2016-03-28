# Parte 5 - Variáveis

Variáveis são associadas a [valores](https://github.com/andrelip/ruby-from-zero-to-hero/blob/master/aulas/aula1/03-dados.md).

Se escrevermos algo como `x = 5`, logo `x` vai estar associado ao número 5 e se comportará como se fosse o mesmo. Em Ruby dizemos que o valor da esquerda recebe o da direita. Isso funciona diferente das equações tradicionais de matemática, pois lá `x = 5` é exatamente igual a `5 = x.

```ruby
5
=> 5 # Retorna o valor da linha anterior. Como não teve nenhum tipo de operação, retornou o próprio inteiro 5.
```

```ruby
x = 5 # Associa o valor inteiro 5 a variável x.
=> 5 # Quando você associa algo, o retorno é o valor que foi associado.
```

```ruby
x = 5
=> 5

x  # Como x já estava associado ao inteiro 5, logo x vai ser executado como se fosse esse número.
=> 5
```

A qualquer momento podemos setar novamente o valor de x para outro valor qualquer.

```ruby
x = 1
=> 1

x = 5
=> 5

x = 6
=> 6

x  
=> 6 # Último valor de x
```

Também podemos chamar nossa variável de qualquer coisa.

```ruby
numero_maior = 5
=> 5

numero_menor = 3
=> 3

numero_maior
=> 5

numero_menor
=> 3
```
Na realidade existem algumas pequenas restrições, como o primeiro caractere que não poder ser um número e algumas palavras reservadas, por enquanto use apenas letras e underline `_`  no lugar de espaço que dificilmente terá algum problema. Se quiser saber mais sobre essa restrição é só pesquisar no google.

Variáveis representam completamente os valores, logo podemos substituir os dados por ela em qualquer caso.
```ruby
numero_maior = 5
=> 5

numero_menor = 3
=> 3

numero_maior > numero_menor
=> true

numero_maior < numero_menor
=> false
```

Sabe quando você escreve uma expressão e aperta `enter`, aparecendo o resultado logo abaixo? Variáveis podem ser associadas com uma expressão também, recebendo o valor que aparece abaixo.

```ruby
'Ola ' + 'mundo!'
=> 'Ola mundo!'

frase = 'Ola ' + 'mundo!'
=> 'Ola mundo!'

frase
=> 'Ola mundo!'
```

```ruby
resultado = 5 > 3
=> true

resultado
=> true
```
