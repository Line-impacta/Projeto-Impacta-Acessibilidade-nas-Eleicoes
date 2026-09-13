# Acessibilidade nas Eleições - Estado de São Paulo

Projeto final focado na análise de dados oficiais do Tribunal Superior Eleitoral (TSE) para mapear a infraestrutura de acessibilidade nos locais de votação e o perfil do eleitorado com deficiência no estado de São Paulo.

**Aluna:** [SEU NOME AQUI]
**Board do Projeto (Trello):** [LINK DO SEU TRELLO AQUI]

## 🛠️ Arquitetura e Tecnologias (As 3 Camadas)
O projeto foi desenvolvido seguindo a estrutura exigida de 3 camadas voltadas para Business Intelligence (BI):
* **Banco de Dados:** SQLite (Armazenamento estruturado e relacional).
* **Back-end (ETL):** Extração, tratamento e carga de arquivos CSV oficiais do TSE via scripts SQL no DB Browser.
* **Front-end:** Power BI (Consumo direto do banco de dados e renderização de painéis interativos).

## 🚀 Funcionalidades por Entrega (ACs)

* **AC1: Visão Geral de Acessibilidade (Concluído)**
  * Criação da modelagem relacional (`eleitorado_local_votacao_2026_SP`).
  * Conexão do Power BI ao banco de dados SQLite.
  * Dashboard exibindo o total de seções, proporção de acessibilidade e o ranking dos 10 municípios com maior infraestrutura acessível.

* **AC2: Análise Demográfica de Deficiências (Planejado)**
  * Inclusão e relacionamento da tabela `perfil_eleitor_deficiencia_2026_SP`.
  * Cruzamento de dados de infraestrutura com os tipos de deficiência por município.

* **AC3: Identificação de Lacunas e Filtros Avançados (Planejado)**
  * Filtros interativos para destacar regiões com alta demanda e baixa infraestrutura.

* **Entrega Final: Mapa Geográfico Interativo (Planejado)**
  * Implementação de visualização espacial para análise regional completa.

## 📂 Como executar o projeto
1. O banco de dados estruturado encontra-se no arquivo `.db` (pode ser inspecionado via DB Browser for SQLite).
2. O dashboard interativo encontra-se no arquivo `.pbix` e requer o Microsoft Power BI Desktop para execução.
