+++
title = 'Arrays em GOLANG'
date = 2024-09-25T21:30:24+01:00
draft = false
description = "Aprendendo sobre arrays em GO"
image = "/images/p5golang.png"
imageBig = "/images/p5golang.png"
categories = ["golang", "tech"]
authors = ["Gustavo Bueno"]
avatar = "/images/avatar1.jpeg"
+++

# Definição

Em Golang, arrays são uma coleção de elementos do mesmo tipo com tamanho fixo, definidos no momento da declaração.

---

# Sintaxe básica

Modelo:

`var nomeArray [tamanho]tipo`

Exemplo:

`var numeros [5]int`


---

# Inicialização

Podemos inicializar os elementos do array no momento da declaração

`var letras = [3]string{"a", "b", "c"}`


---

# Como acessar os elementos

Você pode acessar e modificar os elementos de um array usando o índice (começando em 0)

```
numeros[0] = 10   // Altera o primeiro elemento do array para 10
fmt.Println(numeros[0])  // Exibe o valor do primeiro elemento
```

---

# Comprimento de arrays

`fmt.Println(len(numeros))  // Saída: 5`

A função len pode ser usada para obter o comprimento (número de elementos) de um array

---

# Arrays são de tamanhos fixos

Um ponto importante sobre arrays em Go é que seu tamanho é imutável após a criação. Arrays de tamanhos diferentes são considerados tipos diferentes. Se você precisar de uma coleção dinâmica de elementos, deve usar slices em vez de arrays. O próximo post será sobre eles.![alt text](image.png)