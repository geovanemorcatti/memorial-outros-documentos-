## Fichamento de Conteúdo

O artigo *"Automatic Detection of Performance Bugs in Database Systems using Equivalent Queries"* apresenta o AMOEBA, uma técnica e ferramenta para detectar automaticamente bugs de desempenho em sistemas de gerenciamento de banco de dados (DBMSs). Em vez de focar apenas em bugs funcionais, o AMOEBA concentra-se em bugs que afetam negativamente o tempo de resposta do DBMS. A técnica funciona construindo pares de consultas semanticamente equivalentes e comparando seus tempos de resposta. A pesquisa revela que o AMOEBA descobriu 39 bugs potenciais em DBMSs amplamente utilizados, com 6 bugs confirmados e 5 corrigidos pelos desenvolvedores.

## Fichamento Bibliográfico

- Detecção automática de bugs de desempenho em sistemas de gerenciamento de banco de dados (DBMSs) usando consultas equivalentes.
- Técnica e ferramenta chamada AMOEBA.
- Avaliação do AMOEBA em DBMSs populares como PostgreSQL e CockroachDB.
- Construção de pares de consultas semanticamente equivalentes para comparação de tempos de resposta.
- Descoberta de 39 bugs potenciais, com 6 bugs confirmados e 5 corrigidos pelos desenvolvedores.

## Fichamento de Citações

- *"Because modern data-intensive applications rely heavily on database systems (DBMSs), developers extensively test these systems to eliminate bugs that negatively affect functionality."*
- *"To fill this gap, we present AMOEBA, a technique and tool for automatically detecting performance bugs in DBMSs."*
- *"The core idea behind AMOEBA is to construct semantically equivalent query pairs, run both queries on the DBMS under test, and compare their response time."*
- *"AMOEBA has so far discovered 39 potential performance bugs, among which developers have already confirmed 6 bugs and fixed 5 bugs."*
