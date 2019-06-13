# Aplicativos Web
## Lista de Exercícios 2 – JavaScript

Para realizar os exercícios a seguir, NÃO utilize a visualização para dispositivos móveis.

1.	**(40%)** Selecione a div1 e defina um evento que faça com que quando a div1 for clicada (evento `click`), uma nova div seja criada e adicionada ao final da sequência. Sugere-se a utilização dos seguintes recursos:

```js
document.querySelector()
document.createElement()
elemento.addEventListener()
elemento.append()
```

2.	**(20%)** Selecione a div2 e defina um evento que faça com que quando o mouse passar sobre a div2 (evento `mouseover`), esta div seja escondida. Sugere-se a utilização dos seguintes recursos:

```js
document.querySelector()
elemento.addEventListener()
elemento.style.display
```

3.	**(40%)** Selecione todos os elementos `div` existentes e adicione a cada um deles, menos `div1` e `div2`, um evento que faça com que quando o elemento for clicado duas vezes em um curto intervalo de tempo (evento `dblclick`), após 1 segundo, a cor de fundo do elemento seja alterada para `#FFF`. Sugere-se a utilização dos seguintes recursos:

```js
document.querySelector()
elemento.addEventListener()
elemento.style.backgroundColor
setTimeout
```