Dashboard COVID-19 — Análise Global com Plotly
Dashboard interativo com dados reais de COVID-19 da Our World in Data, analisando a evolução da pandemia por país e continente.
Perguntas respondidas

Quais países tiveram mais casos e mortes totais?
Como evoluíram os novos casos ao longo do tempo?
Qual continente teve a maior taxa de mortalidade?
Existe relação entre casos e mortes por habitante?

Tecnologias

Python 3.10+
pandas — limpeza e transformação dos dados
Plotly Express — gráficos interativos rápidos
Plotly Graph Objects — gráficos customizados
Plotly Subplots — layout com múltiplos gráficos

Como rodar
bashpip install pandas plotly

jupyter notebook notebook_covid_dashboard.ipynb

Não é necessário baixar nenhum dataset. Os dados são carregados automaticamente da internet.

Saídas geradas
ArquivoDescriçãodashboard_covid19.htmlDashboard completo navegável no browser
Gráficos incluídos

Mapa mundial com casos por milhão de habitantes
Top 15 países em casos e mortes (gráfico duplo)
Evolução temporal com média móvel de 7 dias
Taxa de mortalidade por continente (boxplot)
Scatter: casos vs. mortes com tamanho por população

Diferencial técnico

Média móvel de 7 dias para suavizar variações diárias
Escala logarítmica no scatter para visualizar países pequenos
Dashboard exportado como HTML único e compartilhável
Dados sempre atualizados (carregados direto da fonte)

Estrutura do projeto
dia2-covid-dashboard/
├── notebook_covid_dashboard.ipynb
├── dashboard_covid19.html    ← gerado ao rodar o notebook
└── README.md
Autor
Pedro Henri Gois da Silva — github.com/P-Hwe