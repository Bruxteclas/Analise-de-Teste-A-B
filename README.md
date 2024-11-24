# Análise de Teste A/B: Impacto de Alterações de Design no Comportamento dos Usuários

Este projeto realiza uma análise detalhada de um experimento A/B para avaliar o impacto de mudanças no design do site sobre o comportamento e engajamento dos usuários.

## 📋 Objetivo
O projeto visa analisar o impacto de uma mudança no design do site de varejo online, especificamente a alteração da cor de fundo da página principal de branco (Grupo A) para preto (Grupo B). O objetivo é entender se essa alteração influencia o comportamento dos usuários em termos de engajamento e conversão. A empresa busca utilizar os resultados para tomar decisões baseadas em dados sobre o design do site e melhorar a experiência do usuário.

## 📂 Estrutura do Projeto
- **`Analise de Teste AB.ipynb`**: Contém a análise completa, incluindo limpeza de dados, visualizações e testes estatísticos.
- **Dados de entrada**: O arquivo `ab_testing.csv` usado para análise inclui as seguintes colunas:
  - **User ID**: Identificador único de usuários.
  - **Group**: Grupo de controle (`A`) ou tratamento (`B`).
  - **Page Views**: Número de páginas visualizadas.
  - **Time Spent**: Tempo (em segundos) que o usuário passou no site.
  - **Conversion**: Indicador se o usuário realizou a ação desejada (`Yes` ou `No`).
  - **Device**: Tipo de dispositivo usado (`Desktop` ou `Mobile`).
  - **Location**: Região do usuário.

## 🔍 Análises Realizadas
1. **Exploração dos Dados**
   - Verificação de valores ausentes e duplicados.
   - Análise estatística descritiva de todas as colunas.
   - Visualização das distribuições de Page Views e Time Spent.
   
2. **Comparações por Grupo**
   - Boxplots e médias para Page Views e Time Spent.
   - Análise da taxa de conversão entre grupos.

3. **Testes Estatísticos**
   - **Teste t**: Comparação de médias de Page Views e Time Spent entre grupos.
   - **Teste Qui-Quadrado**: Avaliação da significância das diferenças na taxa de conversão.

4. **Dashboard Interativo** *(opcional)*:
   - Desenvolvido com Dash para apresentar os resultados de forma interativa.

## 📊 Principais Resultados
- Não houve impacto significativo nas métricas de engajamento (Page Views e Time Spent).
- O grupo B apresentou uma taxa de conversão significativamente maior do que o grupo A, indicando que o novo design da cor **Preta** do site incentivou ações desejadas.

## 🛠️ Tecnologias e Ferramentas
- **Python**: Para processamento e análise dos dados.
- **Bibliotecas**:
  - `pandas`, `numpy`: Manipulação de dados.
  - `matplotlib`, `seaborn`: Visualizações.
  - `scipy.stats`: Testes estatísticos.
  - `dash`, `plotly`: Construção de dashboards interativos.

## 📈 Visualizações
As principais visualizações incluem:
- Histogramas para distribuições de métricas.
- Boxplots para comparações entre grupos.
- Gráficos de barras para taxas de conversão.

## 📝 Conclusão e Recomendações
- **Conclusão**: A mudança no design não impactou o engajamento, mas melhorou significativamente a taxa de conversão.
- **Recomendação**: Adotar o novo design, considerando o impacto positivo nas conversões.
