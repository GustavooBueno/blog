+++
title = 'Declaração e atribuição de variáveis em GOLANG'
date = 2024-09-24T08:30:24+01:00
draft = false
description = "Como funciona a declaração e atribuição de variáveis em GO"
image = "/images/p3golang.png"
imageBig = "/images/p3golang.png"
categories = ["golang", "tech"]
authors = ["Gustavo Bueno"]
avatar = "/images/avatar1.jpeg"
+++

# A regra de GO
- Variáveis que forem declaradas devem ser utilizadas, se não o programa irá apontar um erro.
- A declaração pode ocorrer de forma **explícita** ou **implícita**.

---

# Forma explícita
`var x int`

---

# Forma implícita
`var z = 10`

Go infere que z é do tipo int

---

# Múltiplas declarações 
Podemos fazer:

`var a, b, c int`

Ou então:

```
var(
    a int
    b string
    c float64
)
```

---

# Atribuição
Atribuição pode ser feita de forma **direta** ou **separada** na declaração
- Direto:

`var y string = "Hello, Go!"`

- Separada:

`var y string`

`y = "Hello, Go!"`

--- 

# Declaração curta
**Muito utilizado**. Não usa var, declara e atribui.

`x := 10`

Go infere que 'x' é do tipo int.

O := deve ser usado apenas quando estiver declarando a variável.

--- 

# Valores das variáveis declaradas
Quando declaramos uma variável, mas não atribuimos nenhum valor a ela. Podemos ter os seguintes casos em GO:
- int e float serão 0
- string será ""
- bool será false
- Ponteiros, slices, maps, channels, interfaces, e funções são nil

--- 

# Constantes
Em Go temos também as constantes

`const pi = 3.14`

---

# Escopo
- **Escopo de Pacote**: Variáveis declaradas fora das funções, no topo do arquivo, são acessíveis em todo o pacote.
- **Escopo de Função**: Variáveis declaradas dentro de uma função são locais àquela função.
