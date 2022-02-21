<!--- https://www.markdownguide.org/basic-syntax/
-->
# Repositório da monografia "Energia Fóssil e Energia Limpa: Um estudo a partir da Teoria das Opções Reais"

# :building_construction: **EM CONSTRUÇÃO**

<!---
    Adicionar imagens dos quatro tipos de usinas em questão
-->

## Contexto e a TOR

A monografia se propõe a estudar a viabilidade de usinas elétricas movidas por combustíveis fósseis e por fontes renováveis. Considerando combustíveis fósseis são abordadas usinas movidas por carvão mineral e gás natural. Por parte das fontes renováveis, considera-se usinas eólicas on-shore e usinas solares fotovoltaicas.

As motivações por trás desse estudo são diversas. A mudança climática tendo sido cada vez mais levada em consideração na tomada de decisão de investimentos públicos e privados, de modo que os efeitos ambientais passam a ser incorporados com maior importância durante a avaliação de projetos. 

Outro ponto relevante é a volatilidade dos preços dos combustíveis, isto é, a variação sob a qual a produção de energia elétrica está sujeita quando utiliza-se combustíveis fósseis nessa atividade. Ainda que no Brasil cerca de 65% da produção de energia elétrica seja proveniente de usinas hidrelétricas, momentos de pouca chuva diminuem a produção em usinas desse tipo e obrigam a operação de usinas movidas por combustíveis fósseis.

A volatilidade dos preços é importante para a avaliação do projeto da construção e operação de uma usina. Em períodos de preços baixos, o projeto pode ser viável; enquanto sob preços mais altos, esse pode não ser o caso. Para incluir a incerteza na avaliação do projeto, utiliza-se aqui a Teoria das Opções Reais (TOR).

A ideia da TOR é similar ao modelo de precificação Black-Scholes de ativos financeiros, no entanto na TOR consideramos ativos físicos como uma usina de energia elétrica. De forma breve, essa teoria utiliza diversos parâmetros relacionados ao projeto como investimento inicial, custos de operação e preço da produto (energia elétrica) para avaliar a viabilidade de um projeto a partir de uma relação preço-custo. 

Um exemplo dessa relação seria o preço da energia elétrica e os custos de operação de uma usina termoelétrica movida a gás natural. A todo tempo, essa relação varia devido a mudanças nos preços da energia e do gás. Um modelo que utiliza a Teoria das Opções Reais incorpora essas variações na avaliação do investimento e indica um valor mínimo dessa relação para que o investimento seja viável.

A monografia integral está disponível no repositório.

### Conteúdo do repositório

* <u>[*Monografia*](https://github.com/Garaujott/monografia_USP_opcoes_reais_energia/blob/main/Monografia_20211129_16h39.pdf)</u> - arquivo integral da monografia

* <u>[*Estimação dos Parâmetros*](https://github.com/Garaujott/monografia_USP_opcoes_reais_energia/blob/main/estimacao_parametros-final.ipynb)</u>  - Jupyter Notebook com a estimação dos parâmetros utilizados na definição e solução do sistema de equações diferenciais.

* <u>[*Solução EDO e simulações*](https://github.com/Garaujott/monografia_USP_opcoes_reais_energia/blob/main/opcoes_reais_monografia-final.ipynb)</u>  - Jupyter Notebook com a solução dos sistemas de EDO para cada uma das fontes consideradas, as simulações variando os parâmetros e a geração de gráficos resultantes das simulações.

## Estimação dos parâmetros
<!---
breve descrição do conteúdo

falar sobre os passos realizados no notebook
--->

## Solução do sistema, simulações e gráficos
<!---
breve descrição do conteúdo

falar sobre os passos realizados no notebook
--->

## Referências e Fontes de Dados

Para todas as estimações, o período considerado foi de 2012 a 2019. Como fontes de dados, temos:

- Previsão SELIC e IGP-M 2024 pelo Boletim FOCUS do Banco Central da semana do dia 22/11/2021: <u>[Boletim Focus 22/11/2021](https://www.bcb.gov.br/content/focus/focus/R20211119.pdf)</u>

- Dólar Mensal: <u>[Dólar Comercial](https://www.investing.com/currencies/usd-brl)</u>

- Preço da Energia Elétrica(1): <u>[Tarifa Média de Fornecimento](https://portalrelatorios.aneel.gov.br/mercado/cativo)</u>; <u>[Arquivo .xlsx](https://sistemas.aneel.gov.br/concessionarios/administracao/samp/RelSampRegCC.xlsx) </u>

- Gás Natural: <u>[Henry Hub Natural Gas Spot Price](https://www.eia.gov/dnav/ng/hist/rngwhhdM.htm)</u>; <u>[Henry Hub Natural Gas Spot Price - Base Mensal](https://www.eia.gov/dnav/ng/hist_xls/RNGWHHDm.xls)</u>

- Carvão Mensal: <u>[Newcastle Coal Futures](https://www.investing.com/commodities/newcastle-coal-futures)</u>

- Custos ligados às usinas elétricas: <u>[PNE 2050](https://www.epe.gov.br/sites-pt/publicacoes-dados-abertos/publicacoes/PublicacoesArquivos/publicacao-227/topico-563/Relatorio%20Final%20do%20PNE%202050.pdf)</u>; <u>[Nota Técnica PR 007-2018](https://www.epe.gov.br/sites-pt/publicacoes-dados-abertos/publicacoes/PublicacoesArquivos/publicacao-227/topico-456/NT%20PR%20007-2018%20Premissas%20e%20Custos%20Oferta%20de%20Energia%20El%C3%A9trica.pdf)</u>

Obs: (1) Os dados de energia elétrica utilizados sofreram alterações no Excel antes de serem importados no notebook. Basicamente consolidou-se os valores mensais considerando todos as classes de consumo e todas as regiões do país, resultando na <u>[planilha presente no repositório.](https://github.com/Garaujott/monografia_USP_opcoes_reais_energia/blob/main/dados/RelSampRegCC.xlsx)</u>



<!---
Obs: A ANEEL mudou a forma como disponibilizava os dados entre a submissão da monografia e a elaboração dessa documentação, de modo que os dados utilizados na monografia não estão mais disponíveis. Porém, é possível obter dados equivalentes no link disponibilizado acima.

Dolár; boletim Focus; Carvão; Gás Natural; Nota Técnica; ANEEL

--->
