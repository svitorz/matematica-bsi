# Noções de Lógica

1. Conjunto de palavras ou símbolos que expressam/afirmam uma ideia. (Normalmente com SVP + Afirmação).

2. Principios fundamentais
   2.1. Princípio da não contradição - Não pode ser Verdadeira e falsa simultaneamente
   2.2. Principio do Terceiro Excluído - Apenas duas opções, ou Verdadeira, ou falsa.

3. Valor lógico
   3.1. Valor lógico verdadeiro ou valor lógico falso.

4. Uso de conectivos
   (não, e, ou, se.. então, se e somente se..)

5. Proposições Simples e Compostas
   5.1. Simples: Uma única ideia
   5.2. Compostas: Duas ou mais proposições ligafas por conectivos

6. Tabela verdade
   Suponhamos uma proposição P(r,s):

| r   | s   |
| --- | --- |
| v   | v   |
| -   | -   |
| v   | f   |
| -   | -   |
| f   | v   |
| -   | -   |
| f   | f   |
| -   | -   |

O número de linhas é representado pelo número de afirmações.
P(p1,p2,p3,pn) então o número de linhas é representado por 2^n (dois elevado a n).

7. Negação
   A negação simplesmente inverte o valor da afirmação. Então:

   | p   | ~p  |
   | --- | --- |
   | v   | f   |
   | -   | -   |
   | f   | v   |
   | -   | -   |

8. Conectivo "E" e a Conjunção
   Suponhamos uma proposição P(p,q)

8.1. No conectivo "E", essa proposição só será verdadeira quando p e q forem verdadeiras.

8.2 Todos os demais casos serão falsos.

| p   | q   | p^q |
| --- | --- | --- |
| v   | v   | v   |
| -   | -   | -   |
| v   | f   | f   |
| -   | -   | -   |
| f   | v   | f   |
| -   | -   | -   |
| f   | f   | f   |
| -   | -   | -   |

9. Conectivo "OU" e a Disjunção

8.1. Verdadeiro quando _pelo menos uma_ das proposições é verdadeira

8.2. Falso quando as duas forem falsas

| p   | q   | p v q |
| --- | --- | ----- |
| v   | v   | v     |
| -   | -   | -     |
| v   | f   | v     |
| -   | -   | -     |
| f   | v   | v     |
| -   | -   | -     |
| f   | f   | f     |
| -   | -   | -     |

[aula 2](logica-aula2.md)
