# 📊 Sistema de Controle de Vendas

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Status](https://img.shields.io/badge/Status-Concluído-success)

Sistema desenvolvido em Python para gerenciamento de produtos, clientes e vendas, utilizando arquivos CSV como armazenamento local dos dados e geração de relatórios analíticos e gráficos.

## 🚀 Funcionalidades

### 📦 Gestão de Produtos
- Cadastro de produtos
- Atualização de produtos
- Exclusão de produtos
- Listagem de produtos

### 👥 Gestão de Clientes
- Cadastro de clientes
- Atualização de clientes
- Exclusão de clientes
- Listagem de clientes

### 💰 Gestão de Vendas
- Registro de vendas
- Validação de clientes e produtos
- Cálculo automático do valor total
- Histórico de vendas

### 📈 Relatórios
- Total faturado
- Quantidade total vendida
- Top 3 categorias mais vendidas
- Produto mais vendido
- Ticket médio por cliente
- Relatório consolidado em arquivo `.txt`

### 📊 Dashboard Gráfico
O sistema gera automaticamente:

- Vendas por data
- Categorias mais vendidas
- Perfil dos clientes por faixa etária

---

## 🛠️ Tecnologias Utilizadas

- Python 3
- Pandas
- Matplotlib
- CSV

---

## 📂 Estrutura do Projeto

```text
.
├── projeto.py
├── tabela_produto.csv
├── tabela_cliente.csv
├── tabela_venda.csv
└── relatorio_consolidado.txt
```

---

## ⚙️ EXECUÇÃO

- Criar as tabelas CSV
- Inserir dados fictícios
- Gerar relatórios automáticos
- Exibir gráficos de análise

---

## 📋 Modelo de Dados

### Produtos

| Campo | Descrição |
|---------|---------|
| id_produto | Identificador do produto |
| nome_produto | Nome do produto |
| valor_unitario | Valor unitário |
| categoria_produto | Categoria do produto |

### Clientes

| Campo | Descrição |
|---------|---------|
| id_cliente | Identificador do cliente |
| nome | Nome completo |
| data_nascimento | Data de nascimento |
| email | E-mail |
| telefone | Telefone |

### Vendas

| Campo | Descrição |
|---------|---------|
| id_venda | Identificador da venda |
| id_produto | Produto vendido |
| id_cliente | Cliente comprador |
| quantidade | Quantidade adquirida |
| data_venda | Data da venda |
| valor_total | Valor total da venda |

---

## 📊 Indicadores Gerados

- Faturamento total
- Quantidade de itens vendidos
- Categorias mais vendidas
- Produto mais vendido
- Ticket médio por cliente

---

## 🎯 Objetivos do Projeto

Este projeto foi desenvolvido para praticar:

- Manipulação de dados com Pandas
- Operações CRUD
- Leitura e escrita de arquivos CSV
- Relatórios automatizados
- Visualização de dados com Matplotlib
- Estruturação de sistemas administrativos
- Análise de dados aplicada

---

## 💡 Melhorias Futuras

- Integração com banco de dados SQL
- Interface gráfica (Tkinter ou PyQt)
- API REST com Flask
- Exportação de relatórios em PDF
- Dashboard web interativo
