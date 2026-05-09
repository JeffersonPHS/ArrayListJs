# ArrayListJs

## Função Map

O *map* percorre toda a lista e transforma cada item dentro da lista em um novo valor, criando uma nova lista com os resultados.

```javascript
// Variável idade que é uma lista
const idade = [1, 2, 3, 4, 5];

// Variável numerosEmDobros que vai ter a variável idade e a função map passando o callback como parâmetro
let numerosEmDoblos = idade.map(Numero);

// Função chamada Numero que vai retornar uma multiplicação por 2 que está sendo passada anteriormente como callback
function Numero(valor) {
   return valor * 2;
}

// Vai exibir a lista multiplicada por 2 ou seja, o dobro (2, 4, 6, 8, 10)
console.log(numerosEmDoblos);
```






## Função Filter:


O **filter** percorre a lista e filtra apenas os itens que atende uma condição dentro por exemplo de uma função. Reduzindo uma lista menor ou criando do mesmo tamanho.





```javascript
Variável idade vai conter uma Arraylista

const idades = [1, 2, 3, 4, 5]

Essa outra variável idade tem a variável idade
que vai ser filtrada pela função filter que dentro do parâmetro vai chamar o Callback
let idade = idades.filter(Numero)



Função chamada número que vai retornar igual
ou maior do que 3 que foi passado anteriormente como callback dentro da variável idade

function Numero(maior) {
   return maior >= 3
}
console.log(idade);

```




##Função Reduce:


O **reduce** vai iterar uma lista  acumulando todos os valores em um único resultado.


```javascript
A variável idade armazena uma lista

const idade = [1, 2, 3, 4, 5];

Variável NúmeroSomado vai armazenar a variabilidade e a função reduce passando o Callback como parâmetro

let NumeroSomado = idade.reduce(Numero);


A função número vai retornar a soma 
um mais a soma 2 que foi passado callback para a variável NúmeroSomado

function Numero(soma1, soma2) {
   return soma1 + soma2
}


Vai exibir a somatória total dos números na lista (15)

console.log(NumeroSomado);

```


