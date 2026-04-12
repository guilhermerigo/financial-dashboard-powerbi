***WEG (WEGE3) - Análise de Crédito e Stress Testing***
Este projeto apresenta uma análise de crédito da WEG S.A. com base em dados financeiros públicos. Foram utilizados Balanço 4T2025, DRE e Fluxo de Caixa ano 2025 obtidos no RI da WEG.

**Objetivo**
Avaliar o risco de crédito da empresa e sua sensibilidade a cenários de stress. Este projeto foi desenvolvido como um aperfeiçoamento pessoal, 
visando consolidar conhecimentos em análise fundamentalista, Power BI e linguagem DAX.

**Indicadores analisados**
- Liquidez corrente
- Cobertura de juros
- Dívida líquida / EBIT
- Índice de inadimplência

**Modelo de Score**
Foi desenvolvido um score de crédito baseado em indicadores ponderados, classificando o risco em níveis de A a D. Os indicadores utilizados foram:

- Endividamento
- Liquidez
- Capacidade de pagamento (juros)
- Geração de caixa

Com diferentes pesos, dado:

Score=
([Nota Divida]*0.3) + ([Nota Liquidez]*0.25) + ([Nota Juros]*0.25) + ([Nota Caixa]*0.2)


**Stress Testing**
Simulação de queda de 5% - 50% da receita:

- Score: 87 → 68,5
- Rating: A → B

Ferramentas:
- Power BI
- DAX
- Excel

Observação:
O índice de inadimplência foi estimado utilizando provisão sobre contas a receber.


Use esse link para entrar no Dashboard feito pelo Lovable (ainda em fase de testes): https://weg-guilherme-test.lovable.app
