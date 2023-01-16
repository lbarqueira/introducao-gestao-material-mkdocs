# Introdução ao cálculo financeiro


## Investimento e despesa corrente

__Investimento__: é a aplicação de recursos limitados feita com vista a obter retorno(s) no futuro, por contrapartida a despesa corrente que se confina ao momento em que ocorre.

Na análise de um projeto de investimento procura-se avaliar se a afetação de recursos ($\text{R}$), feita inicialmente, é capaz de vir a gerar uma sucessão de benefícios líquidos ($\text{B}$) que excedem esse investimento inicial.

$$ -\text{ R}-\text{R}-\text{R}+\text{B}+\text{B}+\text{B } ... +\text{ B} $$

Para essa avaliação põe-se a questão de saber como obter esses recursos, ou seja, como financiar o projecto, através de capital próprio ou alheio, e de saber como prever os benefícios e custos futuros.


## O valor temporal do dinheiro

Concentrando-nos num domínio puramente financeiro, os recursos ($\text{R}$) e os benefícios ($\text{B}$) representam dinheiro, fluxos financeiros negativos ou positivos, designados em inglês por _cash flows_ (negativos, representados por $\text{CF}-$, ou $\text{C}-$; positivos representados por $\text{CF}+$, ou $\text{C}+$).

Idealmente, estaremos interessados em investir em projetos em que a soma dos $\text{CF}-$ seja inferior à soma dos $\text{CF}+$. O problema é que esta análise é dependente do tempo e, com o tempo, o dinheiro está sujeito a determinados fatores como, por exemplo, a inflação e os juros. Ora, para saber como lidar com juros e somar ou comparar fluxos financeiros em diferentes momentos de tempo temos que atender a alguns principios do _Cálculo Financeiro_.

## Capitalização e atualização. Juros simples e compostos

**Suponha que tem 1.000€ hoje, no ano $0$, e pretende depositá-los no banco. O que vai acontecer?**

Ao depositar os 1.000€ no banco, estes ficam a render a uma dada **taxa de juro anual**.

Ao fim de 1 ano, há duas hipóteses:

- **Levantar o juro** ficando apenas o capital inicial $\rightarrow$ deixar nessa conta só o montante inicial, levantando os juros todos os anos (**regime juros simples** - os juros não acumulam ao capital);

- **Acumular o juro** ao capital $\rightarrow$ depositá-los numa conta a prazo em que os juros vencidos ficam a acumular nessa conta gerando mais juros (**regime juros compostos** - esquema de capitalização).

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

>Ver [Exercício 4](exercicios_2.md#exercicio-4) para exemplo de cálculo da taxa de juro **real $(r_r)$**, uma vez dada a taxa de juro **nominal $(r_n)$**.

>Ver [Exercício 5](exercicios_2.md#exercicio-5) para exemplo de cálculo da taxa de juro **nominal $(r_n)$**, uma vez dada a taxa de juro **real $(r_r)$**.


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

>Ver [Exercício 6](exercicios_2.md#exercicio-6) para exemplo relacionado com o cálculo da taxa de juro anual $r_a$ equivalente.

Reportando ao [Exercício 6](exercicios_2.md#exercicio-6), $r_a = 12,55\%$ é a taxa anual efetiva (**TAE**) equivalente à taxa trimestral $r_{4}$ de $3\%$.  

No entanto, na **banca portuguesa** utiliza-se também a designação **nominal** noutro contexto, para significar que os juros de pagamentos ou recebimentos infra-anuais são calculados **proporcionalmente** à taxa anual nominal. Por exemplo, a **taxa mensal** correspondente à taxa anual nominal (**TAN**) de 12% é: $r_m = \frac{12\%}{12} = 1\%$.

>Ver [Exercício 7](exercicios_2.md#exercicio-7) para outro exemplo relacionado com os conceitos de Taxa Anual Nominal (**TAN**) e Taxa Anual Efetiva (**TAE**).


>Ver [Exercício 8](exercicios_2.md#exercicio-8) para consolidação dos conceitos anteriores. NOTA: POR EFETUAR.


## Anuidades e perpetuidades

**Numa situação em que se concede / obtém um _empréstimo_ num período** e temos Rendas (+) ou Pagamentos (-) em prestações constantes a iniciar no período seguinte, temos uma chamada **Anuidade**, durante **$n$ períodos** ($n$ é o número de anos, trimestres, meses,...) com **taxa de atualização $r$** ($r$ pode ser taxa de atualização anual, trimestral, mensal,...).

<figure markdown>
  <img src="../images/tabela_37.png" width="600">
  <figcaption>Representação genérica de uma anuidade </figcaption>
</figure>

A última linha da tabela representa corretamente os _cash flows_ $A$ **devidamente atualizados a uma taxa de atualização** $r$, uma vez que não podemos ignorar o fator tempo.

__Como se atualizam as rendas ou pagamentos?__

$$ \text{Valor Atual (VA)} = \sum_{t=1..n} \frac{A_t}{(1 + r)^t} $$

Trata-se de uma série em progressão geométrica com razão $\frac{1}{1 + r}$ que pode ser escrita como:

$$ VA = A \frac{(1 + r)^n - 1}{(1 + r)^n \times r} = A f(r,n) $$

em que $f(r,n)$ é o fator de anuidade. É a fórmula do _Valor Atual de uma anuidade (sem crescimento)_.

Quando $n = \infty$ estamos perante o _Valor Atual da perpetuidade (sem crescimento)_:

$$ VA = A \times f(r,\infty) = A \times \frac{1}{r} $$

!!! Note 
    É este **Valor Atual** ($VA$) assim encontrado que deverá ser igual ao preço $P$ do nosso bem (vêr tabela anterior), ou ao valor do empréstimo contraído.


**Caso haja antecipação dos pagamentos ou o seu adiamento**

As fórmulas terão de ser **modificadas**:

- caso haja **antecipação de 1 período**: multiplicar por $\frac{1}{(1 + r)}$;

- caso haja **diferimento/adiamento de 1 período**: multiplicar por $(1 + r)$;

- caso haja **diferimento/adiamento de $n$ períodos**: multiplicar por $(1 + r)^n$;


**Caso de rendas crescentes**

Os casos anteriores excluem os casos de **rendas crescentes**. Tendo em conta rendas crescentes a uma taxa de crescimento constante $g < r$, ou seja, sucessivamente $A$, $A(1+g)$, $A(1+g)²$,..., as fórmulas da **anuidade** e da **perpetuidade** serão respetivamente:

- Valor Atual da Anuidade com crescimento $g$:

$$ VA = A \times \left(\frac{1}{r - g} - \frac{(1 + g)^n}{(1 + r)^n (r - g)} \right) $$

- Valor Atual da Perpetuidade com crescimento $g$:

$$ VA = A \times \frac{1}{r - g} $$

>Ver [Exercício 9](exercicios_2.md#exercicio-9) para exemplificação dos conceitos anteriores. 

>Ver [Exercício 10](exercicios_2.md#exercicio-10) para exemplificação dos conceitos anteriores.

>Ver [Exercício 11](exercicios_2.md#exercicio-11) para exemplificação dos conceitos anteriores. 

>Ver [Exercício 12](exercicios_2.md#exercicio-12) para exemplificação dos conceitos anteriores. 