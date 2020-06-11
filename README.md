<h1 align="center">Estudos em JavaScript</h1>

Meus estudos em JavaScript.

### :rocket: Tecnologias
- JavaScript

### :page_with_curl: Estudos

#### FILTER

```bash

Array.prototype.filter()
Cria um novo array com todos os elementos que passaram no teste da função fornecida.

var newArray = arr.filter(callback[, thisArg])

```

#### MAP

```bash

Array.prototype.map()
Chama o callback para cada elemento e devolve um novo array com a mesma quantidade de items

var newArray = arr.map(callback[, thisArg])

```

#### REDUCE

```bash

Array.prototype.reduce()
Executa uma função para cada elemento retornando um único valor de retorno

var newArray = arr.map(callback[, valorInicial])

```

#### PROMISE

```bash

Promise.prototype.then()
Promise.prototype.catch()
As promessas simplificam os cálculos adiados e assíncronos. 
Uma promessa representa uma operação que ainda não foi concluída.

const promise1 = new Promise((resolve, reject) => { resolve('Success!'); });
promise1.then((value) => { console.log(value); }); // expected output: "Success!"

const promise1 = new Promise((resolve, reject) => { throw 'Uh-oh!'; });
promise1.catch((error) => { console.error(error); }); // expected output: Uh-oh!

```

## :memo: Licença
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<h4 align="center">
    Feito com ❤ por <a href="https://www.linkedin.com/in/julio-nery/" target="_blank">Júlio Nery</a>!
    <g-emoji class="g-emoji" alias="wave" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f44b.png">👋</g-emoji>
</h4>
