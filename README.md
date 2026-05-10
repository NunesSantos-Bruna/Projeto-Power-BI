README – AC1
People Analytics – Visão Geral de RH

Arquivo: README.md
Entrega: Avaliação Continuada 1 (AC1)


📌 Descrição do Projeto
Este projeto tem como objetivo desenvolver uma solução de People Analytics utilizando Business Intelligence (BI) para análise de dados de Recursos Humanos. A aplicação tem como foco apoiar a tomada de decisão estratégica por meio da visualização e análise de indicadores relacionados ao quadro de colaboradores da empresa.
Nesta primeira etapa (AC1), foi desenvolvida a visão geral de RH (People Overview), apresentando os principais indicadores e a estrutura atual da força de trabalho.

🏗 Arquitetura do Projeto
O projeto segue o conceito de arquitetura em camadas, conforme proposto na disciplina:
🧱 Camada de Dados

Dataset de Recursos Humanos em formato CSV
Dados públicos e fictícios
Informações demográficas, organizacionais e de status dos colaboradores

⚙️ Camada de Processamento / Negócio

Tratamento e modelagem dos dados via Power Query
Regras de negócio e métricas implementadas em DAX
Indicadores calculados dinamicamente

📊 Camada de Apresentação

Dashboard interativo desenvolvido no Power BI
Visualizações que permitem exploração e filtragem dos dados


📊 Funcionalidades Desenvolvidas – AC1
✔ Headcount total (total de colaboradores)
✔ Quantidade de funcionários ativos
✔ Quantidade de funcionários desligados
✔ Distribuição de colaboradores por departamento
✔ Distribuição de colaboradores por cargo (Job Role)
✔ Filtros interativos por departamento e gênero
Essas funcionalidades compõem a primeira entrega do projeto, garantindo uma visão geral clara da estrutura organizacional.

📈 Indicadores Implementados (KPIs)

Headcount Total
Funcionários Ativos
Funcionários Desligados

As métricas foram implementadas utilizando DAX, garantindo consistência e atualização dinâmica conforme a interação do usuário com os filtros.

🖱 Interatividade
O dashboard conta com segmentações de dados (slicers) que permitem filtrar os indicadores e gráficos por:

Departamento
Gênero

Essa funcionalidade possibilita análises exploratórias e personalizadas, atendendo aos requisitos de funcionalidade incremental exigidos na disciplina.

📂 Estrutura do Repositório
people-analytics/
│
├── dataset/
│   └── HR_Analytics.csv
│
├── powerbi/
│   └── people_analytics_ac1.pbix
│
├── docs/
│   └── dicionario_dados.md
│
└── README.md
