📊 Dashboard Analítico – Registros, Portes e Ocorrências de Armas no Brasil

Este projeto consiste na construção de um dashboard analítico em Power BI com foco na análise de registros de armas, portes, requerimentos e ocorrências no Brasil, utilizando dados em arquivos CSV.

O objetivo é fornecer uma visão estratégica, interativa e visualmente profissional, permitindo análises temporais, geográficas e operacionais para apoio à tomada de decisão.

🎯 Objetivo do Projeto

Desenvolver um painel interativo que permita:

Monitorar o volume de registros, portes, ocorrências e requerimentos;

Analisar a taxa de aprovação de requerimentos;

Identificar padrões por UF, sexo, tipo de arma e tipo de ocorrência;

Visualizar a evolução mensal dos dados;

Suportar decisões com base em indicadores claros e comparativos.

🧠 Estrutura do Projeto

O dashboard foi estruturado em 3 páginas principais:

✅ 1. Visão Geral

Visão macro dos dados:

Total de Registros

Total de Portes

Total de Ocorrências

Taxa de Aprovação de Requerimentos

Evolução mensal dos requerimentos

Mapa por UF

Top UFs por ocorrências

Distribuição por sexo

✅ 2. Análises Detalhadas

Foco em aprofundamento analítico:

Análise por tipo de requerimento

Deferidos x Indeferidos

Categorias de armas

Análise por perfil

Comparações entre grupos

✅ 3. Ocorrências

Foco operacional:

Evolução mensal das ocorrências

Distribuição por tipo de ocorrência

Volume por canal e segmento

🔄 Processo ETL
1. Extração

Importação de arquivos CSV diretamente no Power BI.

2. Transformação

Tratamento no Power Query:

Padronização de datas;

Ajuste de tipos de dados (texto, números e datas);

Remoção de valores nulos;

Criação de colunas auxiliares:

Ano

Mês

UF

Tipo de ocorrência

Categoria da arma

Sexo

Status do registro

Decisão do requerimento

Criação de uma Dimensão de Tempo (DimData) para permitir análises temporais corretas.

3. Carga

Relacionamentos modelados entre:

Registros

Portes

Ocorrências

Requerimentos

Dimensão de Tempo

Dimensão Geográfica (UF)

📐 Modelagem de Dados

Modelagem em formato estrela, garantindo:

Melhor desempenho das consultas;

Facilidade na criação de medidas em DAX;

Consistência nos filtros e segmentações.

📏 Principais Métricas Criadas (DAX)

Total de Registros

Total de Portes

Total de Ocorrências

Total de Requerimentos

Requerimentos Deferidos

Requerimentos Indeferidos

Taxa de Aprovação (%)

Percentual Masculino x Feminino

Top UFs por Ocorrências

Evolução Mensal de Requerimentos

Distribuição por Categoria de Arma

Todas as métricas foram desenvolvidas em DAX, respeitando contexto de filtro e relacionamento entre tabelas.

🎨 Design e Storytelling

O layout foi desenvolvido com foco em:

Hierarquia visual dos KPIs

Leitura rápida dos indicadores

Navegação intuitiva

Storytelling com dados

Foram utilizados:

Cartões de KPI

Gráficos de linha

Gráficos de barras

Gráficos segmentados

Mapas geográficos

Tabelas analíticas

🧭 Interatividade

Segmentação por:

Ano

UF

Tipo de ocorrência

Categoria da arma

Sexo

Drill-through entre páginas

Navegação por botões laterais

Filtros dinâmicos por página

🛠️ Ferramentas Utilizadas

Power BI Desktop

DAX (Data Analysis Expressions)

Power Query

Modelagem Dimensional

Arquivos CSV

📂 Organização do Repositório
📁 dados/        → Arquivos CSV utilizados  
📁 dashboard/    → Arquivo .pbix  
📁 imagens/      → Prints do dashboard  
📄 README.md     → Documentação do projeto  

✅ Status do Projeto

✔️ Concluído
✔️ Modelado
✔️ Dashboards Finalizados
✔️ Documentação Completa

👤 Autor

Thaynan Rodrigues
Cientista e Analista de Dados | Power BI | Python | SQL
