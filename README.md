# Computation-Theory
ISCTE subject

### Partição de um Conjunto

Uma **partição** de um conjunto é uma coleção de subconjuntos não vazios, disjuntos e cuja união é o conjunto original. Em outras palavras, uma partição divide um conjunto em partes distintas, onde cada elemento do conjunto original pertence a exatamente uma das partes. 

#### Propriedades de uma Partição:
1. **Não Vazio:** Cada subconjunto na partição deve ser não vazio.
2. **Disjunto:** Os subconjuntos são mutuamente disjuntos, ou seja, não têm elementos em comum.
3. **Cobertura Completa:** A união de todos os subconjuntos na partição deve resultar no conjunto original.

**Exemplo:**
Se temos um conjunto \(A = \{1, 2, 3, 4\}\), uma partição de \(A\) pode ser:
\[ \{\{1, 2\}, \{3\}, \{4\}\} \]

### Relação de um Conjunto

Uma **relação** em um conjunto é um conjunto de pares ordenados. Uma relação \(R\) em um conjunto \(A\) é um subconjunto do produto cartesiano \(A \times A\). Isso significa que cada par \((a, b)\) na relação \(R\) representa uma conexão entre os elementos \(a\) e \(b\) do conjunto \(A\).

#### Propriedades de uma Relação:
1. **Reflexiva:** Cada elemento está relacionado consigo mesmo, ou seja, \((a, a) \in R\) para todo \(a \in A\).
2. **Simétrica:** Se \((a, b) \in R\), então \((b, a) \in R\).
3. **Transitiva:** Se \((a, b) \in R\) e \((b, c) \in R\), então \((a, c) \in R\).

**Exemplo:**
Se temos um conjunto \(A = \{1, 2, 3\}\), uma relação \(R\) em \(A\) pode ser:
\[ R = \{(1, 2), (2, 3), (1, 3)\} \]

### Diferença entre Partição e Relação

- **Partição:**
  - Divide um conjunto em subconjuntos disjuntos e não vazios.
  - Cada elemento do conjunto original pertence a exatamente um subconjunto da partição.
  - Exemplo: \(\{ \{1, 2\}, \{3\} \}\) é uma partição de \(\{1, 2, 3\}\).

- **Relação:**
  - Define pares ordenados de elementos dentro do mesmo conjunto.
  - Descreve como os elementos do conjunto se relacionam uns com os outros.
  - Exemplo: \(\{(1, 2), (2, 3)\}\) é uma relação em \(\{1, 2, 3\}\).

### Resumo

- **Partição**: Subdivide um conjunto em partes não sobrepostas que cobrem todo o conjunto.
- **Relação**: Estabelece conexões (pares ordenados) entre os elementos de um conjunto.

Enquanto uma partição está focada em dividir o conjunto em subconjuntos específicos, uma relação está preocupada em como os elementos do conjunto se conectam entre si através de pares ordenados.


### Classe de Equivalência

Uma **classe de equivalência** é um subconjunto de um conjunto, definido a partir de uma relação de equivalência. Uma relação de equivalência em um conjunto divide este conjunto em classes de equivalência, onde todos os elementos de uma classe são considerados equivalentes uns aos outros segundo a relação dada.

#### Relação de Equivalência

Para que uma relação \( R \) em um conjunto \( A \) seja uma relação de equivalência, ela deve ser:

1. **Reflexiva:** Cada elemento está relacionado consigo mesmo. Formalmente, \( \forall a \in A, (a, a) \in R \).
2. **Simétrica:** Se \( a \) está relacionado com \( b \), então \( b \) está relacionado com \( a \). Formalmente, \( \forall a, b \in A, (a, b) \in R \Rightarrow (b, a) \in R \).
3. **Transitiva:** Se \( a \) está relacionado com \( b \) e \( b \) está relacionado com \( c \), então \( a \) está relacionado com \( c \). Formalmente, \( \forall a, b, c \in A, (a, b) \in R \text{ e } (b, c) \in R \Rightarrow (a, c) \in R \).

#### Definição de Classe de Equivalência

Para uma relação de equivalência \( R \) em um conjunto \( A \), a classe de equivalência de um elemento \( a \in A \), denotada por \([a]\), é o conjunto de todos os elementos de \( A \) que estão relacionados com \( a \) segundo a relação \( R \). Formalmente,

\[ [a] = \{ x \in A \mid (a, x) \in R \} \]

#### Propriedades das Classes de Equivalência

1. **Desunião:** Classes de equivalência diferentes são disjuntas; não têm elementos em comum. Se \([a] \neq [b]\), então \([a] \cap [b] = \varnothing\).
2. **Cobertura Completa:** A união de todas as classes de equivalência é o conjunto original \( A \).

#### Exemplo de Classe de Equivalência

Considere o conjunto \( A = \{1, 2, 3, 4, 5, 6\} \) e a relação de equivalência \( R \) definida por "ter a mesma paridade" (ou seja, ser ambos pares ou ambos ímpares).

- Reflexiva: Cada número tem a mesma paridade que ele próprio.
- Simétrica: Se um número é par e outro é par, ou se um número é ímpar e o outro é ímpar, a relação é simétrica.
- Transitiva: Se um número é par e outro é par, e um terceiro número também é par, a relação é transitiva (o mesmo para ímpares).

As classes de equivalência são:

- Classe de equivalência dos números pares: \(\{2, 4, 6\}\)
- Classe de equivalência dos números ímpares: \(\{1, 3, 5\}\)

#### Resumo

- **Classe de Equivalência**: Subconjunto de um conjunto definido a partir de uma relação de equivalência, onde todos os elementos são equivalentes entre si segundo a relação.
- **Relação de Equivalência**: Relação que é reflexiva, simétrica e transitiva, usada para definir classes de equivalência.
- **Propriedades**: Classes de equivalência são disjuntas e cobrem completamente o conjunto original.

As classes de equivalência particionam o conjunto em subconjuntos disjuntos onde cada elemento do conjunto original pertence a exatamente uma classe, e todos os elementos de uma classe são considerados equivalentes segundo a relação dada.
