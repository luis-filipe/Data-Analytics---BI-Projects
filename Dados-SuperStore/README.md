# 📊 Projeto de Análise de Dados – SuperStore  
Pipeline completo de ETL + Análise Exploratória em Python + Dashboard em Power BI

Este projeto apresenta um fluxo completo de dados (ETL + EDA + BI), utilizando **Python** para limpeza, transformação e análise exploratória dos dados da SuperStore, seguido da criação de um **Dashboard interativo em Power BI** para visualização dos principais indicadores de vendas, lucro e desempenho comercial.

---

## 🗂️ Estrutura do Repositório

📁 Projeto-SuperStore
│
├── Dashboard.pbix
│ → Arquivo do Power BI com todos os dashboards desenvolvidos.
│
├── Python Code.ipynb
│ → Código completo de tratamento, limpeza e criação de novas colunas.
│
├── Python Visual.ipynb
│ → Código contendo as visualizações (gráficos, histogramas, boxplots etc.)
│
├── Superstore_Sujo.xlsx
│ → Base de dados original (dados brutos).
│
├── Superstore_Limpo.csv
│ → Base de dados tratada e pronta para análise.
│
└── README.md

---

# 🧼 1. Processo de ETL em Python (Limpeza + Transformação)

Todo o processo foi realizado em **Python**, utilizando:

- pandas  
- numpy  
- matplotlib  
- seaborn  

## ✔️ Etapas do ETL

### **1. Importação e visualização inicial**
- Importação das bibliotecas
- Carregamento da planilha original
- Visualização (head, info, describe)
- Contagem de valores nulos
- Contagem de valores únicos por coluna

### **2. Limpeza dos dados**
- Remoção de duplicados  
- Tratamento de inconsistências  
- Padronização de casas decimais (2 casas)  
- Ajuste e formatação das datas  

### **3. Criação de novas colunas**
- Ano  
- Mês  
- Dia  
- Valor Unitário  
- Margem  

### **4. Detecção de Outliers**
- Identificação via boxplot  
- Análise estatística (IQR)

### **5. Análise Exploratória (EDA)**
Foram gerados:
- Histogramas  
- Boxplots  
- Matriz de correlação  
- Scatterplots  
- Total de vendas por categoria  
- Lucro por estado  
- Lucro por categoria e subcategoria  
- Quantidade vendida por segmento  

### **6. Exportação dos dados tratados**
Arquivo final:
- **Superstore_Limpo.csv**

---

# 📊 2. Dashboards Desenvolvidos no Power BI

Após o processamento dos dados, foi criado um dashboard completo no Power BI com diversas páginas de análise.

## 📌 Índice do Dashboard

### **1️⃣ Visão Geral**
- Total de vendas  
- Total de lucro  
- Ticket médio  
- Margem média  
- Vendas por segmento  
- Lucro por categoria  
- Filtro por ano  

### **2️⃣ Produtos e Categorias**
- Produtos mais vendidos  
- Produtos mais lucrativos  
- Produtos com prejuízo  
- Vendas por subcategoria  

### **3️⃣ Segmentos**
- Lucro por segmento  
- Vendas por segmento  
- Comparações entre segmentos  

### **4️⃣ Vendedores**
- Melhores vendedores  
- Quem mais lucra  
- Quem gera prejuízo  
- Ticket médio  
- Desconto médio  
- Total de pedidos  

### **5️⃣ Descontos e Rentabilidade**
- Relação entre desconto e lucro  
- Descoberta: **descontos acima de 20% geram prejuízo**  
- Impacto dos descontos na margem  
- Lucro em vendas com mais de 50% de desconto  

### **6️⃣ Mapa – Cidades mais lucrativas**
- Cidades mais rentáveis  
- Cidades com menor margem  
- Visualização geográfica do lucro  

---

# 💡 3. Principais Insights

### 🔻 Descontos acima de 20% geram prejuízo
Identificado claramente na análise visual e estatística.

### 🔻 Vendedores com prejuízo
Alguns vendedores concedem descontos excessivos, destruindo a margem.

### 🔻 Subcategorias mais rentáveis
Subcategorias específicas impulsionam o lucro da empresa.

### 🔻 Segmentos mais lucrativos
Segmentos se comportam de maneira distinta em margem e volume.

---

# 🚀 4. Como Utilizar o Projeto

### **1. Clonar o repositório**

2. Abrir os códigos em Python

Python Code.ipynb → limpeza e transformação

Python Visual.ipynb → gráficos e EDA

3. Conferir os dados

Superstore.xlsx → base bruta

Superstore_Limpo.csv → base tratada

4. Abrir o dashboard no Power BI

Abra:

Dashboard.pbix

🛠️ Tecnologias Utilizadas

Python

pandas

numpy

matplotlib

seaborn

Power BI

Excel
