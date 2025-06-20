# Dados do Projeto

Este diretório contém os dados utilizados no projeto de análise dos preços dos combustíveis no Brasil.

---

## Sobre os Dados

Os dados foram obtidos do Kaggle no dataset:

[Gas Prices in Brazil - Kaggle](https://www.kaggle.com/datasets/matheusfreitag/gas-prices-in-brazil)

O arquivo principal é um arquivo `.tsv` com registros dos preços de combustíveis em diversos estados brasileiros, abrangendo o período de 2004 até 2021.

---

## Como Baixar os Dados

1. Crie uma conta no [Kaggle](https://www.kaggle.com/) caso ainda não possua.

2. Acesse o dataset no link acima.

3. Faça o download manual do arquivo `gas_prices_brazil.tsv` (ou arquivo(s) que preferir).

4. Coloque o arquivo baixado na pasta `data/` deste projeto.

---

## Estrutura dos Dados

| Coluna                        | Descrição                                       |
|-------------------------------|-------------------------------------------------|
| DATA INICIAL                  | Data inicial do período da observação           |
| DATA FINAL                    | Data final do período da observação             |
| REGIÃO                        | Região do Brasil                                |
| ESTADO                        | Estado brasileiro                               |
| PRODUTO                       | Tipo de combustível                             |
| NÚMERO DE POSTOS PESQUISADOS  | Quantidade de postos pesquisados                |
| UNIDADE DE MEDIDA             | Unidade de medida dos preços (ex: R$/litro)     |
| PREÇO MÉDIO REVENDA           | Preço médio na revenda                          |
| DESVIO PADRÃO REVENDA         | Desvio padrão dos preços na revenda             |
| PREÇO MÍNIMO REVENDA          | Preço mínimo na revenda                         |
| PREÇO MÁXIMO REVENDA          | Preço máximo na revenda                         |
| MARGEM MÉDIA REVENDA          | Margem média na revenda                         |
| COEF DE VARIAÇÃO REVENDA      | Coeficiente de variação na revenda              |
| PREÇO MÉDIO DISTRIBUIÇÃO      | Preço médio na distribuição                     |
| DESVIO PADRÃO DISTRIBUIÇÃO    | Desvio padrão dos preços na distribuição        |
| PREÇO MÍNIMO DISTRIBUIÇÃO     | Preço mínimo na distribuição                    |
| PREÇO MÁXIMO DISTRIBUIÇÃO     | Preço máximo na distribuição                    |
| COEF DE VARIAÇÃO DISTRIBUIÇÃO | Coeficiente de variação na distribuição         |

---

## Observações

- Os dados são atualizados até 2021.

- Para análises mais recentes, verifique atualizações no Kaggle.

- Caso deseje automatizar o download, você pode usar a [Kaggle API](https://www.kaggle.com/docs/api), que exige configuração do token.

---

## Notebooks

Os notebooks para análise inicial estão na pasta `notebooks/`.

