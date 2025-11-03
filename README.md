# 🪐 Projeto Meteora — Análise de Vendas e Insights

Este projeto tem como objetivo realizar uma **análise exploratória dos dados da loja Meteora**, que vende roupas e acessórios em todo o Brasil.  
O estudo utiliza dados reais (via CSV hospedados no GitHub da Alura) para compreender padrões de vendas, desempenho de vendedores, produtos mais vendidos e oportunidades de negócio.

---

## 📊 Objetivo do Projeto

A loja **Meteora** deseja compreender melhor seus dados de vendas e operações para:

- Identificar os produtos e marcas mais vendidos.
- Analisar o desempenho dos vendedores por período.
- Compreender o comportamento de vendas por estado.
- Gerar insights estratégicos para ações sazonais, como campanhas de Natal.

---

## ⚙️ Tecnologias Utilizadas

- **Python 3**
- **Google Colab / Jupyter Notebook**
- **Pandas** — manipulação e limpeza de dados  
- **SQLite (SQLAlchemy)** — criação de banco de dados em memória  
- **Matplotlib & Seaborn** — visualizações estáticas  
- **Plotly Express** — visualizações interativas  

---

## 📂 Estrutura dos Dados

O notebook utiliza as seguintes tabelas (carregadas via CSV):

| Tabela | Descrição |
|--------|------------|
| `itens_pedidos` | Informações sobre os produtos vendidos, frete e quantidade. |
| `pedidos` | Dados das vendas realizadas (data, valor e vendedor). |
| `produtos` | Características dos produtos comercializados. |
| `vendedores` | Dados dos vendedores da loja. |

As fontes dos dados estão disponíveis no repositório:  
[Alura SQL + Python Integração](https://github.com/alura-cursos/SQL-python-integracao)

---

## 🚀 Como Executar o Projeto

### 🧭 Opção 1 — Executar no Google Colab

1. Abra o link abaixo:
   ```
   https://colab.research.google.com/drive/1BSWzR-KB7k6G_rg0wybrlm7ZsFRy7BOO?usp=sharing
   ```
2. Clique em **"Conectar"** no topo do Colab.
3. Execute cada célula (Shift + Enter) para visualizar os resultados e gráficos.

> 💡 Substitua o caminho acima se o nome do seu repositório for diferente.

---

### 💻 Opção 2 — Executar Localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/Cilli01/meteora_analise.git
   cd meteora-analise
   ```
2. Instale as dependências:
   ```bash
   pip install pandas sqlalchemy matplotlib seaborn plotly
   ```
3. Execute o notebook:
   ```bash
   jupyter notebook Notebook_Meteora.ipynb
   ```

---

## 📈 Principais Análises

- Distribuição de **condições dos produtos** vendidos.  
- Top 10 **produtos mais vendidos** e **com maior receita**.  
- Ranking de **marcas mais populares**.  
- Desempenho dos **vendedores por ano e estado**.  
- Vendas mensais e **picos de receita em 2020**.  
- Insights para **ações de Natal em São Paulo**.

---

## 🧠 Resultados e Insights

- São Paulo apresenta o maior volume de pedidos entre os estados.
- Alguns produtos e marcas dominam as vendas nacionais.
- Há sazonalidade clara nas vendas de dezembro (Natal).
- O desempenho dos vendedores varia fortemente por região e época do ano.

---

## 🧑‍💻 Autor

**Caio César**  
💼 Data Science & Business Intelligence  
📧 [caiocesarccs01@gmail.com]  
🔗 [LinkedIn](www.linkedin.com/in/caio-cesar-ccs)


