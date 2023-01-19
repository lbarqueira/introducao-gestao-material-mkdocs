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

&emsp;__c)__ Valor residual do investimento

Desenvolvendo:

**a) Despesas de investimento em capital fixo**

- correspondem ao primeiro ou primeiros cash flows e são **negativos**, uma vez que são saídas de dinheiro;

-  **despesas de investimento** em ativos fixos tangíveis (terrenos, edifícios, equipamentos) e intangíveis (software, licenças e patentes).

**b) Investimento em fundo de maneio de exploração**

- fundos necessários para constituição e reforço de inventário de matérias-primas ou mercadorias, ou para financiar os custos com os produtos vendidos a crédito num dado ano, deduzidos do montante obtido por crédito dos fornecedores;

- sendo saídas de dinheiro, os valores dos *cash flows* são **negativos**; 

- o investimento em fundo de maneio necessário de exploração pode ser calculado como a diferença entre as variações de ativos e passivos correntes, de curto prazo:

$$ \text{Inv.FME} = \Delta (\text{Inventário} + \text{Clientes} - \text{Fornecedores}) $$

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

TODO: 
>Ver [Exercício 3](exercicios_3.md#exercicio-3) para introdução da taxa de atualização no [Exercício 1](exercicios_3.md#exercicio-1).

**Qual deverá ser a taxa de atualização $r$?**

Os *cash flows* estão expressos em termos nominais, a preços correntes, ou reais, a preços constantes.

Se estiverem a preços correntes, a taxa de atualização $r$ ........