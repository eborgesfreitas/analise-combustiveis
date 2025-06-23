# ⛽ Análise da Evolução dos Combustíveis no Brasil (2004–2021)

![Badge](https://img.shields.io/badge/Python-Data--Analysis-blue)  
![Badge](https://img.shields.io/badge/Status-Em%20Andamento-yellow)

Este projeto realiza uma análise exploratória da evolução dos preços dos principais combustíveis no Brasil — **Gasolina Comum, Etanol Hidratado e Diesel S10** — com base nos dados públicos disponibilizados pela **Agência Nacional do Petróleo, Gás Natural e Biocombustíveis (ANP)**.  

O objetivo é compreender como esses preços se comportaram ao longo dos anos, avaliar a volatilidade dos combustíveis e identificar diferenças regionais entre os estados brasileiros.

## 🔗 Artigo no Medium
➡️ Leia a análise completa e detalhada no artigo:  
[**📄 Como evoluem os preços dos combustíveis no Brasil? (2004 a 2021)**](https://medium.com/@eborgesfreitas/como-evoluem-os-pre%C3%A7os-dos-combust%C3%ADveis-no-brasil-uma-an%C3%A1lise-de-2004-a-2021-0cb4a55e933f)  

---

## 🗺️ **Principais Análises Realizadas**
- ✅ Evolução dos preços médios da Gasolina, Etanol e Diesel de 2004 a 2021.
- ✅ Comparação de preços entre os estados brasileiros.
- ✅ Análise de volatilidade dos combustíveis usando Coeficiente de Variação (CV%).
- ✅ Diferença de preços absolutos e relativos entre os tipos de combustíveis.

---

## ⚙️ **Tecnologias e Ferramentas Utilizadas**
- 📊 Python
- 🐼 Pandas
- 📈 Seaborn
- 📊 Plotly
- 🌍 Folium (mapas)
- 📉 Matplotlib
- 🧠 Jupyter Notebook

---

## 📂 **Estrutura do Projeto**
```plaintext
├── data/                     # Dados brutos e tratados utilizados na análise
│   ├── raw/ 2004-2021.tsv
│   └── processed/ dados_tratados.csv
├── notebooks/                 # Notebooks separados por tema
│   ├── 00_tratamento_dados.ipynb
│   ├── 01_analise_exploratoria.ipynb
│   └── 02_comparacoes_combustiveis.ipynb
├── images/                    # Gráficos e imagens geradas
├── requirements.txt           # Dependências do projeto
└── README.md                  # Este arquivo
```

## 📦 Como Executar

1. Clone este repositório:

```bash
git clone https://github.com/eborgesfreitas/analise-combustiveis.git
```

2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Execute os notebooks no Jupyter ou Google Colab para explorar a análise.

## 📊 Dashboard

*EM BREVE:* Um Dashboard interativo no Power BI para visualização dos principais insights.

## 📝 Licença

Este projeto está licenciado sob a licença MIT — veja o arquivo LICENSE para mais detalhes.

---

Feito com 💙 por Eduardo Borges Freitas

[🔗 LinkedIn](https://www.linkedin.com/in/eborgesfreitas/)

[🔗 Medium](https://medium.com/@eborgesfreitas)

[🔗 GitHub](https://github.com/eborgesfreitas)
