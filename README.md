📦 Sistema de Gerenciamento de Pedidos – Sopraê Delivery

Projeto de Modelagem, Normalização e Implementação SQL

Este repositório contém todo o desenvolvimento do banco de dados do mini-mundo Sopraê Delivery, desde o DER até a implementação prática em SQL utilizando SQLiteStudio.


---

📘 Sobre o Projeto

O objetivo deste sistema é gerenciar pedidos, clientes, entregadores, produtos e todo o fluxo operacional do Sopraê Delivery.
O projeto inclui:

Minimundo completo

DER conceitual

Modelo lógico

Normalização (1FN, 2FN e 3FN)

Scripts SQL (DDL + DML)

Integração com ferramentas reais (SQLiteStudio)

Versionamento via GitHub



---

📂 Estrutura do Repositório

01_criacao_tabelas.sql
02_inserts.sql
03_selects.sql
04_updates.sql
05_deletes.sql
soprae_delivery.sqlite (opcional)
README.md


---

🛠 Tecnologias Utilizadas

SQLiteStudio

SQLite 3

SQL (DDL e DML)

Git & GitHub



---

🏗 Scripts do Projeto

✔ 01_criacao_tabelas.sql

Contém todas as estruturas do banco de dados, incluindo chaves primárias, estrangeiras e integridade.


---

✔ 02_inserts.sql

População inicial das principais tabelas.


---

✔ 03_selects.sql

Consultas utilizando WHERE, ORDER BY, LIMIT e JOIN.


---

✔ 04_updates.sql

Atualizações de dados com condições reais.


---

✔ 05_deletes.sql

Remoção segura de registros, respeitando integridade referencial.


---

▶ Como Executar no SQLiteStudio

1. Abra o banco (soprae_delivery.sqlite) ou crie um novo.


2. Pressione Ctrl + E para abrir o editor SQL.


3. Abra o script desejado em: Arquivo > Abrir.


4. Execute pelo botão verde ▶.


5. Execute na ordem:



01_criacao_tabelas.sql
02_inserts.sql
03_selects.sql
04_updates.sql
05_deletes.sql


---

📄 Observações Importantes

O banco está totalmente normalizado até 3FN.

Todos os scripts foram testados no SQLiteStudio.

O arquivo .sqlite pode ser incluído no repositório para facilitar a avaliação.



---

✨ Autora

Samira Moreira
Projeto desenvolvido para a disciplina de Modelagem de Banco de Dados.


---
