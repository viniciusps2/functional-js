# functional-js
Curated discussion about Functional Programming in JS

## FP

tem algo mais do q OO

OO já é o paradigma velho em JS q eu me arrependo de ter enfatizado tanto nos ultimos meses

OO bom, que faz sentido instanciar classe, só temos no mongoose (ORM, precisa guardar estado)

o ponto forte do js não é OO, é multiparadigma, é OO quando se aplica, mas FP na maioria dos casos

podemos usar um FP leve, usando funções puras, sem efeito colateral, sem multar dado

usando so os principios

só de usar função, sem efeito colateral, fazer as funções conhecer menos possivel dos objetos q recebe (ex. função q cria etiqueta, sabia mto do core, totalmente acoplada)

pare de usar classe quando não precisa!

instanciar nova classe, guardar estado, mutar estado desnecessariamente

qnd resolveria com função q tem um scopo mais isolado

pra q instanciar uma classe com um método?? mtas vezes ela pode ser só uma função, q é mto mais reutilizável


## clojure

ele é usado mtas vezes como IIFE


no front, p/ isolar


mas tem mto mais usos q isso



function createCounter () {
	let count = 0
	return function () {
		return ++count
	}
}

let counter = createCounter()

counter()
// 0


counter()
// 1

## referencias

https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Closures

http://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-intro/

