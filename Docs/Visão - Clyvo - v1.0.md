# Visão - Clyvo Med - v1.0

> Preencha este documento antes de qualquer reunião técnica ou início de desenvolvimento.
> Deve ser aprovado por todos os membros e, se aplicável, pelo professor ou cliente.

---

## Identificação

| Campo | Informação |
|---|---|
| Nome do projeto | Clyvo Med |
| Data de início | 16/04/2026 |
| Data prevista de entrega | 16/08/2026 |
| Time | Arthur Brito, Pedro Brum e Felipe Flosi |
| Versão deste documento | v1.0 |

---

## O Problema

**Tutores de pets** que não acompanham a saúde dos animais preventivamente frequentemente **só buscam atendimento em situações de emergência**, resultando em diagnósticos tardios, mortes evitáveis e custos elevados — o atendimento emergencial representa 60% das utilizações dos planos de saúde pet, com custo médio de R$ 800,00 por evento.

**Evidências do problema:**

- Entrevistas realizadas com: 0 pessoas
- Dados / pesquisa: Briefing oficial Clyvo Vet (2026) — 60% das utilizações de planos são emergenciais; custo médio R$ 800,00/evento
- Experiência própria do time: —

---

## A Solução

**Clyvo Med** é uma plataforma digital de acompanhamento preventivo
para tutores de pets
que centraliza o perfil do animal, automatiza alertas de cuidados e oferece orientação inteligente por IA — reduzindo emergências e promovendo uma relação contínua entre tutor, clínica e hospital.

---

## Público-Alvo

| Perfil | Característica principal | Dor principal |
|---|---|---|
| Tutor de pet (primário) | Dono de animal doméstico, pouco engajado com prevenção | Só busca atendimento em crises; não sabe quando agir |
| Médico veterinário / Clínica (secundário) | Profissional sobrecarregado com burocracia administrativa | Perde tempo com tarefas manuais; baixa recorrência de pacientes |

---

## Proposta de Valor e Diferenciais

| Alternativa atual | Por que não resolve bem |
|---|---|
| Consultas avulsas / pronto-socorro | Reativas, caras e sem histórico centralizado |
| Lembretes manuais no celular | Não personalizados, sem contexto do pet, fácil de ignorar |
| Apps genéricos de pets | Não integram IA, clínica e histórico clínico num só lugar |

**Nosso diferencial:**
A plataforma combina cadastro inteligente do pet (perfil vivo que evolui com o tempo), IA de orientação por imagem e contexto, jornada preventiva automatizada por raça/fase de vida e histórico clínico centralizado — conectando tutor, clínica e hospital num único ecossistema.

---

## Escopo — O que está dentro

**Must Have (obrigatório para entregar)**

- RF01 — Cadastro completo do pet (nome, espécie, raça, idade, peso, histórico)
- RF02 — Histórico e linha do tempo de eventos clínicos
- RF03 — Jornada preventiva com alertas automáticos (vacinas, vermífugos, check-ups, banho/tosa)

**Should Have (importante, mas não bloqueia)**

- RF04 — IA de orientação: envio de foto + análise cruzada com dados do pet, retornando nível de atenção, possíveis causas e orientação prática
- RF05 — Alertas inteligentes baseados em raça e fase de vida

**Could Have (entra se sobrar tempo)**

- RF06 — Biblioteca de raças com características, cuidados, alimentação e problemas comuns
- RF07 — Tele-orientação: chat com veterinário para triagem e orientação rápida

---

## Fora do Escopo — O que NÃO será feito nesta versão

- Modelo 3D interativo de raças — alta complexidade técnica e baixo impacto no MVP
- Integração real com planos de saúde pet — depende de parcerias e APIs externas fora do alcance do projeto
- Gestão financeira / emissão de NF para clínicas — escopo da Clyvo Vet B2B, não do app do tutor

---

## Requisitos Não-Funcionais

- RNF01 — A IA de orientação deve utilizar API externa (ex: GPT-4o Vision ou Gemini) — não será treinado modelo próprio
- RNF02 — Dados pessoais de tutores e pets devem ser tratados em conformidade com a LGPD
- RNF03 — A interface deve ser responsiva e funcionar em dispositivos móveis (mobile-first)

---

## Critério de Sucesso

- Critério 1: O fluxo completo (cadastro → alerta → orientação por IA) foi demonstrado funcionando no MVP até 24/05/2026 (Sprint 1/2) 
- Critério 2: Pelo menos 3 perfis de pets distintos cadastrados e com histórico populado para a apresentação 
- Critério 3: A IA retorna orientação coerente (nível de atenção + causa + recomendação) para ao menos 5 cenários de teste

---

## Riscos Identificados

| Risco | Probabilidade | Impacto | Mitigação |
|---|---|---|---|
| API de IA com custo ou limite de uso | Média | Alto | Usar tier gratuito (Gemini Free / OpenAI trial); mockar respostas no MVP se necessário |
| Escopo grande para o prazo | Alta | Alto | Priorizar Must Haves; Should/Could entram só após RF01–RF03 prontos |
| Divisão desigual de tarefas no grupo | Média | Médio | Definir responsabilidades claras na seção abaixo e revisar semanalmente |
| Falta de dados reais de pets para teste | Baixa | Médio | Criar dados fictícios realistas para demonstração |

---

## Stack / Ferramentas / Recursos

| Categoria | Escolha | Justificativa |
|---|---|---|
| Prototipação | Figma | Gratuito, colaborativo, time já conhece |
| Frontend | A definir pelo grupo | — |
| Backend | Spring Boot (Java) / FastAPI (Python) | Familiaridade do time |
| IA / Visão | GPT-4o Vision ou Gemini | APIs prontas, sem necessidade de treinar modelo |
| Banco de dados | A definir | — |
| Gestão de tarefas | A definir | — |
| Documentação | Obsidian | Já em uso pelo time |

---

## Orçamento Estimado

| Item | Valor | Fonte |
|---|---|---|
| APIs de IA (tier gratuito) | R$ 0,00 | Recursos próprios |
| Hospedagem / deploy | R$ 0,00 | Free tier (Vercel, Railway, etc.) |
| **Total** | **R$ 0,00** | — |

---

## Divisão do Time

| Pessoa | Responsabilidade principal | Disponibilidade (h/semana) |
|---|---|---|
| Felipe Flosi | Backend / Arquitetura da API | — |
| Arthur Brito | A definir | — |
| Pedro Brum | A definir | — |

---

## Aprovação

| Nome | Confirmação | Data |
|---|---|---|
| Felipe Flosi | ☐ | — |
| Arthur Brito | ☐ | — |
| Pedro Brum | ☐ | — |

**Aprovado pelo professor/cliente:** — | **Data:** —