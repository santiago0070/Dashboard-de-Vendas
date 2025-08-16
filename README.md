# 📊 Análise de Vendas de Cursos Online

Bem-vindo ao repositório da **Análise de Vendas de Cursos Online**! 🚀 Este projeto contém um dataset em Excel (`Avaliação de Vendas de Cursos Onlines (4).xlsx`) com dados detalhados sobre vendas de cursos online em 2021. Aqui você pode explorar o desempenho de vendas por vendedor, produto, região e metas mensais. Ideal para análises de negócios, visualizações de dados e relatórios de BI!

---

## 📋 Visão Geral do Projeto

Este dataset registra vendas de cursos online (como Excel, Power BI, Python, VBA, Word e PowerPoint) realizadas por uma equipe de vendedores no Brasil em 2021. Ele inclui:

- **Vendas por mês, vendedor e produto** 📈
- **Metas mensais** 🎯
- **Distribuição geográfica das vendas** 🌎

Use este dataset para análises como:
- Identificar os melhores vendedores.
- Avaliar quais cursos geram mais receita.
- Comparar vendas reais com metas.
- Explorar tendências regionais no Brasil.

---

## 📂 Estrutura do Dataset

O arquivo Excel contém três planilhas principais:

### 1. Análise
- **Descrição**: Contém tabelas dinâmicas com resumos de vendas para 2021.
- **Dados**:
  - Vendas totais por mês e vendedor.
  - Receita por produto (Excel, Power BI, Python, VBA, Word, PowerPoint).
  - Comparação com metas mensais.
- **Exemplo**:
  - Gabriel liderou com R$291.450 em vendas totais.
  - Janeiro teve vendas de R$47.200, superando a meta de R$31.000.

### 2. Base Tratada
- **Descrição**: Registro detalhado de 3.670 transações de vendas.
- **Colunas**:
  - `Data`: Data da venda (formato serial do Excel, ex.: 43466 = 01/01/2019).
  - `Ano`: Ano da venda (ex.: 2019, 2021).
  - `Mês`: Mês da venda (ex.: jan, fev).
  - `Vendedor`: Nome do vendedor (ex.: Paulo, Diego, Alon).
  - `Cliente`: Nome completo do cliente.
  - `Primeiro Nome Cliente` e `Sobrenome Cliente`: Nome e sobrenome.
  - `Região`: Região do Brasil (Sudeste, Norte, Sul, Centro-Oeste, Nordeste).
  - `Produto`: Curso vendido (ex.: VBA, Word).
  - `Valor`: Valor da venda (ex.: R$300, R$450, R$500, R$600).
- **Exemplo**: Uma venda de VBA por R$600 realizada por Diego na região Norte em janeiro de 2019.

### 3. Meta Mensal
- **Descrição**: Lista as metas de vendas para cada mês de 2021.
- **Colunas**:
  - `Mês`: Janeiro a dezembro.
  - `Meta`: Valor alvo (ex.: R$31.000 para janeiro, R$46.000 para fevereiro).

---

## 🔍 Insights Principais

- **Desempenho por Vendedor** 🏆:
  - Gabriel: R$291.450 (maior vendedor).
  - João: R$262.700 (menor entre os principais).
- **Popularidade dos Produtos** 📚:
  - VBA e Word são os mais vendidos, com valores frequentes de R$600 e R$500/R$600, respectivamente.
- **Tendências Regionais** 🌍:
  - A planilha `Base Tratada` permite analisar vendas por região (ex.: Sudeste, Nordeste).
- **Metas Mensais** 🎯:
  - Janeiro superou a meta (R$47.200 vs. R$31.000), enquanto agosto ficou abaixo (R$42.750 vs. R$51.000).

---

## 🚀 Como Usar

Este dataset é perfeito para análises de dados, visualizações e relatórios. Aqui estão algumas ideias:

- **Análise de Vendedores**: Compare o desempenho dos vendedores ao longo do ano.
- **Receita por Produto**: Veja quais cursos geram mais receita.
- **Comparação com Metas**: Avalie se as metas mensais foram atingidas.
- **Tendências Regionais**: Explore a distribuição de vendas por região.

### Pré-requisitos
- **Software**: Microsoft Excel, LibreOffice Calc ou Python com `pandas` e `openpyxl`.
- **Bibliotecas Python** (opcional): `pandas`, `matplotlib`, `seaborn` para análises e visualizações.

### Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/your-username/online-course-sales.git
