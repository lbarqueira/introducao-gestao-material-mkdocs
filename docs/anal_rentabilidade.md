# Análise da rentabilidade de projetos de investimento

## *Cash Flows*

**Representação de um projeto de investimento**

- Uma sequência de fluxos financeiros (_cash flows_) usualmente anuais, sendo o primeiro período o período _atual_, período $0$:

| **Período**   | **0** | **1** | **2** | **3** | **...** | **n** |
|---------------|-------|-------|-------|-------|---------|-------|
| _Cash flows_  | $CF_0$|$CF_1$ |$CF_2$ |$CF_3$ |...      |$CF_n$ |

- Estes _cash flows_, ditos totais, correspondem, por sua vez, a dois grandes grupos: **CFI** (_Cash flows_ de investimento) e **CFE** (_Cash flows_ de exploração)

### _Cash Flows_ de investimento (CFI)

Subdividem-se em:

&emsp;__a)__ Despesas de investimento em capital fixo (*Capital Expenditures*);

&emsp;__b)__ Investimento em fundo de maneio de exploração (*Change in Noncash Working Capital*);

&emsp;__c)__ Valor residual do investimento.

Assim:

**a) Despesas de investimento em capital fixo**

- correspondem ao primeiro ou primeiros cash flows e são **negativos**, uma vez que são saídas de dinheiro;

-  **despesas de investimento** em ativos fixos tangíveis (terrenos, edifícios, equipamentos) e intangíveis (software, licenças e patentes).

**b) Investimento em fundo de maneio de exploração**

- fundos necessários para constituição e reforço de inventário de matérias-primas ou mercadorias, ou para financiar os custos com os produtos vendidos a crédito num dado ano, deduzidos do montante obtido por crédito dos fornecedores;

- sendo saídas de dinheiro, os valores dos *cash flows* são **negativos**; 

- o investimento em fundo de maneio necessário de exploração pode ser calculado como a diferença entre as variações de ativos e passivos correntes, de curto prazo:

$$ \small \text{Inv.FME} = \Delta (\text{Inventário} + \text{Clientes} - \text{Fornecedores}) $$

**c) Valor Residual do Investimento**

- **No final do tempo de vida do projeto**, o valor das despesas de investimento em capital fixo que seja recuperável constitui um *cash flow* **positivo**, conhecido como *valor residual do investimento*;

- A venda no fim do seu tempo de vida de um dado ativo fixo origina geralmente **um ganho ou uma perda extraordinários (uma mais ou uma menos-valia)**.

- Se a **empresa for lucrativa** este valor vai ter impacto fiscal, pagando-se mais ou menos imposto.

- Assim, calcula-se o **VALOR RESIDUAL LÍQUIDO DE IMPOSTOS** ($VR$):

$$ \small VR =  \text{Valor Mercado}_n - (\text{Valor Mercado}_n - \text{Valor Contabilístico}_n) \times \text{Taxa Imposto} $$

&emsp; onde:

$$ \small \text{Valor Mercado}_n = \text{Valor esperado de venda do ativo no ano n} $$

$$ \small \text{Valor Contabilístico}_n = \text{Valor de compra} - \text{Amort./ Depreciações Acumuladas no ano n} $$

### _Cash Flows_ de exploração (CFE)

- Os Cash Flows durante a fase de exploração (passada a fase inicial de investimento) serão habitualmente positivos se o projeto for lucrativo.

$$ CFE = EBIT \times (1 - \text{tx.imposto}) + \text{Amortizações e Depreciações} $$

&emsp; Onde:

&emsp; &emsp; *EBIT* (*Earnings before interest and tax*) $=$ Resultados Antes de Juros e Impostos (RAJI) $=$ **Resultados Operacionais**

!!! Note 
    Considera-se aqui o **EBIT x (1 - tx.imposto) = resultado operacional líquido de impostos**, *em vez de* **EBT x (1 - tx.imposto) = Resultado Líquido do Período**,  para não deduzir os custos financeiros de financiamento que aparecem como taxa de juro na taxa de atualização dos cash flows. Isso é coerente com o facto de se considerar o montante total do investimento e não só a parte financiada por capitais próprios.

!!! Note 
    Quando temos um __*EBIT* negativo__, e vamos cálcular $EBIT \times (1-\text{tx.imposto})$ como procedemos? 
    
    **Exemplo**: $\text{tx.imposto} = 25\%$ e $\text{EBIT} = -30.000$€

    a) Tratando-se de uma **empresa, o pressuposto geral é que com resultado (EBIT) negativo não há imposto**, ou seja ele é zero $\implies$ $EBIT \times (1-\text{tx.imposto}) = -30.000$€.

    b) Se o **EBIT é negativo**, mas se trata de um projeto implementado por uma **empresa lucrativa** apesar do projeto, então para calcular o EBIT líquido e o seu *cash flow*, o imposto tem que ser calculado e neste caso ele é negativo. $EBIT \times (1-\text{tx.imposto}) = -22.500$€

    Ou seja, a empresa pagará menos impostos. Há obviamente um contributo positivo para o *cash flow* do projeto porque essa diferença corresponde a um benefício fiscal que contará assim positivamente no projeto.


