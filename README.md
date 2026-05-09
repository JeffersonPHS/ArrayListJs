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
