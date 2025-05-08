# lendo_uma_pagina_html_wikipedia
O objetivo é ler uma pagina HTML no Wikipedia e transforma-lá em um DataFrame para análises posteriores


# 🌎 Análise de População de Países

Este projeto realiza uma análise dos dados de população dos países, extraídos diretamente da Wikipédia. Utilizamos técnicas de web scraping com Pandas para capturar, limpar e estruturar essas informações, permitindo uma visão clara da distribuição populacional global.

---

## 📌 **Objetivo**

O objetivo deste projeto é coletar, organizar e explorar os dados populacionais dos países, oferecendo uma base limpa e estruturada para futuras análises estatísticas e visualizações.

---

## 🛠️ **Tecnologias Utilizadas**

* Python 3.9+
* Pandas
* Google Colab

---

## 📥 **Coleta de Dados**

Os dados foram obtidos diretamente de uma página da Wikipédia contendo uma lista de países por população. Utilizamos o método `pd.read_html()` para extrair as tabelas HTML e convertê-las em DataFrames.

```python
import pandas as pd

# Coletando os dados a partir do arquivo HTML
dados_html = pd.read_html('/content/Lista de países por população – Wikipédia, a enciclopédia livre.html')
```

---

## 🗂️ **Estrutura do Projeto**

```
├── data
│   └── Lista de países por população – Wikipédia, a enciclopédia livre.html
│
├── notebooks
│   └── analise_populacao_paises.ipynb
│
├── README.md
└── requirements.txt
```

---

## 🔍 **Análises Realizadas**

1. **Seleção da Tabela Correta:** Identificação e extração da tabela com dados populacionais.
2. **Limpeza dos Dados:** Remoção de colunas desnecessárias, como `Unnamed: 0`.
3. **Organização:** Estruturação dos dados para futuras análises.

---

## 📊 **Próximos Passos**

* Análise Exploratória dos Dados (EDA):

  * Estatísticas descritivas
  * Visualização de distribuição populacional
  * Ranking de países mais populosos
* Tratamento de dados faltantes (caso existam) e padronização dos formatos.
* Geração de gráficos e dashboards interativos.

---

## 🚀 **Como Executar o Projeto**

1. Clone o repositório:

   ```bash
   git clone https://github.com/brodyandre/analise_populacao_paises.git
   ```
2. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```
3. Acesse o notebook e rode as células sequencialmente.

---

## 🤝 **Contribuições**

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.

---

## 📝 **Licença**

Este projeto está sob a licença MIT.

---

**Autor:** Luiz André
**LinkedIn:** [Meu Linkedin](https://www.linkedin.com/in/brodyandre)
**Última atualização:** 08 de Maio de 2025
""

