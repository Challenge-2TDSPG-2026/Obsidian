---
titulo: Dúvidas & Respostas
disciplina: Compliance, QA and Tests
professor: Gustavo Molina Figueiredo
tags: [qa, duvidas, fiap]
vinculado: "[[qa_progresso]]"
ultima_atualizacao: 2025-01-01
---

# ❓ Dúvidas & Respostas — QA & Compliance

> [!info] Como usar
> - Registre a dúvida assim que surgir
> - Marque a origem: **Aula · Exercício · Sprint · Estudo próprio**
> - Tente responder com pesquisa antes de levar ao professor
> - Quando resolver, mova o bloco para **Dúvidas Resolvidas** e preencha a resposta

---

## 🟡 Dúvidas em aberto

> [!question] Título da dúvida
> **Origem:** Aula 0X / Exercício 0X / Sprint 0X / Estudo próprio
> **Contexto:**
>
> **O que já tentei:**
>
> **Próximo passo:** Pesquisar / Perguntar ao professor / Testar / Abrir issue

---

## 🐛 Dúvidas sobre Bugs / Falhas em Testes

> [!bug] Título do bug / comportamento inesperado
> **Sprint / Componente:**
> **Tipo de teste:** Unitário / Integração / E2E / Manual
>
> **Comportamento esperado:**
>
> **Comportamento atual:**
>
> **Hipótese:**
>
> **Status:** Em investigação / Resolvido / Aceito como comportamento

---

## ✅ Dúvidas Resolvidas

> [!success] Título da dúvida
> **Resposta:**
>
> **Fonte:**
>
> **Aula / Sprint relacionada:**

---

## 💬 Perguntas preparadas para o professor

- 
- 

---

## 📚 Fontes que ajudaram

| Recurso | O que esclareceu | Link |
| ------- | ---------------- | ---- |
|         |                  |      |

---

> [!example]- Dataview — Todas as dúvidas em aberto do vault QA
> ```dataview
> TABLE origem, proximo_passo
> FROM "FIAP/QA"
> WHERE tipo = "duvida" AND status = "aberta"
> SORT file.mtime DESC
> ```
