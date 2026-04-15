---
titulo: Progresso
disciplina: Compliance, QA and Tests
professor: Gustavo Molina Figueiredo
tags: [qa, progresso, fiap]
temas: [testes-unitarios, integracao, e2e, lgpd, compliance, ci-cd, sprints]
vinculado: "[[00_painel_geral]]"
ultima_atualizacao: 2025-01-01
---

# 📈 Progresso — QA & Compliance

---

## 🎯 Objetivo da Disciplina

> [!quote] O que quero dominar ao final do semestre
> 

---

## 📊 Progresso por Aula

| #  | Data  | Conteúdo | Entendimento     | Revisado? |
| -- | ----- | -------- | ---------------- | --------- |
| 01 | DD/MM |          | 😕 🤔 😊 🔥     | ⬜         |
| 02 | DD/MM |          | 😕 🤔 😊 🔥     | ⬜         |
| 03 | DD/MM |          | 😕 🤔 😊 🔥     | ⬜         |
| 04 | DD/MM |          | 😕 🤔 😊 🔥     | ⬜         |
| 05 | DD/MM |          | 😕 🤔 😊 🔥     | ⬜         |
| 06 | DD/MM |          | 😕 🤔 😊 🔥     | ⬜         |
| 07 | DD/MM |          | 😕 🤔 😊 🔥     | ⬜         |
| 08 | DD/MM |          | 😕 🤔 😊 🔥     | ⬜         |
| 09 | DD/MM |          | 😕 🤔 😊 🔥     | ⬜         |
| 10 | DD/MM |          | 😕 🤔 😊 🔥     | ⬜         |

> 😕 Não entendi · 🤔 Parcialmente · 😊 Entendi bem · 🔥 Domino

---

## 🏃 Progresso das Sprints

| Sprint    | Período       | Status | Cobertura | Bugs abertos | Bugs resolvidos |
| --------- | ------------- | ------ | --------- | ------------ | --------------- |
| Sprint 01 | DD/MM → DD/MM | ⬜      | __%       | 0            | 0               |
| Sprint 02 | DD/MM → DD/MM | ⬜      | __%       | 0            | 0               |
| Sprint 03 | DD/MM → DD/MM | ⬜      | __%       | 0            | 0               |

> ⬜ Não iniciada · 🟡 Em andamento · ✅ Concluída

---

## 📊 Cobertura de Testes (Projeto)

| Camada      | Meta    | Atual | Status |
| ----------- | ------- | ----- | ------ |
| Unitários   | ≥ 80%   | __%   | ⬜      |
| Integração  | ≥ 60%   | __%   | ⬜      |
| E2E         | Fluxos críticos |   | ⬜      |

---

## ✅ Checklist de Tópicos da Disciplina

**Testes**
- [ ] Testes unitários com JUnit 5
- [ ] Mocks com Mockito
- [ ] Testes de integração com Spring Test
- [ ] Testcontainers
- [ ] Testes E2E
- [ ] TDD na prática
- [ ] Métricas de cobertura

**CI/CD**
- [ ] Pipeline básico (GitHub Actions / Jenkins)
- [ ] Execução automática de testes no pipeline
- [ ] Análise estática (SonarQube)
- [ ] Deploy automatizado

**Compliance & LGPD**
- [ ] Fundamentos da LGPD
- [ ] Dados pessoais vs dados sensíveis
- [ ] Direitos do titular
- [ ] Impacto no desenvolvimento de software
- [ ] Boas práticas de compliance em APIs

---

## 📝 Avaliações

| Avaliação       | Tipo                        | Data  | Peso | Nota | Status |
| --------------- | --------------------------- | ----- | ---- | ---- | ------ |
| AV1             | Prova / Trabalho / Projeto  | DD/MM |      | —    | ⬜      |
| AV2             | Prova / Trabalho / Projeto  | DD/MM |      | —    | ⬜      |
| AV3             | Prova / Trabalho / Projeto  | DD/MM |      | —    | ⬜      |
| **Média final** | —                           | —     | —    | —    | —      |

---

## 🏆 Tópicos Dominados

- 

## ⚠️ Tópicos para Reforçar

- → ver [[qa_duvidas]]

---

## 🔗 Links rápidos

| Arquivo               | Link              |
| --------------------- | ----------------- |
| Materiais & Anotações | [[qa_materiais]]  |
| Exercícios & Sprints  | [[qa_exercicios]] |
| Dúvidas & Respostas   | [[qa_duvidas]]    |
| Painel geral          | [[00_painel_geral]] |

---

> [!example]- Dataview — Resumo das sprints
> ```dataview
> TABLE periodo, status, cobertura, bugs_abertos, bugs_resolvidos
> FROM "FIAP/QA"
> WHERE tipo = "sprint"
> SORT file.name ASC
> ```

> [!example]- Dataview — Dúvidas em aberto
> ```dataview
> TABLE origem, proximo_passo
> FROM "FIAP/QA"
> WHERE tipo = "duvida" AND status = "aberta"
> SORT file.mtime DESC
> ```

> [!example]- Dataview — Entregas com prazo
> ```dataview
> TABLE prazo, status, nota
> FROM "FIAP/QA"
> WHERE tipo = "entrega"
> SORT prazo ASC
> ```
