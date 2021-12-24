# Variáveis

* Nomes simbólicos para receber algum valor
* Atalhos de código 
* Identificadores
* 3 palavras reservadas para criar uma variável
    * var
    * let
    * const

O JS é uma linguagem fracamente tipada e dinâmica
- Variáveis não precisam ter um tipo previamente definido
- Podemos mudar o conteúdo na variável

SCOPE

## var
```js
// var é global e poderá funcionar fora de um escopo de bloco 
console.log('> existe x antes do bloco? ', x)

{
    var x = 0
}

console.log('> existe x depois do bloco? ', x)
```

## let e const
```js
// const e let são locais e só funcionam no escopo onde foi criada
console.log('> existe y antes do bloco? ', y)

{
    let y = 0
}

console.log('> existe x depois do bloco? ', y)
```
# Nomeando variáveis
## Para criar nomes

* JS é case-sensitive (sensível ao caso)
* JS aceita a cadeia de caracteres Unicode

- Posso: 
    * Iniciar com esses caracteres especiais: $ _
    * Iniciar com letras
    * Colocar acentos 
    * Letras maísculas e minúsculas fazem diferença

- Não posso:
    * Iniciar com números 
    * Colocar espaços vazios no nome

- Ideal:
    * Criar nomes que fazem sentido
    * Que explique o que a variável é ou faz
    * camelCase
    * snake_case
    * escrever em inglês
