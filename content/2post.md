+++
title = 'Primeiro hello world em GOLANG'
date = 2024-09-24T08:00:24+01:00
draft = false
description = "Entendendo as primeiras linhas de código"
image = "/images/p2golang.png"
imageBig = "/images/p2golang.png"
categories = ["golang", "tech"]
authors = ["Gustavo Bueno"]
avatar = "/images/avatar1.jpeg"
+++

# Código que será utilizado
Primeiramente crie um arquivo main.go e cole o seguinte código:
```
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

Rode no terminal o comando: `go run main.go`

---

# package main
Todo código GO começa com a declaração de um pacote. O pacote main é o ponto de partida do programa. Quando é feita a execução de um programa GO, ele procura a função main.

---

# import "fmt"
Importa o pacote fmt (abreviação de format). É um pacote com funções para formatar entrada e saída de dados.

---

# func main()
Função principal de um programa GO. Toda execução começa por essa função.

---

# fmt.Println("Hello, World!")
Usando o pacote fmt, chamamos a função Println que vai imprimir o "Hello World" no console e adicionar uma linha no final.
Se não quisessemos a linha no final, poderíamos usar a função Print em vez da Println.

