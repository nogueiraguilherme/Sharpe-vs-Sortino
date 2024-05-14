# Sharpe-vs-Sortino
## Estudo de caso em Bitcoin

Sharpe e Sortino são métricas para estudo e análise de risco em investimentos.

Ao investir buscamos retorno, mas precisamos observar além disso, precisamos também observar o risco, ou seja, avaliar o retorno ajustado ao risco. Um ativo com alto retorno pode ser um ativo com alto risco, trazendo volatilidade para nossa carteira.

Precisamos entender os momentos de usar cada um deles.

$\textbf{Sharpe ratio} = \frac{R{p}-R{f}}{{\sigma {p}}}$<br>
Onde:<br>
$R{p}$ = retorno do portfolio (ou ativo)<br>
$R{f}$ = taxa livre de risco<br>
$\sigma {p}$ = desvio padrão dos retornos<br>

$\textbf{Sortino ratio} = \frac{R{p}-R{f}}{{\sigma {p}}}$<br>
Onde:<br>
$R{p}$ = retorno do portfolio (ou ativo)<br>
$R{f}$ = taxa livre de risco<br>
$\sigma {p}$ = desvio padrão **negativo** dos retornos<br>

O Índice Sharpe é mais sensível à volatilidade por considerar tanto a volatilidade positiva quanto a negatica, por conta disso, em momentos de alta (bull market) é mais interessante usar o Índice Sortino, que representará melhor nosso portfólio de investimentos.

Você pode acessar o código comentado [aqui](https://github.com/nogueiraguilherme/Sharpe-vs-Sortino/blob/main/Sharpe_vs_Sortino_Bitcoin.ipynb).
