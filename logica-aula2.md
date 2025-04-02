## Aula 2

10. Conectivo SE... Então

'Se p então q' só sera falsa quando p for verdadeira e q for falsa.

| p   | q   | p -> q |
| --- | --- | ------ |
| v   | v   | v      |
| -   | -   | -      |
| v   | f   | f      |
| -   | -   | -      |
| f   | v   | v      |
| -   | -   | -      |
| f   | f   | v      |
| -   | -   | -      |

## Recíproca q -> p

| p   | q   | p -> q |
| --- | --- | ------ |
| v   | v   | v      |
| -   | -   | -      |
| v   | f   | v      |
| -   | -   | -      |
| f   | v   | f      |
| -   | -   | -      |
| f   | f   | v      |
| -   | -   | -      |

11. SE E SOMENTE SE, e a bicondicional

A bicondicional "p se e somente se q" é uma proposição cujo valor lógico é V quando p e q são ambas verdadeiras ou ambas falsas.

| p   | q   | p <-> q |
| --- | --- | ------- |
| v   | v   | v       |
| -   | -   | -       |
| v   | f   | f       |
| -   | -   | -       |
| f   | v   | f       |
| -   | -   | -       |
| f   | f   | v       |
| -   | -   | -       |

12. Tabela verdade de uma Proposição Composta
    Considerando a proposição "[ (p v q) -> (~p) ] -> (p^q)"

| p   | q   | (p v q) | (~p) | (p v q) -> (~p) | (p^q) | (p v q) -> (~p) -> (p^q) |
| --- | --- | ------- | ---- | --------------- | ----- | ------------------------ |
| v   | v   | v       | f    | f               | v     | v                        |
| -   | -   | -       | -    | -               | -     | -                        |
| v   | f   | v       | f    | f               | f     | v                        |
| -   | -   | -       | -    | -               | -     | -                        |
| f   | v   | v       | v    | v               | f     | f                        |
| -   | -   | -       | -    | -               | -     | -                        |
| f   | f   | f       | v    | v               | f     | f                        |
| -   | -   | -       | -    | -               | -     | -                        |

13. Tautologia, Contradição e Contingência

13.1. Tautologia é uma proposição composta P(p,q,r,...), que sempre será verdadeira. São chamadas de proposições logicamente verdadeiras.

A expressão dada é:
(p^q)->(p^q)

| p   | q   | (p^q) | (p^q)->(p^q) |
| --- | --- | ----- | ------------ |
| v   | v   | v     | v            |
| -   | -   | -     | -            |
| v   | f   | f     | v            |
| -   | -   | -     | -            |
| f   | v   | f     | v            |
| -   | -   | -     | -            |
| f   | f   | f     | v            |
| -   | -   | -     | -            |

13.2 Contradição
