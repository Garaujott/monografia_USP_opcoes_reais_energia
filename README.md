<!--- https://www.markdownguide.org/basic-syntax/
-->
# Repositório da monografia "Energia Fóssil e Energia Limpa: Um estudo a partir da Teoria das Opções Reais"

# :building_construction: **EM CONSTRUÇÃO**

## Introdução

<!---
**falar sobre o contexto da monografia**

**falar sobre a Teoria das Opções Reais (TOR)**
--->

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
