
#### Exercício 1

Calcule os juros vencidos por um capital de 20.000€ durante o período de 5 meses, sendo que o mesmo capital vencerá juros mensalmente, __em regime de juro simples__, à taxa anual nominal de 4,5%.

__R__:

Juro vencido ao final do 1º mês: 20.000€ x 0,045/12 = 75€

Juro vencido ao final do 2º mês: 75€

Juro vencido ao final do 3º mês: 75€

Juro vencido ao final do 4º mês: 75€

Juro vencido ao final do 5º mês: 75€

$$ Total = \text{75€} \times \text{5} = \text{375€} $$

$$ Total = \text{20.000€} \times \text{5} \times \text{(0.045/12)} = \text{375€} $$

&nbsp;

#### Exercício 2

Um capital de 80.000€ aplicado em regime de juro composto à taxa anual de 4% produziu, num certo prazo t, um valor acumulado de 97.333€. Calcule o prazo de aplicação.

__R__:

$$ C_t = C_0(1 + r)^t $$

$$ t = \log_{1+r}{(\frac{C_t}{C_0})} = \frac{\log{(\frac{C_t}{C_0})}}{\log{(1+r)}} $$

$$ 97.333 = 80.000(1 + 0.04)^t $$

$$ t = \frac{\log{(\frac{97.333}{80.000})}}{\log{(1+0.04)}} = 5.0002 $$

Ou seja, o prazo de aplicação foi de 5 anos.

&nbsp;

#### Exercício 3

Um capital aplicado à taxa anual de 2% em regime de juros compostos gerou ao fim de quatro anos o valor acumulado de 108.243,216€. Qual o valor do capital inicialmente aplicado?

__R__:

$$ VA = \frac{C_n}{(1 + r)^n} $$

$$ VA = \frac{108.243,216}{(1 + 0,02)^4} = \text{100.000€} $$

O valor do capital inicialmente aplicado é 100.000€.

&nbsp;

#### Exercício 4

Se a taxa de juro **nominal $(r_n)$** = 2% e a taxa de inflação $(i)$ for de 1.5%, qual será a taxa de juro **real $(r_r)$**?

__R__:

$$ \small \text{1 + taxa nominal} = \text{(1 + taxa real)} \times \text{(1 + taxa inflação)} $$

$$ \small \text{1 + 0,02} = \text{(1 + taxa real)} \times \text{(1 + 0,015)} $$

$$  r_r = \frac{1 + r_n}{1 + i} - 1 = \frac{1 + 0,02}{1 + 0,015} - 1 = 0,492\%$$

$$  r_r \approx r_n - i = 2\% - 1,5\% = 0,5\% $$


&nbsp;

#### Exercício 5

Um investidor aplicou 1.000€ num depósito bancário por um ano, sendo que a taxa de juro anual real obtida foi de 6%. Sabendo que, nesse ano, a taxa de inflação foi de 6%, qual a taxa de juro anual nominal oferecida pelo banco?

__R__:

$$ \small \text{1 + taxa nominal} = \text{(1 + taxa real)} \times \text{(1 + taxa inflação)} $$

$$ \small \text{1 + taxa nominal} = \text{(1 + 0,06)} \times \text{(1 + 0,06)} $$

$$ \small \text{taxa nominal} = \text{1,06} \times \text{1,06} - 1 = 0,1236 = 12,36\% $$

&nbsp;

#### Exercício 6

Um empréstimo bancário paga juros à taxa de 3% ao trimestre. Qual é a taxa de juro anual $r_a$ equivalente?

__R__:

$$ (1+r_k)^k = 1 + r_a $$

Um ano tem 4 trimestres, logo $k=4$ e $r_4=3\%$. Assim:

$$ (1+0,03)^4 = 1 + r_a $$

$$ r_a  = (1+0,03)^4 - 1 = 0,1255 = 12,55\% $$

Assim, se o empréstimo for de $\text{1.000€}$, pagar $r_4=3\%$ ao trimestre, ou seja $\text{30€}$, é equivalente a pagar $\text{12,55}\% \times \text{1.000€} = \text{125,5€}$ no fim do ano, no pressuposto que os $\text{1.030€}$ obtidos no fim do 1º trimestre podiam ser aplicados a $3\%$ ao trimestre e assim sucessivamente até ao final do ano.

&nbsp;

#### Exercício 7

Na sequência do [Exercício 6](exercicios_2.md#exercicio-6), mas agora com juros de $10\%$ vencidos ao **semestre**.

__R__:

Neste caso $r_2=10\%$, pelo que a taxa de juro anual $r_a$ equivalente, ou seja, a TAE (Taxa Anual Efetiva) é:

$$ r_a  = (1+0,1)^2 - 1 = 0,21 = 21\% $$

A TAN (Taxa Anual Nominal) é:

$$ TAN  = 2 \times 10\% = 20\% $$

!!! Note 
    Trata-se de uma aplicação à Taxa Anual Nominal (TAN) de 20%, com capitalização de juros semestralmente, **equivalente** a uma aplicação com capitalização dos juros no final do ano à Taxa Anual Efetiva (TAE) de 21%.


<figure markdown>
  <img src="../images/tabela_36.png" width="600">
  <figcaption>Taxa Anual Nominal (TAN) e Taxa Anual Efetiva (TAE)</figcaption>
</figure>

&nbsp;

#### Exercício 8

Se a taxa de juro anual **nominal ($r_n$)** for $2\%$ e a a taxa de inflação ($i$) for $1,5\%$, e tendo calculado anteriormente a taxa de juro real como $0,492\%$,$1.000$€ recebidos hoje capitalizam ao fim de 1 ano:

a) em termos nominais (ou seja, a preços correntes)?

b) em termos reais (ou seja, a preços constantes do ano $0$)?


