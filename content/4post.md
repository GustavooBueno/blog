+++
title = 'Tipos em GOLANG'
date = 2024-09-25T20:30:24+01:00
draft = false
description = "Passando pelos tipos que existem em GO"
image = "/images/p4golang.png"
imageBig = "/images/p4golang.png"
categories = ["golang", "tech"]
authors = ["Gustavo Bueno"]
avatar = "/images/avatar1.jpeg"
+++

# Tipos básicos

1. Tipos Numéricos Inteiros
    - int - inteiro
    - uint - inteiro sem sinal

2. Tipos Numéricos de Ponto Flutuante
    - float32 ou float64

3. Booleanos
    - bool

4. Strings
    - string

---

# Tamanho das variáveis
Podemos especificar o tamanho das variáveis em bits: int8, int16, int32, int64

---

# Como criar um tipo

```
package main

import "fmt"

type ID string

func main() {
	var palavra ID = "IDteste"

	fmt.Println(palavra)
}
```

Escreva type (nome do tipo) (tipo)

---

# Como printar uma variável baseado em seu tipo

Principais:

1. %d - inteiro
2. %f - ponto flutuante (%.2f para definir casas decimais)
3. %s - string
4. %t - booleano
5. %p - ponteiro
6. %v - qualquer valor


