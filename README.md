## Tatame_Analytics

Este é um projeto desenvolvido para construir uma pipeline de dados profissional, automatizada e escalável para o Instituto Tatame do Bem.  
O fluxo conta com **Python (ETL)**, **Supabase/PostgreSQL** (Data Warehouse) e **Power BI (Dashboards)**, garantindo centralização, qualidade e confiabilidade das informações.

## Objetivo do Projeto

Criar uma arquitetura de dados que permita:

- Consolidar dados de diversas fontes (APIs, Access, Google Sheets, planilhas internas).
- Automatizar a coleta, limpeza e padronização dos dados.
- Armazenar tudo no Supabase com tabelas estruturadas e historização.
- Integrar o Power BI para dashboards atualizados e análises estratégicas.
- Padronizar processos e permitir reprodutibilidade por qualquer membro da equipe.

##  Arquitetura da Pipeline

[Fonte de Dados]
- API HYB (Lançamentos financeiros)
- Base Access (sistema de controle de doações)
- Google Sheets (vendas das lojinhas do tatame)
- Planilhas internas

[Python ETL]
- Extração automática
- Tratamento e padronização
- Geração de dados RAW e Processados

[Supabase / PostgreSQL]
- Data Warehouse
- Tabelas fato e dimensões
- Versionamento e históricos

[Power BI]
- Dashboards
- Relatórios financeiros
- Indicadores de desempenho


Este projeto está em andamento.
No momento, já concluí a etapa de:
- Extração de todas as fontes de dados
- Salvamento dos dados brutos

Agora seguirei com o tratamento dos dados e salvamento dois dados tratados para subir para o banco de dados de forma unificada e organizada.
