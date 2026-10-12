# Acessibilidade nas Eleicoes - Estado de Sao Paulo

Projeto final focado na analise de dados oficiais do Tribunal Superior Eleitoral (TSE) para mapear a infraestrutura de acessibilidade nos locais de votacao e o perfil do eleitorado com deficiencia no estado de Sao Paulo.

**Aluna:** Aline Tavares Fujihara.
**Board do Projeto (Trello):** https://trello.com/b/hZd4uiku/projeto-acessibilidade-nas-eleicoes.

## 🛠️ Arquitetura e Tecnologias (As 3 Camadas)
O projeto foi desenvolvido seguindo a estrutura exigida de 3 camadas voltadas para Business Intelligence (BI):
* **Banco de Dados:** SQLite (Armazenamento estruturado e relacional).
* **Back-end (ETL):** Extracao, tratamento e carga de arquivos CSV oficiais do TSE via scripts SQL no DB Browser.
* **Front-end:** Power BI (Consumo direto do banco de dados e renderizacao de paineis interativos).

## 🚀 Funcionalidades por Entrega (ACs)

* **📌 AC1: Visao Geral de Acessibilidade (Concluido)**
  * Criacao da modelagem relacional (eleitorado_local_votacao_2026_SP).
  * Conexao do Power BI ao banco de dados SQLite.
  * Dashboard exibindo o total de secoes, proporcao de acessibilidade e o ranking dos 10 municipios com maior infraestrutura acessivel.

* **📌 AC2: Analise Demografica de Deficiencias (Planejado)**
  * Inclusao e relacionamento da tabela perfil_eleitor_deficiencia_2026_SP.
  * Cruzamento de dados de infraestrutura com os tipos de deficiencia por municipio.

* **📌 AC3: Identificacao de Lacunas e Filtros Avancados (Planejado)**
  * Filtros interativos para destacar regioes com alta demanda e baixa infraestrutura.

* **📌 Entrega Final: Mapa Geografico Interativo (Planejado)**
  * Implementacao de visualizacao espacial para analise regional completa.

## 📂 Como executar o projeto
1. O banco de dados estruturado encontra-se no arquivo .db (pode ser inspecionado via DB Browser for SQLite).
2. O dashboard interativo encontra-se no arquivo .pbix e requer o Microsoft Power BI Desktop para execucao.
