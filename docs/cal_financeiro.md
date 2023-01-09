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

$$ VA = \frac{1.100€}{(1 + 0.1)^1} = 1.000€ $$

O $VA$ de 1.210€ a receber ao fim de 2 anos é também igual a:

$$ VA = \frac{1.210€}{(1 + 0.1)^2} = 1.000€ $$

Notar que estas fórmulas pressupõem que a taxa de juro usada como taxa de atualização se mantém ao longo do tempo.

__Capitalização versus Atualização__

<figure markdown>
  <img src="../images/tabela_35.png" width="600">
  <figcaption>Capitalização versus Atualização</figcaption>
</figure>

>Ver [Exercício 1](exercicios_2.md#exercício-1) para exemplo de cálculo de juros em regime de juro simples.

>Ver [Exercício 2](exercicios_2.md#exercício-2) para exemplo relacionado com o regime de juro composto.

>Ver [Exercício 3](exercicios_2.md#exercício-3) para exemplo relacionado com o regime de juro composto.

## Taxas nominais (a preços correntes) e reais (a preços constantes)



## Taxa Anual Efetiva (TAE) e Taxa Anual Nominal (TAN)



## Anuidades e perpetuidades



