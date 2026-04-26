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
- Looker / Data Studio

---
## Acesse a dashboard construída no Looker Studio clicando na imagem

[![Thumbnail Dashboard Olist](https://raw.githubusercontent.com/lucaselpidio/media-rep/refs/heads/main/dashboard_olist_thumbnail.png)](https://datastudio.google.com/reporting/30b2712f-01db-4832-88b4-7837695f6257)

---

# 📊 Resumo Geral dos Insights da Dashboard

## 💰 Receita e Volume
O negócio apresenta um volume consistente de pedidos ao longo do tempo, com faturamento acompanhando essa evolução.

* **Ticket Médio:** Estável entre **R$ 206,00 e R$ 208,00**, indicando consistência no valor das compras.
* **Insight:** O crescimento do faturamento está mais atrelado ao **volume de pedidos** do que a variações no valor médio por compra.

---

## 🛍️ Produto e Comportamento de Compra
* Faturamento concentrado em categorias específicas de produtos.
* Alta diversidade nas formas de pagamento utilizadas.
* **Insight:** Oportunidade de otimizar a conversão focando nas categorias de maior performance e adaptando o checkout às preferências de pagamento.

---

## 🚚 Logística
* Tempo médio de entrega dentro do padrão esperado.
* **Taxa de Atraso:** Apenas **6,27%** (6.3k de 97.6k pedidos).
* **Insight:** A operação logística é majoritariamente eficiente e apresenta baixa taxa de erro.

---

## ⭐ Experiência do Cliente
* **Nota Média Geral:** 4.0
* **Distribuição de Avaliações:**
    * **5⭐:** 66k avaliações (Volume expressivo)
    * **1⭐:** 14.8k avaliações (Volume relevante)
* **Insight:** Existe uma **polarização** nas avaliações, indicando que experiências extremas (muito boas e muito ruins) coexistem na operação.

---

## 🔗 Relação Logística × Satisfação (Insight Principal)
A pontualidade é o principal driver de satisfação:
* **Pedidos no Prazo:** 4.15 ⭐
* **Pedidos Atrasados:** 2.25 ⭐
* **Insight Crítico:** O atraso reduz a satisfação do cliente em quase **50%**.

---

## 💵 Logística × Valor Financeiro
* **Ticket Médio (Atrasado):** R$ 208,08
* **Ticket Médio (No Prazo):** R$ 206,03
* **Insight:** O atraso não impacta o valor financeiro da venda atual, mas prejudica severamente a percepção de marca.

---

## 🧠 Conclusão Estratégica
Embora a falha logística atinja uma minoria (**~6%**), o impacto na experiência do usuário é desproporcional. O problema não afeta o faturamento imediato (ticket médio estável), mas gera um risco crítico para a **retenção e reputação** do negócio.

### 🚀 Resumo para Negócio
1.  **Operação:** Eficiente em escala.
2.  **Gargalo:** Impacto emocional alto em falhas pontuais.
3.  **Foco:** Melhorar a comunicação e reduzir atrasos para proteger o LTV (Lifetime Value).

>  *A análise mostrou que a logística é eficiente em escala, mas falhas pontuais têm impacto desproporcional na satisfação do cliente, sem afetar diretamente a receita no curto prazo.*
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
