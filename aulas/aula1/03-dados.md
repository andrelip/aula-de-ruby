# Parte 3 - Dados

Em qualquer aplicação, iremos trabalhar com dados (pense neles como sendo um valor).
Nessa parte iremos explicar os tipos de dados, como números e texto, e como utilizar-los.

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

### "Número decimal" (float)
Pense neles como se fossem números decimais, embora tenha alguns detalhes, no momento isso não é nem um pouco relevante.

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
Só pode ter um dos dois valores, verdadeiro ou falso.

```ruby
true # true quando for verdadeiro
=> true # Como não realizamos nenhuma operação, então a execução retorna o seu próprio valor.
```

```ruby
false # true quando for falso
=> false
```
[Parte 4 - Comparando](https://github.com/andrelip/ruby-from-zero-to-hero/blob/master/aulas/aula1/04-comparacao.md)
