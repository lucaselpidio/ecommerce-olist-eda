# 📊 Análise de Dados — E-commerce Olist

## 📌 Visão Geral
Este projeto tem como objetivo analisar dados do e-commerce brasileiro **Olist**, buscando compreender padrões de vendas, comportamento de preços, evolução temporal dos pedidos e o impacto da logística na experiência do cliente.

O projeto foi desenvolvido com foco em **portfólio profissional**, simulando um cenário real de atuação de um Analista de Dados Júnior.

---

## 🎯 Objetivos do Projeto
- Avaliar o comportamento dos valores dos pedidos
- Comparar volume de vendas e faturamento por categoria
- Analisar a evolução temporal dos pedidos
- Investigar o impacto do prazo de entrega na avaliação dos clientes

---

## 🗂️ Dataset
- Fonte: Brazilian E-Commerce Public Dataset by Olist
- Ambiente: Kaggle
- Dataset consolidado contendo informações de:
  - Pedidos
  - Itens
  - Pagamentos
  - Clientes
  - Produtos
  - Avaliações
  - Logística

---

## 🛠️ Ferramentas Utilizadas
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook (Kaggle)

---

## 📈 Análises Realizadas

### 1️⃣ Distribuição dos Valores dos Pedidos
- Avaliação da concentração dos valores pagos
- Identificação de assimetria e cauda longa
- Maioria dos pedidos concentrada em faixas de menor valor

---

### 2️⃣ Valores dos Pedidos (Distribuição Detalhada)
- Análise estatística descritiva
- Identificação de valores máximos elevados, porém raros
- Entendimento do impacto de valores extremos na visualização

---

### 3️⃣ Categorias de Produtos
- Comparação entre:
  - Volume de vendas
  - Faturamento total
- Identificação de categorias populares vs. categorias mais lucrativas

---

### 4️⃣ Evolução Temporal dos Pedidos
- Análise da quantidade de pedidos ao longo do tempo
- Identificação de crescimento consistente do e-commerce
- Discussão sobre limitações para análise de sazonalidade

---

### 5️⃣ Prazo de Entrega × Avaliação do Cliente
- Criação de métrica de atraso na entrega
- Classificação dos pedidos em:
  - Entregues no prazo
  - Entregues com atraso
- Comparação da nota média dos clientes

📌 **Resultado-chave**:
- Pedidos atrasados: média de avaliação ≈ **2,2**
- Pedidos no prazo: média de avaliação ≈ **4,1**

---

## 🔎 Principais Insights
- O e-commerce apresentou crescimento consistente ao longo do período analisado
- Categorias mais vendidas em volume não são necessariamente as que mais geram faturamento
- A maior parte dos pedidos possui valores relativamente baixos
- O prazo de entrega tem impacto direto e significativo na satisfação do cliente

---

## 🚀 Próximos Passos
- Analisar sazonalidade separando crescimento estrutural e efeito mensal
- Investigar causas de atraso por região, vendedor ou categoria
- Criar dashboards interativos para acompanhamento dos indicadores
- Aplicar modelos simples de previsão de demanda ou atraso

---

## 📁 Estrutura do Repositório
data /

      clean_final_data.csv
notebook/

         analise_olist.ipynb
README.md
