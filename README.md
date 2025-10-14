# 🧠 Assessor Virtual de Investimentos – QA & Testes Automatizados

Este repositório contém os artefatos de **validação de sistema** do projeto *Assessor Virtual de Investimentos*, incluindo:

- ✅ Casos de teste manuais (Azure Boards)
- 🧪 Coleções e mocks de API (Postman)
- 🔁 Scripts de automação e monitoramento de regressão
- 📊 Relatórios e evidências de teste

---

## 🔗 Links de Integração

- **Azure Boards:** [Acompanhar backlog e sprints](https://dev.azure.com/RM98237/Assessor%20Vitual%20de%20Investimentos)
- **Demo (YouTube):** [Apresentação da Sprint 3 - QA & Automação](https://youtube.com/watch?v=XXXXXXXXXXX)

---

## 🧩 Estrutura

/docs           → Documentação dos testes e links de referência
/postman        → Coleções e ambientes mockados
/scripts        → Scripts de execução automatizada (Node.js / Newman)

---

## 🚀 Execução Automatizada

1. Instale o Newman:
   ```bash
   npm install -g newman

2.	Execute os testes do Postman:
    newman run ./postman/AssessorVirtualAPI.postman_collection.json \
  -e ./postman/AssessorVirtualAPI.postman_environment.json

    ---

## 📎 4. Conteúdo dos links

**`/docs/azure-boards-link.md`**
```markdown
# Azure Boards – Integração

🔗 [Acessar o board da sprint atual](https://dev.azure.com/RM98237/Assessor%20Vitual%20de%20Investimentos)

Contém:
- Backlog completo do projeto
- Epics, Features e PBIs vinculados aos Test Cases
- Status de execução de testes manuais e automação

# Vídeo Demo (Sprint 3)

🎥 [Assistir no YouTube](https://youtube.com/watch?v=XXXXXXXXXXX)

Nesta demo apresentamos:
- Automação de testes com Postman
- Execução via Mock Server
- Integração com Azure Boards
