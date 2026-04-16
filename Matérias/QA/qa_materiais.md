---
titulo: Materiais & Anotações
disciplina: Compliance, QA and Tests
professor: Gustavo Molina Figueiredo
tags: [qa, materiais, anotacoes, fiap]
vinculado: "[[qa_progresso]]"
ultima_atualizacao: 2025-01-01
---

# 📂 Materiais & Anotações — QA & Compliance

---

## 🗺️ Mapa de Tipos de Teste

| Tipo        | Escopo                  | Ferramenta principal          | Quando usar                              | Status no projeto |
| ----------- | ----------------------- | ----------------------------- | ---------------------------------------- | ----------------- |
| Unitário    | Método / Classe         | JUnit 5 + Mockito             | Isolar lógica sem dependências externas  |                   |
| Integração  | Módulos / Camadas / API | Spring Test / Testcontainers  | Testar comunicação entre componentes     |                   |
| E2E         | Fluxo completo          | Selenium / Cypress / RestAssured | Simular comportamento real do usuário  |                   |
| Performance | Carga / Stress          | JMeter / k6                   | Validar comportamento sob volume         |                   |
| Segurança   | Vulnerabilidades        | OWASP ZAP / Dependabot        | Antes de cada release                    |                   |
| Compliance  | LGPD / Normas internas  | Revisão manual + checklists   | Dados pessoais envolvidos                |                   |
| Regressão   | Funcionalidades antigas | Suite completa automatizada   | Após qualquer mudança em produção        |                   |

---

## 📖 Anotações por Aula

### Aula 01 — DD/MM — Título

> [!abstract] Resumo
> 

**Conceitos-chave:**
- 
- 

**Tipos de teste abordados:** Unitário / Integração / E2E / Performance / Segurança / Compliance

**Ferramentas mencionadas:** 

**Código / Exemplo:**

```java
// exemplo
```

**Conexão com sprint / projeto:** 

**Revisar:**
- [ ] 

---

### Aula 02 — DD/MM — Título

> [!abstract] Resumo
> 

**Conceitos-chave:**
- 
- 

**Tipos de teste abordados:** 

**Ferramentas mencionadas:** 

**Código / Exemplo:**

```java

```

**Conexão com sprint / projeto:** 

**Revisar:**
- [ ] 

---

### Aula 03 — DD/MM — Título

> [!abstract] Resumo
> 

**Conceitos-chave:**
- 

---

### Aula 04 — DD/MM — Título

> [!abstract] Resumo
> 

---

### Aula 05 — DD/MM — Título

> [!abstract] Resumo
> 

---

### Aula 06 — DD/MM — Título

> [!abstract] Resumo
> 

---

### Aula 07 — DD/MM — Título

> [!abstract] Resumo
> 

---

### Aula 08 — DD/MM — Título

> [!abstract] Resumo
> 

---

### Aula 09 — DD/MM — Título

> [!abstract] Resumo
> 

---

### Aula 10 — DD/MM — Título

> [!abstract] Resumo
> 

---

## 🔗 Recursos Externos

**Documentação oficial**
- [JUnit 5](https://junit.org/junit5/docs/current/user-guide/) — Guia completo de testes unitários em Java
- [Mockito](https://site.mockito.org/) — Criação de mocks em Java
- [Spring Testing](https://docs.spring.io/spring-framework/docs/current/reference/html/testing.html) — Testes de integração com Spring
- [LGPD — Lei 13.709/2018](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm) — Texto oficial da lei
- 

**Vídeos / Cursos**
- 

**Artigos**
- 

**Repositórios de referência**
- 

---

## 📦 Materiais do Professor

| Arquivo | Tipo              | Aula | Localização |
| ------- | ----------------- | ---- | ----------- |
|         | Slide / PDF / Código | 01 |             |
|         | Slide / PDF / Código | 02 |             |

---

## 🗒️ Glossário

| Termo              | Definição |
| ------------------ | --------- |
| **Unit Test**      | Testa uma unidade isolada (método/classe) sem dependências externas reais |
| **Integration Test** | Testa a comunicação entre módulos, camadas ou serviços |
| **E2E Test**       | Simula o fluxo completo do usuário de ponta a ponta |
| **Mock**           | Substituto controlado de uma dependência real usado em testes |
| **Stub**           | Versão simplificada de um componente que retorna respostas predefinidas |
| **Spy**            | Wrapper em torno de um objeto real que permite verificar interações |
| **Coverage**       | Percentual do código-fonte coberto por testes automatizados |
| **Assertion**      | Verificação explícita de que um resultado esperado foi atingido |
| **Test Suite**     | Conjunto organizado de casos de teste relacionados |
| **Test Case**      | Cenário individual com entrada, ação e resultado esperado definidos |
| **Regression**     | Teste que garante que mudanças não quebraram funcionalidades existentes |
| **Flaky Test**     | Teste que ora passa, ora falha sem mudança no código — deve ser corrigido |
| **TDD**            | Test-Driven Development — escrever o teste antes da implementação |
| **BDD**            | Behavior-Driven Development — testes escritos em linguagem de negócio (Gherkin) |
| **CI/CD**          | Pipeline de integração e entrega contínua — automatiza build, teste e deploy |
| **Pipeline**       | Sequência automatizada de etapas: build → test → análise → deploy |
| **LGPD**           | Lei Geral de Proteção de Dados (13.709/2018) — regula uso de dados pessoais no Brasil |
| **Compliance**     | Conformidade com leis, normas regulatórias e políticas internas |
| **DoD**            | Definition of Done — critérios acordados para considerar uma tarefa concluída |
| **DoR**            | Definition of Ready — critérios para uma tarefa entrar no sprint |
| **Sprint**         | Ciclo fixo de desenvolvimento (geralmente 1–4 semanas) com entregas definidas |
| **Backlog**        | Lista priorizada de tarefas / user stories a serem desenvolvidas |
| **Severidade**     | Impacto de um bug no sistema: Crítico / Alto / Médio / Baixo |
| **Testcontainers** | Biblioteca que sobe containers Docker reais durante testes de integração |
| **SonarQube**      | Ferramenta de análise estática de código — detecta bugs, code smells e vulnerabilidades |
| **OWASP**          | Open Web Application Security Project — referência para segurança em aplicações |
| **Dado Pessoal**   | Qualquer informação que identifique ou possa identificar uma pessoa natural (LGPD Art. 5°) |
| **Dado Sensível**  | Subconjunto de dados pessoais com proteção reforçada: saúde, biometria, religião etc. |

---

> [!example]- Dataview — Aulas com revisão pendente
> ```dataview
> TABLE aula, data, conteudo
> FROM "FIAP/QA"
> WHERE tipo = "aula" AND revisado = false
> SORT aula ASC
> ```
