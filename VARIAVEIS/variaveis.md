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