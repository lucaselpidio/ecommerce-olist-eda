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
## 📎 Notebook no Kaggle
O projeto também está disponível no Kaggle, onde foi desenvolvido e executado originalmente:

🔗 [Acessar o notebook no Kaggle](https://www.kaggle.com/code/lucaselpidio/analise-olist)

---

## 🛠️ Ferramentas Utilizadas
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook (Kaggle)

---

## 📈 Análises Realizadas

### 1️⃣ Faturamento do E-commerce
O faturamento total foi calculado considerando apenas pedidos com status "delivered", garantindo que apenas transações concluídas fossem analisadas.

A análise mensal do faturamento permite observar sua evolução ao longo do tempo, evidenciando períodos de crescimento do e-commerce ao longo do intervalo analisado.

No período analisado, o e-commerce gerou um faturamento total de **R$ 19.618.578,64**, indicando uma operação de grande porte.
 
![Faturamento mensal do e-commerce](https://github.com/lucaselpidio/media-rep/blob/main/olist_project/fat_mensal.png)

---

### 2️⃣ Ticket Médio dos Pedidos
Visualização da distribuição do valor dos pedidos com o objetivo de comunicar o comportamento típico dos clientes, evitando que valores extremamente raros prejudiquem a leitura do gráfico.

A análise considera todos os pedidos no cálculo do ticket médio, sem exclusão de dados. No entanto, para fins de comunicação visual, o gráfico foi limitado ao percentil 99, permitindo destacar a região onde se concentra a maior parte dos pedidos.

A distribuição apresenta forte assimetria à direita, indicando a presença de poucos pedidos de valor extremamente elevado em comparação à maioria das compras.
 
![Distribuição do ticket médio dos pedidos](https://github.com/lucaselpidio/media-rep/blob/main/olist_project/ticket_medio.png)

---

### 3️⃣ Volume de Vendas × Faturamento por Categoria
Análise comparativa entre o volume de vendas e o faturamento por categoria de produto, com o objetivo de identificar diferenças entre popularidade e geração de receita.

O volume de vendas por categoria evidencia as categorias mais populares, geralmente associadas a produtos de menor ticket, porém com alta recorrência de compras.

Já a análise de faturamento por categoria destaca categorias menos frequentes, porém mais lucrativas, podendo apresentar divergências significativas em relação ao ranking por volume de vendas.
 
![Volume de vendas por categoria](https://github.com/lucaselpidio/media-rep/blob/main/olist_project/cat_produtos.png)

![Faturamento por categoria](https://github.com/lucaselpidio/media-rep/blob/main/olist_project/cat_fat.png)


---

### 4️⃣ Evolução Temporal dos Pedidos
Análise da evolução do volume de pedidos ao longo do tempo, com o objetivo de avaliar o crescimento do e-commerce e investigar a presença de possíveis variações no comportamento de compra.

A análise foi realizada no nível de pedido,

Os resultados evidenciam um crescimento consistente no volume de pedidos ao longo dos anos analisados. No entanto, comparações diretas entre meses de anos diferentes devem ser interpretadas com cautela, uma vez que o crescimento estrutural do negócio influencia fortemente o volume absoluto de pedidos, limitando a identificação de sazonalidade com esse tipo de visualização.
 
![Evolução temporal dos pedidos](https://github.com/lucaselpidio/media-rep/blob/main/olist_project/comportamento_temporal.png)


---

### 5️⃣ Prazo de Entrega × Avaliação do Cliente
Análise do impacto do cumprimento do prazo de entrega na avaliação dos clientes, buscando responder se atrasos na entrega influenciam a nota atribuída à experiência de compra.

A análise foi realizada no nível de pedido.
 
![Avaliação média por status de entrega](https://github.com/lucaselpidio/media-rep/blob/main/olist_project/entrega_aval.png)


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

      clean_final_data.rar
notebook/

         analise_olist.ipynb
README.md



---

## 👤 Autor
**Lucas Victor Elpidio**  
Analista de Dados  
📎 GitHub: https://github.com/lucaselpidio

---

## 📄 Observação
Este projeto foi desenvolvido com fins educacionais e de portfólio, utilizando dados públicos disponibilizados pela Olist.

Os dados no formato csv contidos no diretório data tiveram que ser compactados para serem subidos no GitHub, mas podem ser salvos usando o método to_csv diretamente pelo arquivo ipynb.
