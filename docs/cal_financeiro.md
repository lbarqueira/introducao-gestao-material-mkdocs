# Introdução ao cálculo financeiro


## Investimento e despesa corrente

__Investimento__: é a aplicação de recursos limitados feita com vista a obter retorno(s) no futuro, por contrapartida a despesa corrente que se confina ao momento em que ocorre.

Na análise de um projeto de investimento procura-se avaliar se a afetação de recursos ($\text{R}$), feita inicialmente, é capaz de vir a gerar uma sucessão de benefícios líquidos ($\text{B}$) que excedem esse investimento inicial.

$$ -\text{ R}-\text{R}-\text{R}+\text{B}+\text{B}+\text{B } ... +\text{B} $$

Para essa avaliação põe-se a questão de saber como obter esses recursos, ou seja, como financiar o projecto, através de capital próprio ou alheio, e de saber como prever os benefícios e custos futuros.


## O valor temporal do dinheiro

Concentrando-nos num domínio puramente financeiro, os recursos ($\text{R}$) e os benefícios ($\text{B}$) representam dinheiro, fluxos financeiros negativos ou positivos, designados em inglês por _cash flows_ (negativos, representados por $\text{CF}-$, ou $\text{C}-$; positivos representados por $\text{CF}+$, ou $\text{C}+$).

Idealmente, estaremos interessados em investir em projetos em que a soma dos $\text{CF}-$ seja inferior à soma dos $\text{CF}+$. O problema é que esta análise é dependente do tempo e, com o tempo, o dinheiro está sujeito a determinados fatores como, por exemplo, a inflação e os juros. Ora, para saber como lidar com juros e somar ou comparar fluxos financeiros em diferentes momentos de tempo temos que atender a alguns principios do _Cálculo Financeiro_.

## Capitalização e atualização. Juros simples e compostos

__Suponha que tem 1.000€ hoje, no ano $0$, e pretende depositá-los no banco. O que vai acontecer?__

Ao depositar os 1.000€ no banco, estes ficam a render a uma dada _taxa de juro anual_.

Ao fim de 1 ano, há duas hipóteses:

- __Levantar o juro__ ficando apenas o capital inicial $\rightarrow$ deixar nessa conta só o montante inicial, levantando os juros todos os anos (__regime juros simples__ - os juros não acumulam ao capital);

- __Acumular o juro__ ao capital $\rightarrow$ depositá-los numa conta a prazo em que os juros vencidos ficam a acumular nessa conta gerando mais juros (__regime juros compostos__ - esquema de capitalização).

Assim:

__Capital ou depósito inicial = 1.000 €__;

__r =  taxa de juro anual = 5%__;

>_Nota: Fluxo < 0 $\leftrightarrow$ pagamento; Fluxo > 0 $\leftrightarrow$ recebimento_

__Juros Simples__

<figure markdown>
  <img src="../images/tabela_33.png" width="600">
  <figcaption>Juros Simples</figcaption>
</figure>



$$ C_n = rC_0​+C_0​=(1+r)C_0​ $$

__Juros Compostos $\leftrightarrow$ Neste caso há capitalização__

<figure markdown>
  <img src="../images/tabela_34.png" width="600">
  <figcaption>Juros Compostos</figcaption>
</figure>



$$ C_n = C_0(1 + r)^n $$

Em que $n$ é o número de anos.

O __processo de capitalização__ permite por sua vez chegar, de forma inversa, à noção de __atualização__, em que se faz o cálculo do valor atual ($VA$) ou presente de dinheiro a receber no futuro, sendo a respetiva taxa designada por __Taxa de Atualização__ ($r$).

$$ VA = \frac{C_n}{(1 + r)^n} $$

Em que $C_n$ é o valor a receber daqui a $n$  anos e $r$ a taxa de juros.

Por exemplo, o __valor atual__ ($VA$) de 1.100€ recebidos 1 ano depois, supondo uma taxa de juro para aplicações semelhantes de 10% ao ano, é igual a:

$$ VA = \frac{1.100}{(1 + 0.1)^1} = \text{1.000€} $$

O $VA$ de 1.210€ a receber ao fim de 2 anos é também igual a:

$$ VA = \frac{1.210}{(1 + 0.1)^2} = \text{1.000€} $$

Notar que estas fórmulas pressupõem que a taxa de juro usada como taxa de atualização **se mantém ao longo do tempo**. Se por exemplo, a taxa de atualização variar entre o ano $1$ e o ano $2$, sendo $r_1 = 10\%$ e $r_2 = 5\%$, então o $VA$ de 1.210€ recebidos no fim do ano $2$ será dado por:

$$ VA = \frac{1.210}{(1 + 0.1)(1 + 0.05)} = \text{1.047,62€} $$

__Capitalização versus Atualização__

<figure markdown>
  <img src="../images/tabela_35.png" width="600">
  <figcaption>Capitalização versus Atualização</figcaption>
</figure>

