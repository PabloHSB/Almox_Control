# 📦 Almox Control

Sistema de gerenciamento de almoxarifado desenvolvido para automatizar e rastrear o fluxo de requisição, separação e baixa de materiais no chão de fábrica. 

Este projeto nasceu da necessidade real de substituir processos logísticos manuais (papel e caneta) por uma arquitetura de dados eficiente, garantindo integridade de estoque e agilidade na operação.

## 🚀 O Problema Resolvido
Antes do sistema, o controle de estoque sofria com gargalos na comunicação entre operação e almoxarifado, além do risco de falhas humanas na atualização de saldos. O **Almox Control** atua como uma ponte automatizada, validando o estoque em tempo real e exigindo aprovações antes de qualquer movimentação física.

## 🛠️ Tecnologias 

**Fase 1 (Atual - MVP de Produção):** 
* Microsoft Forms (Coleta de Dados e Interface)
* Power Automate (Pipeline de Dados e Orquestração)
* SharePoint (Banco de Dados Relacional)
* Microsoft Teams via Adaptive Cards (Interface de Aprovação e Notificação)

**Fase 2 (Evolução Planejada):** 
* Front-end: React / Glide Apps
* Back-end: Python (FastAPI)
* Banco de Dados: PostgreSQL
* Integração: ERP Corporativo

## ⚙️ Funcionalidades

- [x] Consulta e validação de estoque em tempo real.
- [x] Lógica condicional de movimentação (Retirada Expressa vs. Solicitação).
- [x] Aprovação de separação via Cartões Adaptáveis no Teams.
- [x] Atualização autônoma de banco de dados.
- [ ] Solicitação de múltiplos itens simultâneos (Carrinho).
- [ ] Dashboard gerencial de consumo e histórico de movimentações.
- [ ] Controle de ponto de pedido e alertas automatizados de estoque mínimo.

## 📂 Estrutura do Projeto

*   `/documentos`: Documentação de requisitos, regras de negócio e fluxos.
*   `/banco de dados`: Modelagem relacional e scripts SQL de estruturação.
*   `/diagramas`: Arquitetura do sistema e mapeamento do fluxo de dados.

---
*Desenvolvido com foco em Engenharia de Dados, Automação Corporativa e Otimização Logística.*
