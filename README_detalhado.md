# Online Retail Analysis

## Descrição do Projeto
Este repositório contém uma análise completa dos dados de uma loja online. Utilizando técnicas avançadas de análise e modelagem, o projeto fornece insights estratégicos para otimizar operações de vendas, segmentação de clientes, previsão de demanda e engajamento. Cada seção do projeto foi desenvolvida com o objetivo de agregar valor à empresa ao fornecer informações úteis para a tomada de decisão.

---

## Estrutura dos Projetos

### 1. Análise de Sensibilidade de Preços
**Objetivo**: Avaliar como a variação de preços afeta as vendas de produtos específicos.  
**Etapas**:
   - Coleta de dados de preços e vendas ao longo do tempo.
   - Análise da elasticidade de preço para entender a sensibilidade dos clientes.
   - Criação de gráficos para visualizar a relação entre preço e quantidade vendida.
**Resultados**:  
   - Identificação de produtos com maior sensibilidade a mudanças de preço.
**Valor para a Empresa**:  
   - Permite definir estratégias de precificação mais eficazes para maximizar a receita.

---

### 2. Clusterização de Produtos
**Objetivo**: Identificar segmentos de produtos com características semelhantes.  
**Etapas**:
   - Pré-processamento de dados e seleção de variáveis relevantes para clustering.
   - Aplicação de K-Means para segmentação de produtos.
   - Visualização dos clusters para interpretação dos segmentos.
**Resultados**:  
   - Grupos de produtos com características semelhantes.
**Valor para a Empresa**:  
   - Facilita a criação de campanhas de marketing segmentadas e o gerenciamento de inventário.

---

### 3. Modelo de Classificação de Produto
**Objetivo**: Prever a categoria de novos produtos adicionados ao inventário.  
**Etapas**:
   - Preparação de um conjunto de dados de treinamento com produtos previamente classificados.
   - Treinamento de um modelo de classificação usando Random Forest.
   - Avaliação do modelo com métricas como acurácia e matriz de confusão.
**Resultados**:  
   - Classificação automatizada de produtos.
**Valor para a Empresa**:  
   - Simplifica o processo de categorização de novos produtos, agilizando o gerenciamento do inventário.

---

### 4. Segmentação de Clientes com Análise RFM
**Objetivo**: Classificar os clientes com base em Recência, Frequência e Valor Monetário.  
**Etapas**:
   - Cálculo das variáveis RFM para cada cliente.
   - Normalização dos dados e aplicação de clustering para segmentação.
   - Análise dos clusters para identificar perfis de clientes.
**Resultados**:  
   - Grupos de clientes segmentados por comportamento de compra.
**Valor para a Empresa**:  
   - Facilita a personalização de campanhas de marketing e programas de fidelização.

---

### 5. Previsão de Demanda
**Objetivo**: Prever a demanda futura dos produtos para otimizar o gerenciamento de estoque.  
**Etapas**:
   - Análise temporal das vendas diárias.
   - Decomposição sazonal e ajuste do modelo ARIMA.
   - Previsão de demanda para períodos futuros e cálculo de erro de previsão.
**Resultados**:  
   - Previsão de demanda com base no histórico de vendas.
**Valor para a Empresa**:  
   - Auxilia no planejamento de estoque e na redução de custos com excesso de inventário.

---

### 6. Sistema de Recomendação de Produtos
**Objetivo**: Recomendar produtos para clientes com base em compras anteriores.  
**Etapas**:
   - Criação de uma matriz de clientes por produtos.
   - Cálculo da similaridade entre clientes usando o cosseno de similaridade.
   - Implementação de uma função de recomendação baseada na similaridade.
**Resultados**:  
   - Lista de produtos recomendados para cada cliente.
**Valor para a Empresa**:  
   - Aumenta o engajamento dos clientes e a probabilidade de compras cruzadas.

---

### 7. Análise de Retenção e Engajamento dos Clientes
**Objetivo**: Analisar a taxa de retenção dos clientes ao longo do tempo e identificar padrões de engajamento.  
**Etapas**:
   - Agrupamento dos clientes em coortes com base no mês de primeira compra.
   - Cálculo da taxa de retenção para cada coorte.
   - Visualização das coortes usando um heatmap.
**Resultados**:  
   - Identificação de coortes com alta ou baixa retenção.
**Valor para a Empresa**:  
   - Fornece insights sobre a eficácia das campanhas de fidelização e permite ajustes para melhorar a retenção.

---

## Principais Ferramentas e Tecnologias Utilizadas
- **Linguagem**: Python 3.x
- **Bibliotecas**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`, `mlxtend`, `xgboost`, `openpyxl`, `plotly`

## Como Executar o Projeto

1. **Pré-requisitos**:
   - Certifique-se de ter o Python 3.x instalado.
   - Instale as bibliotecas necessárias executando o comando abaixo.

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels mlxtend xgboost openpyxl plotly
