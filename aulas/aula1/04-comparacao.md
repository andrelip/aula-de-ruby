# Parte 4 - Operadores de comparação

Uma parte fundamental da programação é executar algo caso uma comparação seja verdadeira ou falsa, como um número ser igual a outro. Antes de chegar lá, irei explicar como executar essas  comparações.

## Principais Operadores

`==` Retorna verdadeiro se o valor da `esquerda` e o `direita` `forem iguais`. Caso contrário retorna falso.

```ruby
5 == 5
=> true
```

```ruby
4 == 5
=> false
```

```ruby
'ruby' == 'ruby'
=> true
```

```ruby
'ruby' == 'java'
=> false
```

```ruby
true == false
=> false
```

```ruby
false == false
=> true
```


`!=` Retorna verdadeiro se o valor da `esquerda` e o da `direita` `forem diferentes`. Caso contrário retorna falso.

```ruby
4 != 5
=> true
```

```ruby
4 != 4
=> false
```

`>` Retorna verdadeiro apenas se o valor da `esquerda` for `MAIOR` que o da direita. Caso contrário retorna falso, mesmo que sejam iguais.

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

`<` É o oposto do anterior, apenas retorna verdadeiro se o da `esquerda` for `MENOR`.

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

`>=` Retorna verdadeiro se o valor da `esquerda` for `MAIOR OU IGUAL` ao da direita.

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

`<=` A mesma coisa do anterior, mas considera que o da `esquerda` deve ser `MENOR OU IGUAL` ao da direita

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
