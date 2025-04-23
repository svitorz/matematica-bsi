# Teoria sobre Conjuntos, Lógica e Números Complexos

## Leis de De Morgan

As **Leis de De Morgan** são regras fundamentais da Teoria dos Conjuntos e da Lógica que descrevem a relação entre as operações de união, interseção e complementação.

1. **Primeira Lei de De Morgan**
   \[
   (A \cup B)' = A' \cap B'
   \]
   Equivalente lógica:
   \[
   \sim (p \lor q) \equiv (\sim p) \land (\sim q)
   \]
   Ou seja, a negação da disjunção é equivalente à conjunção das negações.

2. **Segunda Lei de De Morgan**
   \[
   (A \cap B)' = A' \cup B'
   \]
   Equivalente lógica:
   \[
   \sim (p \land q) \equiv (\sim p) \lor (\sim q)
   \]
   Ou seja, a negação da conjunção é equivalente à disjunção das negações.

---

## Teoria Complementar

### Propriedade do Complemento

- Para qualquer conjunto \( A \), vale:
  \[
  (A')' = A
  \]
  Esta propriedade afirma que o complemento do complemento de um conjunto resulta no próprio conjunto.

### Inclusões

- Teorema 1: Para todo conjunto \( A \),
  \[
  A \subseteq A
  \]

- Teorema 3: Se \( A \subseteq B \) e \( B \subseteq C \), então:
  \[
  A \subseteq C
  \]

---

## Números Racionais e Irracionais

- Uma soma infinita da forma:
  \[
  2 + 2 + 2 + 2 + \dots
  \]
  não é convergente, portanto **não representa um número racional nem irracional** — ela é indefinida no conjunto dos números reais.

---

## Números Complexos

Equações a serem resolvidas no conjunto dos números complexos \( \mathbb{C} \):

1. \( x^2 + 100 = 0 \)
2. \( x^2 - 6x + 10 = 0 \)
3. \( -x^2 + 4x - 29 = 0 \)
4. \( x^4 + 5x^2 + 6 = 0 \)

Estas equações envolvem raízes complexas, e sua resolução exige o uso da fórmula de Bhaskara e fatorações.

---

## Representações com Diagramas de Venn

- Para ilustrar as Leis de De Morgan:

  - \( A \cup B' = A' \cap B' \)
  - \( A \cap B' = A' \cup B' \)

- Para ilustrar a igualdade:
  \[
  A \cap B' = A - B
  \]
  Usamos o diagrama de Venn para destacar os elementos de \( A \) que não pertencem a \( B \).

---

[provas matematicas](provas-matematicas.md)
