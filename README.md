# Dashboard de Acidentes de Trânsito — Porto Alegre

## Visão Geral
Este projeto apresenta um dashboard analítico desenvolvido no Microsoft Power BI com foco na análise de acidentes de trânsito na Região Metropolitana de Porto Alegre, permitindo identificar padrões temporais, tipos mais recorrentes de ocorrência, gravidade dos acidentes e tendências ao longo dos anos.

O objetivo principal foi transformar dados brutos em informações estratégicas para apoiar interpretação estatística, tomada de decisão e identificação de fatores críticos relacionados à segurança viária.

---

## Objetivos do Projeto
- Analisar o volume total de acidentes registrados
- Identificar tendências anuais e mensais
- Verificar dias da semana com maior incidência
- Avaliar distribuição por turno (dia/noite)
- Classificar tipos de acidentes mais frequentes
- Examinar consequências por nível de gravidade

---

## Principais Indicadores (KPIs)
- **Total de Acidentes**
- **Média de Acidentes por Dia**
- **Ano com Maior Número de Ocorrências**
- **Distribuição por Dia da Semana**
- **Distribuição por Mês**
- **Percentual por Turno**
- **Consequências (Ferimentos leves, graves e fatais)**
- **Top 4 Tipos de Acidentes**

---

## Principais Insights Identificados
- 2023 apresentou o maior volume de acidentes da série analisada
- Sexta-feira concentrou a maior incidência de ocorrências
- O período diurno representa a maior parte dos acidentes
- Abalroamento e colisão estão entre os tipos mais recorrentes
- Há variações sazonais relevantes entre os meses

---

## Ferramentas Utilizadas
- **Microsoft Power BI**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **CSV**
- **Modelagem de Dados**

---

## Estrutura Analítica
### Transformações realizadas:
- Padronização e limpeza de dados
- Criação de calendário temporal
- Agrupamento por:
  - Ano
  - Mês
  - Dia da semana
  - Turno
  - Tipo de acidente

### Medidas DAX:
- Total de acidentes
- Média diária
- Percentual por categoria
- Variação anual
- Ranking Top N

---

## Decisões Técnicas
- Utilização de medidas DAX para garantir dinamismo nos filtros
- Aplicação de Top N para destacar categorias mais relevantes
- Uso de ALLSELECTED para percentuais contextuais
- Organização visual orientada à leitura executiva
- Separação entre indicadores absolutos e relativos para evitar distorções analíticas

---

## Estrutura do Repositório
```txt
dashboard-acidentes-powerbi/
│── dashboard.pbix
│── dados.csv
│── images/
│   ├── dashboard-geral.png
│── README.md
