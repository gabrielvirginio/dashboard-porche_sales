# 🏎️ Dashboard de Vendas Porsche — Análise de Dados

## 📊 Sobre o Projeto

Este projeto consiste no desenvolvimento de um **Dashboard Interativo de Vendas Porsche**, voltado à análise exploratória de dados, identificação de padrões comerciais e visualização de indicadores relevantes para a compreensão dos registros de vendas.

A solução permite explorar os dados por meio de filtros interativos, indicadores-chave de desempenho (KPIs), gráficos analíticos e rankings, proporcionando uma visão segmentada das ocorrências por modelo, ano-modelo, cidade, forma de pagamento e período da venda.

O dashboard foi desenvolvido em HTML, permitindo a execução local no navegador e a interação com os dados sem depender de serviços externos de visualização.

## 🎯 Objetivos

- Analisar a distribuição dos registros por modelo Porsche.
- Identificar os anos-modelo com maior frequência na base.
- Investigar a distribuição geográfica dos registros por cidade.
- Avaliar a participação das diferentes formas de pagamento.
- Identificar modelos recorrentes e possíveis empates nos rankings.
- Explorar variações temporais conforme o período de venda selecionado.
- Disponibilizar indicadores e visualizações dinâmicas para facilitar a interpretação dos dados.

## 🔎 Filtros Interativos

O dashboard disponibiliza filtros que permitem segmentar a análise de acordo com os seguintes critérios:

- **Modelo Porsche:** seleção dos modelos presentes na base de dados.
- **Model Year:** filtragem pelo ano-modelo do veículo.
- **City:** seleção da cidade associada ao registro.
- **Pay Method:** segmentação por forma de pagamento.
- **Período da venda:** seleção do intervalo temporal utilizado na análise.

A combinação dos filtros permite investigar diferentes segmentos e observar como os indicadores e gráficos se comportam diante dos critérios selecionados.

## 📈 Indicadores e Visualizações

### KPIs — Indicadores-chave de desempenho

- **Quantidade de registros:** total de registros considerados conforme os filtros aplicados.
- **Variedade de modelos:** quantidade de modelos distintos identificados na base filtrada.
- **Cidade líder:** cidade com maior quantidade de registros no recorte analisado.
- **Ano-modelo mais frequente:** ano-modelo com maior número de ocorrências.

### Gráficos e rankings analíticos

- **Ranking dos modelos:** classificação dos modelos Porsche conforme a frequência de registros.
- **Distribuição por ano-modelo:** comparação do volume de registros entre os anos-modelo.
- **Volume por cidade:** identificação das cidades com maior concentração de registros.
- **Formas de pagamento:** distribuição dos registros conforme o método de pagamento informado.

Os indicadores e as visualizações permitem comparar os segmentos selecionados e identificar concentrações, diferenças e padrões observáveis na base de dados.

## 💡 Insights e Análises

O dashboard permite investigar diferentes aspectos da distribuição dos registros:

- **Modelos mais recorrentes:** identificação dos modelos com maior frequência na planilha.
- **Preferências por cidade:** comparação da distribuição dos modelos e registros entre as cidades, conforme os filtros disponíveis.
- **Empates nos rankings:** identificação de situações em que dois ou mais modelos, cidades ou anos-modelo apresentam a mesma quantidade de registros.
- **Distribuição por ano-modelo:** análise da concentração de ocorrências entre diferentes gerações de veículos.
- **Formas de pagamento:** comparação da frequência dos métodos de pagamento registrados.
- **Destaque temporal:** identificação dos períodos com maior concentração de registros válidos, conforme o intervalo de venda selecionado.

Os resultados devem ser interpretados considerando o escopo e as limitações da base. A frequência de registros permite identificar recorrências, mas não comprova, isoladamente, preferência de mercado, volume efetivo de unidades entregues ou desempenho financeiro.

## 🧹 Qualidade dos Dados e Critérios Metodológicos

A análise utiliza os registros disponíveis na planilha como fonte de informação e respeita os critérios de contagem definidos para o dashboard.

### Tratamento das datas

A base apresenta **24 registros sem data de venda válida**.

Para preservar a visão geral dos dados:

- Os 24 registros permanecem incluídos na visão geral, quando aplicável.
- Quando um filtro de período de venda é aplicado, os registros sem data válida são excluídos, pois não é possível determinar se pertencem ao intervalo selecionado.
- Consequentemente, o total de registros pode variar entre a visão geral e as análises temporais filtradas.

### Critérios de contagem

- As contagens são baseadas nos registros existentes na planilha.
- A variedade de modelos corresponde à quantidade de modelos distintos identificados no recorte analisado.
- Os rankings são construídos com base na frequência dos registros.
- Empates devem ser interpretados como igualdade na quantidade de ocorrências, e não como diferenças de desempenho.
