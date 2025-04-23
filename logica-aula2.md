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

| p   | q   | (p^q) | (p ^ q) -> (p ^ q) |
| --- | --- | ----- | ------------------ |
| v   | v   | v     | v                  |
| -   | -   | -     | -                  |
| v   | f   | f     | v                  |
| -   | -   | -     | -                  |
| f   | v   | f     | v                  |
| -   | -   | -     | -                  |
| f   | f   | f     | v                  |
| -   | -   | -     | -                  |

13.2. Contradição

Em contraste com a tautologia, uma contradição é uma proposição em que todos os valores são falsos.

exemplo P(p,q)= ~(p V q) ^ (p ^ q)

| p   | q   | (p^q) | (p V q) | ~ (p V q) | ~(pVq)^(p^q) |
| --- | --- | ----- | ------- | --------- | ------------ |
| v   | v   | v     | v       | f         | f            |
| -   | -   | -     | -       | -         | -            |
| v   | f   | f     | v       | f         | f            |
| -   | -   | -     | -       | -         | -            |
| f   | v   | f     | v       | f         | f            |
| -   | -   | -     | -       | -         | -            |
| f   | f   | f     | f       | v         | f            |
| -   | -   | -     | -       | -         | -            |

13.3. Contingência
Uma proposição que não é uma tautologia e nem uma contradição é uma contingência.

14. Implicação Lógica  
    A proposição P implica a proposição Q se, e somente se, a condicional P -> Q for uma tautologia. Representa-se por => Q, e se lê "P implica Q".

15. Equivalência Lógica
    A proposição P é equivalente à proposição Q se, e somente se, a bicondicional P <-> Q for uma tautologia, ou que P e Q tenham a mesma tabela verdade. Representa-se por P <=> e se lê "P é equivalente a Q".

16. Teorema Contra recíproco ou Contrapositivo
    A equivalência lógica (𝑝 → 𝑞) ⇔ (~𝑞 → ~𝑝)
    demonstrada significa que , se 𝑝 → 𝑞 é V, então
    𝑝 ⇒ 𝑞 é 𝑒𝑞𝑢𝑖𝑣𝑎𝑙𝑒𝑛𝑡𝑒 𝑎 (~𝑞) ⇒ (~𝑝)

    [logica aula 1](logica-aula1.md)
    [provas matemáticas](provas-matematicas.md)