>Ver [Exercício 1](exercicios_2.md#exercicio-1) para exemplo de cálculo de juros em regime de juro simples.

>Ver [Exercício 2](exercicios_2.md#exercicio-2) para exemplo relacionado com o regime de juro composto.

>Ver [Exercício 3](exercicios_2.md#exercicio-3) para exemplo relacionado com o regime de juro composto.



## Taxas nominais (a preços correntes) e reais (a preços constantes)

Pegando no último exemplo, a variação das taxas de juro e de atualização ao longo do tempo podem ter várias razões:

- alterações na política monetária;

- uma maior ou menor concorrência no setor bancário;

- alterações na taxa de variação geral dos preços de bens e serviços, designada **taxa de inflação**, com repercussão nas taxas praticadas.

__Análise a preços correntes e constantes__

- **Valor nominal = Valor a preços correntes**

    - É o valor do dinheiro tal como o conhecemos, por exemplo, uma nota de 20€ terá sempre o valor nominal de 20€.

- **Valor real = Valor a preços constantes**

    - É o valor do dinheiro ajustado de modo a considerar o efeito da **inflação**, por exemplo, um produto que custou 20€ em 2000 custaria 27€ a preços de 2015.

Suponha que lhe prometem 1.000€ para daqui a um ano, mas que os preços sobem durante esse ano, ou seja, **há inflação**. **Os 1.000€ daqui a 1 ano são 1.000€ a preços correntes do ano 1**.

Se a taxa de inflação anual for de 1,5%, o **valor real** desses 1.000€, i.e., o valor a preços constantes (preços de hoje, ano $0$) será igual a:

$$ \frac{1.000}{(1 + 0.015)} = \text{985,22€} $$

O valor obtido significa que um bem que custe hoje (ano $0$) $\text{985,22€}$ custa daqui a um ano (ano $1$): $985,22 × 1,015 = \text{1.000€}$

__Taxas de Juro: Nominal e Real__

- Taxa de juro **nominal $(r_n)$** - usa-se em avaliação de projetos a preços correntes, não é corrigida do efeito da **inflação** $(i)$.

-  Taxa de juro **real $(r_r)$** – usa-se em avaliação de projetos a preços constantes = Taxa nominal expurgada do efeito da __inflação__.

A **fórmula exata** para transformar taxas de juro ou de atualização nominais em reais é a seguinte:

$$ \small \text{1 + taxa nominal} = \text{(1 + taxa real)} \times \text{(1 + taxa inflação)} $$

$$  r_r = \frac{1 + r_n}{1 + i} - 1 \approx r_n - i $$


Exemplo: Se a taxa de juro **nominal $(r_n)$** = 2% e a taxa de inflação $(i)$ for de 1.5%, qual será a taxa de juro **real $(r_r)$**?

$$ \small \text{1 + 0,02} = \text{(1 + taxa real)} \times \text{(1 + 0,015)} $$

$$  r_r = \frac{1 + r_n}{1 + i} - 1 = \frac{1 + 0,02}{1 + 0,015} - 1 = 0,492\%$$

$$  r_r \approx r_n - i = 2\% - 1,5\% = 0,5\% $$


## Períodos inferiores a um ano: Taxas Anuais Nominais (TAN) e Anuais Efetivas (TAE)

Até aqui temos vindo a considerar sempre **períodos anuais** para os *cash flows* e para a taxa de atualização. Contudo, é também possível trabalhar com períodos infra-anuais, usando nesse caso na atualização dos fluxos financeiros infra-anuais uma **taxa** de juro **equivalente** à anual.

Considerando 1 ano dividido em $k$ subperíodos, a **equivalência de taxas** é dada pela seguinte igualdade:

$$ (1+r_k)^k = 1 + r_a $$

com:

- $r_a$, a taxa de juro anual;

- $k$, número de subperíodos no ano;

- $r_k$, taxa efetiva para o subperíodo $k$;

    - $k=12$ e taxa mensal $r_{12}$ ou $r_m$

    - $k=4$ e taxa trimestral $r_{4}$ ou $r_t$

    - $k=2$ e taxa semestral $r_{2}$ ou $r_s$

A **taxa $r_a$** é a chamada **taxa anual efetiva** (**TAE**) equivalente à taxa $r_k$.

>Ver [Exercício 4](exercicios_2.md#exercicio-4) para exemplo relacionado com o cálculo da taxa de juro anual $r_a$ equivalente.

Reportando ao [Exercício 4](exercicios_2.md#exercicio-4), $r_a = 12,55\%$ é a taxa anual efetiva (**TAE**) equivalente à taxa trimestral $r_{4}$ de $3\%$.  

No entanto, na **banca portuguesa** usa-se também a designação **nominal** noutro contexto, para significar que os juros de pagamentos ou recebimentos infra-anuais são calculados **proporcionalmente** à taxa anual nominal. Por exemplo, a **taxa mensal** correspondente à taxa anual nominal (**TAN**) de 12% é: $r_m = \frac{12\%}{12} = 1\%$.

>Ver [Exercício 5](exercicios_2.md#exercicio-5) para outro exemplo relacionado com os conceitos de Taxa Anual Nominal (**TAN**) e Taxa Anual Efetiva (**TAE**).


>Ver [Exercício 6](exercicios_2.md#exercicio-6) para consolidação dos conceitos anteriores.


## Anuidades e perpetuidades



## Sumário

!!! Summary "Sumário"
    Juros simples (os juros não acumulam ao capital)
    
    $$ \large C_n = rC_0​+C_0​=(1+r)C_0​ $$

    Juros Compostos - Capitalização: Valor no ano $n$ de um capital aplicado no ano $0$

    $$ \large C_n = C_0(1 + r)^n $$

    Atualização (ou desconto): Valor Atual (no ano $0$) de um capital gerado no ano $n$

    $$ \large VA = \frac{C_n}{(1 + r)^n} $$
