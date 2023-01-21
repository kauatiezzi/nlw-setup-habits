Variaveis: Uma caixinha onde guardamos um tipo de dado para usar mais tarde.

Tipos de dados que recebem: texto, números, booleanos (vdd/falso) ou dados mais estruturados.

```js
// declaro e atribuo valor
let boasVindas = "Fala, Dev!"

// retribuo valor
boasVindas = `Fala, Dev! Tudo beleza?!`

// constante não muda o valor
const serHumano = true
serHumano = false // Erro!
```

Funções:

- Agrupamento de código
- Reuso de código
- Mini programas dentro do programa maior.
- Toda linguagem oferece muitas opções.

```js
// usando uma função
alert("Fala, Dev!")

// criando uma função

function alert(text) {
  return text
}
```

Objetos:

- é tudo sobre objetos.

* Atributos: São as propriedades de um objeto.

* Métodos: São as funcionalidades de um objeto.

```js
const celular = {
  cor: "preto", // string
  ligar: function () {
    const mensagem = "Ligando"
  }, // recebendo uma função
}

// usando o objeto

alert(celular.cor) // preto
celular.ligar()
```
