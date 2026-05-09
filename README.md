# ArrayListJs


## Função Map:


### O map percorre toda a lista e transforma cada item dentro da lista em um novo valor, criando uma nova lista com os resultados.

> Variável idade que é uma lista
```

const idade = [1, 2, 3, 4, 5];
```


> Variável NúmerosEmDobros que vai ter a variável idade e a função map passando o callback como parâmetro
```
let numerosEmDoblos = idade.map(Numero);
```
> Função chamada Número que vai retornar uma multiplicação por 2 que está sendo passado anteriormente como callback na variável NúmerosEmDobros
```
function Numero(valor) {
   return valor * 2
}
```
> Vai exibir a lista multiplicada por 2 ou seja, o dobro (2, 4, 6, 8, 10)
```
console.log(numerosEmDoblos);
```
