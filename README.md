# Projeto de Análise de Dados Financeiros dos Clientes

## Descrição

Este projeto visa analisar dados financeiros de clientes e calcular métricas importantes como **Rentabilidade**, **Margem Operacional** e **Percentual de Impostos sobre o Faturamento**. As análises são feitas utilizando o **Pandas** para manipulação de dados e **Plotly** para visualização interativa. Bem como usei o **FPDF** para gerar relatórios em PDF.

Além disso, os resultados são salvos em dois formatos: **CSV** e **XLSX** (Excel), facilitando o armazenamento e a análise posterior.

## Principais Métricas Calculadas

### 1. **Margem Operacional**
A **Margem Operacional** é um indicador financeiro crucial para avaliar a eficiência operacional de uma empresa. Essa métrica é obtida ao dividir o Lucro Operacional pela Receita Total e multiplicar o resultado por 100 para expressá-lo como uma porcentagem. Com a Margem Operacional, é possível entender quanto do faturamento está sendo convertido em lucro operacional, o que ajuda a identificar a saúde financeira da empresa.

**Fórmula**:
```text
Margem Operacional (%) = (Lucro Operacional / Faturamento Mensal) * 100
```

### 2. **Impostos proporcional ao Faturamento**
O **Percentual de Impostos sobre o Faturamento** é uma métrica que indica a carga tributária que uma empresa enfrenta em relação ao seu faturamento total. Essa métrica é importante para entender a eficiência fiscal da empresa e como os impostos impactam sua rentabilidade.
**Fórmula**:
```text
Percentual de Impostos (%) = (Impostos / Faturamento Mensal) * 100
```

### 3. **Rentabilidade**
A **Rentabilidade** é uma métrica que mede o retorno financeiro de um investimento ou de uma empresa em relação ao seu custo. Essa métrica é fundamental para avaliar a eficiência de uma empresa em gerar lucros a partir de seus ativos e investimentos. A Rentabilidade é calculada dividindo o Lucro Líquido pelo Patrimônio Líquido e multiplicando o resultado por 100 para expressá-lo como uma porcentagem.
**Fórmula**:
```text
Rentabilidade (%) = (Lucro Líquido / Patrimônio Líquido) * 100
```

## Explicação
O projeto consiste em um Jupyter Notebook que lê os dados financeiros de um arquivo CSV, realiza as análises e gera gráficos interativos. Os resultados são salvos em dois formatos: CSV e XLSX (Excel). Além disso, o projeto inclui a geração de um relatório em PDF com as principais métricas calculadas. Tratei os dados para garantir que as colunas de valores financeiros fossem convertidas corretamente para o tipo numérico, permitindo cálculos precisos. Depois, apliquei as fórmulas para calcular a Margem Operacional, o Percentual de Impostos e a Rentabilidade. Os gráficos interativos foram criados usando o Plotly, permitindo uma visualização clara e intuitiva dos dados. O relatório em PDF foi gerado usando a biblioteca FPDF, apresentando as principais métricas calculadas de forma organizada.


## Tecnologias Utilizadas
- Python
- Pandas
- Plotly
- FPDF
- CSV
- XLSX
- Jupyter Notebook