>Ver [Exercício 1](exercicios_3.md#exercicio-1) para exemplo de cálculo do mapa de *cash flows* de um projeto.

## Taxa de atualização

Tendo por base o [Exercício 1](exercicios_3.md#exercicio-1) sabemos como calcular os *cash flows* de um projeto. 

No entanto, na **Avaliação de Projetos de Investimento** estamos confrontados com a necessidade de comparar Fluxos financeiros aplicados numa fase inicial (hip. ano $0$), com Fluxos gerados nos anos seguintes (anos $1, 2, 3 , 4, ...$).

A solução é **atualizá-los**, dividindo cada $CF_j$ (*cash flow* do período $j$) por $(1 + r)^{j}$, ou seja,  $\frac{CF_j}{(1 + r)^{j}}$, onde $r$ é a taxa de atualização.

>Ver [Exercício 2](exercicios_3.md#exercicio-2) para consolidação do conceito de avaliação de projetos e a taxa de atualização.

>Ver [Exercício 3](exercicios_3.md#exercicio-3) para *introdução da taxa de atualização* no [Exercício 1](exercicios_3.md#exercicio-1).

**Mas qual deverá ser a taxa de atualização $r$?**

- As taxas de atualização são em geral **nominais**, aplicadas a *cash flows* a preços correntes.

- Quando os *cash flows* são reais ou a preços constantes, utilizam-se taxas de atualização reais, calculadas de acordo com o que vimos anteriormente:

$$ \text{taxa real} = \frac {\text{1 + taxa nominal}}{\text{(1 + taxa inflação)}} - 1 $$

- A determinação das taxas de atualização deve ter em conta o risco associado ao investimento.

- As taxas de atualização exprimem o **custo de oportunidade do capital** ou seja, o rendimento que o investidor pretende tendo em conta o risco do investimento. **O investidor exige receber pelo menos a taxa que obteria em investimentos alternativos com o mesmo grau de risco**.



- A taxa de atualização de um projeto financiado **só com capital próprio** deve corresponder à **soma** de:

    - **rendimento esperado de activos sem risco** (rendimentos previsíveis a priori com precisão, como a remuneração dos títulos de dívida do Estado, geralmente mais elevada que a dos depósitos bancários)

    -  **com um prémio de risco** inerente à atividade económica em causa e ao risco financeiro associado ao grau de endividamento da empresa.

$$ \small \text{Taxa de atualização para um investimento financiado com capital prórpio} = \text{taxa de remuneração de um ativo sem risco} + \text{prémio de risco} $$

- Exemplo:

    - A taxa de juro sem risco (obrigações do tesouro) = $2\%$

    - Se o risco inerente a um projeto $x$ = $5\%$

    - Então a taxa de atualização deveria ser: $r = j_{sr} + P_r = 7\%$ 

    - $j_{sr} -$ taxa de juro sem risco (obrigações do tesouro)

    - $P_r -$ prémio de risco


- Quando, como é comum, houver financiamento **também com capital alheio**, dívida (p.ex, bancária ou obrigacionista), a taxa de atualização deve incorporar também a taxa de juro da dívida líquida de impostos, uma vez que as empresas podem deduzir aos resultados os juros pagos e com isso pagar menos impostos.

- Nesse caso (**de financiamento misto**), a taxa de atualização deve ser igual ao **custo médio ponderado do capital** ($\text{CMPC}$), sendo a ponderação dada pelas percentagens dos dois tipos de capital, calculadas **ao valor de mercado**:

$$ \text{Taxa de atualização com financiamento misto (Capital Próprio CP e Dívida D)} = $$

$$ \text{CMPC ou (WACC – Weighted Average Cost of Capital)} = $$

$$ = r_{CP} \times \%CP + r_{D} \times (1 - t) \times \% D $$

$$ \small = \text{taxa de remuneração do capital próprio} \times \%\text{capital próprio} + \text{taxa de juro dos empréstimos líquida de impostos} \times \%\text{capital alheio} $$

>Ver [Exercício 4](exercicios_3.md#exercicio-4) para exemplificação do cálculo da taxa de atualização.

>Ver [Exercício 5](exercicios_3.md#exercicio-5) para exemplificação e consolidação do cálculo da taxa de atualização.

>Ver [Exercício 6](exercicios_3.md#exercicio-6) para exemplificação e consolidação do cálculo da taxa de atualização.

## Critérios de análise da rentabilidade dos projetos

>Ver [Análise financeira para Ideias de Negócio | UAi Knowledge, 26.jul 2021](https://youtu.be/oOhgxLJlYrQ?t=4656) para vídeo explicativo sobre critérios de análise da rentabilidade dos projetos.

### O Valor Atual Líquido (*VAL*)

O cálculo do *VAL* consiste na soma de todos os *cash flows* $CF_{k}$ do projeto devidamente atualizados:

$$ \text{VAL(r)} = \sum _{k=0}^{n} \frac{CF_k}{(1 + r)^k} $$

onde:

- $k$, refere-se habitualmente a um ano, embora seja possivel outra periodicidade, desde que seja coincidente com a periocidade da taxa de atualização;

- o período inicial é $0$.

Baseados no $\text{VAL}$, podem-se enunciar **duas regras de decisão**:

- **Caso de um único projeto**: Se $\text{VAL}(r)>0$ $=>$ **Projeto Rentável** à taxa de atualização $r$ (ou seja, há um acréscimo de valor para a empresa face ao custo dos recursos financeiros envolvidos);

- **Caso de dois ou mais projetos**: Entre dois projetos $A$ e $B$, se $\text{VAL}_A > \text{VAL}_B$, **Projecto $A$ é preferível a Projecto $B$**.

>Ver [Exercício 7](exercicios_3.md#exercicio-7) para exemplificação do cálculo do $VAL$.

### A Taxa Interna de Rentabilidade (*TIR*)

Calculado a par do $\text{VAL}$, é outro indicador de rentabilidade. Corresponde à taxa de atualização $r$ para a qual o $\text{VAL}$ é zero.

$$ \text{VAL(r)} = \sum _{k=0}^{n} \frac{CF_k}{(1 + r)^k} = 0 $$

$$ r = TIR $$

- Calcula-se iterativamente;

- **Aceitar um projeto com $\text{VAL}(r)>0$, dada a taxa de atualização $r$, é equivalente a aceitá-lo quando $TIR>r$**

**Problemas no cálculo e na utilização da TIR**

- Pode existir **mais do que uma TIR**. É o caso, por exemplo, da existência de *cash flows* negativos intermédios ou finais (investimentos não convencionais), causados, nomeadamente, por necessidades de reinvestimento ao longo do projeto;

- **Pode não existir TIR**;

- **A TIR é inadequada para projetos mutuamente exclusivos** (i.e., em que só podemos fazer um deles, quer por limitações de recursos financeiros quer por limitações fisicas). Nesse caso, a seleção de projetos com base na **TIR**, é uma escolha muitas vezes errónea.
> Ver o [Exercício 8](exercicios_3.md#exercicio-8) que ilustra esta última situação, ou seja, que a TIR é inadequada para comparar projetos mutuamente exclusivos.


### Período de Recuperação do Investimento (*PRI*, ou *Payback Period*)

Tempo necessário para que os *cash flows* atualizados gerados pelo projeto igualem (recuperem) o capital investido inicialmente. Mede portanto a rapidez de recuperação do capital inicial investido.

$$ \sum _{k=0}^{PB} \frac{CF_k}{(1 + r)^k} = 0 $$

onde:

- $CF_k =$ *cash flow* do período $k$;

- $PB =$ múmero de períodos do *Payback*;

- $r =$ taxa de atualização.

**Outra fórmula**:

$$ \text{PRI} = \text{Ano anterior à mudança de sinal no } CF_{acumulado} - \frac{\text{último } CF_{acumulado \; negativo}}{CF_{atualizado \; no \; primeiro \; acumulado \; positivo}} $$


>Ver [Exercício 9](exercicios_3.md#exercicio-9) para exemplificação do cálculo do $PRI$, ou *Payback Period*.

Se os *cash flows* acumulados nunca passarem a positivos o projeto não é rentável, sendo o *PRI* superior à vida útil do investimento.

### Índice de Rendibilidade (*IR*)

$$ \text{IR} = \frac{\text{VAL} + \text{Investimento Inicial} }{\text{Investimento Inicial}} = \frac{\text{VA}}{\text{Investimento Inicial} } $$

Um projeto considera-se aceitável (viável) quando $\text{IR}> 1$

Trata-se de medir o valor atual ($\text{VA}$) gerado por unidade monetária investida.

Tal como acontece com a $\text{TIR}$, o $\text{IR}$ é inadequado para comparar projetos mutuamente exclusivos (i.e, em que só podemos fazer um deles).

>Ver [Exercício 10](exercicios_3.md#exercicio-10) para exemplificação do cálculo do $IR$, e o problema idêntico ao $TIR$ com investimentos mutuamente exclusivos.