# 🎾 Projeto Vertex — Dashboard Comercial de Tênis

> **Análise de Vendas, Rentabilidade e Expansão de Mercado para uma Empresa do Setor Tênis**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Status](https://img.shields.io/badge/Status-Ativo-brightgreen?style=for-the-badge)

---

<img width="1447" height="806" alt="dashboard_vertex" src="https://github.com/user-attachments/assets/1ef0e0fc-6e3c-4314-a7ef-0dd0acce5cbc" />

---

## 📌 Sobre o Projeto

O **Projeto Vertex** é um dashboard analítico desenvolvido em Power BI para uma empresa do segmento de tênis que comercializa equipamentos, acessórios e vestuário esportivo.

## 🔗 Acesse o Projeto

https://app.powerbi.com/view?r=eyJrIjoiNjc0ODAyMDktMjEyMC00NTdmLWE2ZTYtN2IxNWU5YWVlOWU2IiwidCI6IjU1ODQ1MjA3LTk3YjAtNDU4OS1hNjQxLTQ4NGUzNjAxOTlkNyJ9

### 🎯 Objetivos

O objetivo principal é transformar dados brutos de vendas em **inteligência de negócio**, respondendo perguntas críticas para a tomada de decisão comercial e estratégica.

- Monitorar o desempenho financeiro da empresa (Faturamento, Custo e Margem Bruta)
- Identificar tendências de crescimento ano a ano e mês a mês
- Revelar quais **categorias de produtos** e **segmentos de clientes** são mais rentáveis
- Entender a **concentração geográfica** das vendas e oportunidades de expansão
  
---

## 🗂️ Estrutura dos Dados

O modelo é organizado em um **esquema estrela** com as seguintes tabelas:

| `fVendas` | Fato | Transações de vendas com segmento, região, estado, produto e data |</br>
| `dProdutos` | Dimensão | Produtos com categoria, subcategoria, custo e preço padrão |</br>
| `SubcategoriaProduto` | Dimensão | Detalhamento de subcategorias dos produtos |</br>
| `CategoriaProduto` | Dimensão | Categorias principais dos produtos |</br>
| `dCalendario` | Dimensão | Calendário completo para análises temporais |</br>

---

## 📊 KPIs Principais

| `$ Faturamento` | Receita total de vendas |</br>
| `$ Custo` | Custo total dos produtos vendidos |</br>
| `$ Margem Bruta` | Diferença entre faturamento e custo |</br>
| `% Margem Bruta` | Percentual de margem sobre o faturamento |</br>
| `% YoY` | Variação de faturamento/custo/margem ano a ano |</br>
| `% MoM` | Variação de faturamento/custo/margem mês a mês |</br>
| `$ Rentabilidade` | Indicador consolidado de saúde financeira |</br>

---

## 💡 Insights Descobertos

### 📈 1. Crescimento Expressivo em 3 Anos

| 2022 | R$ 2.688.726 |</br>
| 2023 | R$ 6.669.806 |</br>
| 2024 | R$ 8.368.931 |</br>

> A empresa mais que **triplicou** o faturamento entre 2022 e 2024. O crescimento desacelerou em 2024, mas ainda se manteve em 25,5%

---

### 🏪 2. Canal de Vendas: Loja Especializada Domina

| Loja Especializada | R$ 7.339.389 |</br>
| Grande Varejista | R$ 3.558.894 |</br>
| Distribuidor Atacadista | R$ 2.832.332 |</br>
| Clube de Tênis | R$ 2.004.008 |</br> 
| Academia de Tênis | R$ 1.992.840 |</br>

> A **Loja Especializada** responde por mais de 40% do faturamento total. O **Distribuidor Atacadista** tem a maior margem percentual — um canal a ser **expandido estrategicamente**.

---

### 🎾 3. Produtos Profissionais Lideram

| Profissionais | R$ 4.824.800 |</br>
| Masculino | R$ 1.578.250 |</br>
| Camisetas e Polos | R$ 1.570.260 |</br>
| Raqueteiras | R$ 1.177.800 |</br>
| Infantil | R$ 704.085 |</br>

> Produtos da categoria **Profissionais** dominam em volume, mas têm a **menor margem**.Categorias como **Vestuário (50%)** e **Infantil (51,3%)** são muito mais rentáveis.
---

### 🗺️ 4. Concentração Geográfica: Sudeste Responde por 68% das Vendas

| Sudeste | R$ 11.835.478 | 68% |</br>
| Sul | R$ 3.186.690 | 18% |</br>
| Nordeste | R$ 1.436.455 | 8% |</br>
| Centro-Oeste | R$ 809.676 | 5% |</br>
| Norte | R$ 459.164 | 3% |</br>

> Norte e Centro-Oeste têm baixíssima participação, representando clara **oportunidade de expansão**

---

## 🛠️ Tecnologias Utilizadas

- **Power BI Desktop** — Modelagem e visualização
- **DAX** — Cálculo de medidas, inteligência de tempo (YoY, MoM, LY, LM)
- **Power Query (M)** — Transformação e limpeza dos dados
- **Modelo Estrela** — Estrutura dimensional para performance e clareza


## 🔗 Fonte dos Dados

Os dados utilizados foram extraídos da plataforma de Cursos Xperiun

Os dados.csv foram tratados para análise no Power Query antes da modelagem e análise.

