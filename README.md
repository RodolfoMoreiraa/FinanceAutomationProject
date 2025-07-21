# 📊 Simple Finance Dashboard

Um dashboard financeiro simples construído com **Streamlit**, **Pandas** e **Plotly**, que permite visualizar e categorizar as suas despesas e receitas de forma prática e interativa.

## 🚀 Funcionalidades

- 📁 Upload de ficheiros CSV com transações bancárias
- 🏷️ Criação e gestão de categorias personalizadas
- 📌 Atribuição de categorias às despesas manualmente
- 💾 Salvamento automático das categorias em `categories.json`
- 📊 Visualização gráfica das despesas por categoria (gráfico de pizza)
- 💳 Resumo de pagamentos totais

## 🛠️ Tecnologias Utilizadas

- **[Streamlit](https://streamlit.io/)** – Interface interativa em Python para construção de dashboards
- **[Pandas](https://pandas.pydata.org/)** – Manipulação e análise dos dados das transações
- **[Plotly](https://plotly.com/python/)** – Criação de gráficos interativos

## 🧾 Formato Esperado do CSV

O ficheiro CSV deve conter as seguintes colunas (com estes nomes exatos):

- `Date` – Data da transação (ex: `01 Jan 2024`)
- `Details` – Descrição da transação
- `Amount` – Valor da transação (ex: `1,234.56`)
- `Debit/Credit` – Tipo de transação (`Debit` ou `Credit`)

## ▶️ Como Executar Localmente

1. Clone o repositório:

```bash
git clone https://github.com/SEU_USUARIO/finance-dashboard.git
cd finance-dashboard
