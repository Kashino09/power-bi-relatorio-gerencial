# 📊 Desafio Power BI — Relatório Gerencial de Vendas

## 📑 Índice
- Contexto
- Objetivos
- Fontes
- Construção do Relatório
- Arquivos
- Publicação
- Autor

# Contexto:
- Este projeto é a entrega do segundo desafio de Power BI da trilha de Analista de Dados da [DIO](https://www.dio.me/), com base no conteúdo ensinado no curso e nos dados de amostra disponibilizados no repositório original: [julianazanelatto/power_bi_analyst](https://github.com/julianazanelatto/power_bi_analyst).

# Objetivos:
- Construir um relatório mais elaborado que o desafio anterior, com estrutura definida e navegabilidade entre páginas;
- Usar segmentadores de dados (intervalo de datas) e botões com imagem associada;
- Usar indicadores e botões para alternar entre diferentes visuais sobre o mesmo assunto (Bookmarks);
- Criar uma segunda página do relatório;
- Publicar o relatório no Power BI Service.

# Fontes:
- Base de dados `financials`: [dataset do repositório original do desafio](https://github.com/julianazanelatto/power_bi_analyst/tree/main/dataset)
- Conteúdo de referência: módulos do curso de Power BI Analyst da DIO

# Construção do Relatório

**Página 1 — Relatório de Vendas**
- 5 cards de KPI: Total de Vendas, Unidades Vendidas, Descontos Totais, Total de Lucro, Custo de Mercadoria (COGS)
- Segmentador de intervalo de datas, com ícone associado
- Gráfico de área: Evolução de Vendas por Mês
- Vendas por Segmento, com botões para alternar entre Bar Chart e Pie Chart (Bookmarks)
- Vendas por Produto
- Vendas por País, com botões para alternar entre Treemap e Map Chart (Bookmarks)
- Botão de navegação para a Página 2

**Página 2 — Relatório de Lucro Detalhado**
- Segmentador de intervalo por Ano
- Árvore de decomposição: Lucro por Ano e País
- Radar: Lucro por Produto
- Treemap: Lucro por Segmento
- Cascata: Variação de Lucro por Trimestre
- Botão de navegação de volta para a Página 1

# Arquivos

| Arquivo | Descrição |
|---|---|
| `Power BI - Relatório Gerencial de Vendas.pbix` | Projeto completo do Power BI Desktop, com as 2 páginas |
| `Power BI - Relatório Gerencial de Vendas.pdf` | Exportação em PDF das 2 páginas do relatório |
| `Power BI - Relatório Gerencial de Vendas.pptx` | Suplemento em PowerPoint, com uma página do relatório por slide |

# Publicação
- Relatório publicado na Web (acesso público, sem necessidade de login): [Acessar relatório](https://app.powerbi.com/view?r=eyJrIjoiYjlhYjkzNzItMmE0My00YTQ4LWJkNTgtZDcxZGQ3MWY2YTgyIiwidCI6ImU1YmRjMjU4LTZlOWYtNDljNS1iMjYxLWM4MjVmZDM5OTNiYiJ9)

# Autor
- Kelwin Paschoal
