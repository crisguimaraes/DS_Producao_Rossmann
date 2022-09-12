# DS_Producao_Rossmann

## O Problema de negócio

O CFO da Rossmann, uma das maiores cadeias de drogarias da europa, pretende realizar uma reforma nas mais de 1000 unidades de farmácias que fazem parte do grupo.
Para financiar as obras, ele pretende destinar uma parcela da receita de cada uma das unidades.

Para ter mais acertividade e eficiência na alocação dos recursos financeiros, o CFO solicitou que fosse realizada uma previsão das vendas para as próximas 6 semanas, para dessa forma, determinar o orçamento destinado a cada uma das lojas.

## Estratégia para resolução do problema de negócio

De forma a ter uma primeira solução para esta demanda e entregar valor para o time de negócio de forma mais ágil, foi utilizado o método CRISP_DS (Cross Industry Standard Process for Data Science) de desenvolvimento.

O método CRISP é uma forma cíclica de solucionar o problema que permite ter uma visão ampla da solução, ajuda a organizar os pensamentos e códigos de forma simples e direta e a ter mais celeridade na entrega de valor. Através dessa metodologia, é seguido um pipeline de 10 passos em cada ciclo de desenvolvimento e, após entregar o primeiro lote de valor, você pode iterar novamente, encontrar novos insights, ajustar parâmetros, melhorar a precisão e fornecer mais valor. O ciclo pode ser repetido quantas vezes forem necessárias.

## O método CRISP_DS no desafio da Rossmann

### 1 - Questão de negócio

- Qual é o valor das vendas de cada loja nas próximas 6 semanas?

### 2 - Entendimento do negócio

- **Motivação**: 
a previsão de vendas foi requisitada pelo CFO da Rossmann em uma reunião mensal sobre os resultados das lojas que fazem parte do grupo.

- **Causa raiz do problema**: 
dificuldade em determinar o valor do investimento para a reforma de cada loja.

- **Dono do problema**: 
Diretor financeiro (CFO) da Rossmann

- **Formato da solução**:
Previsão de vendas para as próximas 6 semanas
Ferramentas: Jupyter Notebook, Python, séries temporais/regressão
Formato da entrega: valor total das vendas/loja nas próximas 6 semanas com possibilidade de acesso via web.
