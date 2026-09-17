# Code Kata

## Contador em segundos (Closures)

Analise o código abaixo. O objetivo inicial era fazer o console exibir `1, 2, 3... 10`, com um intervalo de 1 segundo entre cada número.

```js
function rodarContador() {
  for (var i = 1; i <= 10; i++) {
    setTimeout(function() {
      console.log(i);
    }, i * 1000);
  }
}

rodarContador();
```
