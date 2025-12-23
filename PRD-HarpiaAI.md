# PRD - Harpia AI
## Product Requirements Document

**Versão:** 1.0  
**Data:** Dezembro 2024  
**Autor:** Equipe Harpia AI  
**Status:** Em Desenvolvimento

---

## 1. Visão Geral do Produto

### 1.1 Resumo Executivo

**Harpia AI** é uma plataforma SaaS de **GEO (Generative Engine Optimization)** que ajuda marcas a monitorar, analisar e otimizar sua presença nas respostas de modelos de IA generativa como ChatGPT, Gemini, Claude e Perplexity.

### 1.2 Problema

A forma como consumidores descobrem marcas está mudando drasticamente:

- **67%** dos usuários de IA generativa usam LLMs para pesquisar produtos/serviços
- **Consultas de marca** estão migrando do Google para ChatGPT, Perplexity e similares
- Empresas **não têm visibilidade** sobre o que IAs dizem sobre suas marcas
- **Informações incorretas** em LLMs podem prejudicar reputação e vendas
- SEO tradicional **não funciona** para otimização em IA generativa

### 1.3 Solução

Harpia AI oferece uma plataforma completa para:

1. **Monitorar** menções da marca em múltiplos LLMs
2. **Analisar** sentimento e precisão das respostas
3. **Comparar** posicionamento com concorrentes
4. **Otimizar** conteúdo para melhorar citações em IA
5. **Proteger** a marca contra desinformação

### 1.4 Proposta de Valor Única

> "Seja a marca citada pelo ChatGPT, Gemini e Claude. Clientes agora recebem recomendações da IA, não do Google. Esteja nessas respostas."

---

## 2. Objetivos e Métricas de Sucesso

### 2.1 Objetivos de Negócio

| Objetivo | Meta Q1 | Meta Q2 | Meta Anual |
|----------|---------|---------|------------|
| Clientes Pagantes | 50 | 150 | 500 |
| MRR (Monthly Recurring Revenue) | R$ 50K | R$ 150K | R$ 500K |
| Churn Rate | < 5% | < 4% | < 3% |
| NPS | > 40 | > 50 | > 60 |

### 2.2 KPIs do Produto

| Métrica | Descrição | Meta |
|---------|-----------|------|
| Consultas Analisadas | Total de queries processadas por mês | 1M+ |
| Modelos Monitorados | Quantidade de LLMs suportados | 50+ |
| Precisão de Análise | Accuracy do sentiment analysis | 98% |
| Time to First Value | Tempo até primeiro insight | < 5 min |
| DAU/MAU Ratio | Engajamento de usuários | > 40% |

---

## 3. Personas e Usuários

### 3.1 Persona Primária: Marketing Manager

**Nome:** Carolina, 32 anos  
**Cargo:** Head de Marketing Digital  
**Empresa:** E-commerce de moda, 200 funcionários

**Dores:**
- Não sabe o que ChatGPT diz quando clientes perguntam sobre sua marca
- Concorrentes aparecem em recomendações de IA, ela não
- Não tem métricas de "Share of Voice" em IA

**Objetivos:**
- Garantir presença positiva em LLMs
- Monitorar menções da marca em tempo real
- Provar ROI de estratégias de GEO para diretoria

**Quote:**
> "Descobri que o ChatGPT estava recomendando nosso concorrente quando clientes perguntavam sobre nossa categoria. Precisamos mudar isso."

---

### 3.2 Persona Secundária: Brand Manager

**Nome:** Ricardo, 38 anos  
**Cargo:** Gerente de Marca  
**Empresa:** Multinacional de bens de consumo

**Dores:**
- Informações incorretas sobre produtos em LLMs
- Não consegue "corrigir" o que a IA diz
- Precisa de relatórios para stakeholders globais

**Objetivos:**
- Proteger reputação da marca em IA
- Relatórios executivos com insights acionáveis
- Benchmark contra concorrentes globais

---

### 3.3 Persona Terciária: SEO/Content Lead

**Nome:** Fernanda, 28 anos  
**Cargo:** Coordenadora de SEO e Conteúdo  
**Empresa:** Agência digital

**Dores:**
- Clientes perguntam sobre "SEO para IA" e ela não sabe responder
- Precisa de nova oferta de serviço para agência
- Falta de ferramentas específicas para GEO

**Objetivos:**
- Oferecer serviço de GEO para clientes
- Dashboards white-label para apresentar resultados
- Automatizar monitoramento multi-cliente

---

## 4. Funcionalidades do Produto

### 4.1 Módulos Core

#### 4.1.1 Dashboard Principal

**Descrição:** Visão consolidada da presença da marca em IA

**Funcionalidades:**
- [ ] Score de Visibilidade Geral (0-100)
- [ ] Gráfico de evolução temporal
- [ ] Top 5 queries onde a marca aparece
- [ ] Alertas recentes
- [ ] Comparativo com período anterior

**User Stories:**
- Como Marketing Manager, quero ver meu score de visibilidade em IA para entender minha posição atual
- Como usuário, quero ver tendências ao longo do tempo para medir progresso

---

#### 4.1.2 Monitoramento de Menções

**Descrição:** Tracking em tempo real de menções em LLMs

**Funcionalidades:**
- [ ] Consultas automáticas a ChatGPT, Gemini, Claude, Perplexity
- [ ] Análise de sentimento (positivo/neutro/negativo)
- [ ] Detecção de informações incorretas
- [ ] Histórico de respostas por query
- [ ] Filtros por modelo, data, sentimento

**Queries Monitoradas (exemplos):**
```
"Qual a melhor [categoria] no Brasil?"
"O que você sabe sobre [marca]?"
"Recomende [produto/serviço] para [caso de uso]"
"Compare [marca] com [concorrente]"
"[marca] é confiável?"
```

**User Stories:**
- Como Brand Manager, quero saber quando um LLM fornece informação incorreta sobre minha marca
- Como usuário, quero filtrar menções por sentimento para priorizar ações

---

#### 4.1.3 Análise Competitiva

**Descrição:** Benchmark de presença vs. concorrentes

**Funcionalidades:**
- [ ] Adicionar até N concorrentes (por plano)
- [ ] Share of Voice comparativo
- [ ] Queries onde concorrentes aparecem e você não
- [ ] Gap analysis de posicionamento
- [ ] Alertas de mudança de ranking

**User Stories:**
- Como Marketing Manager, quero saber em quais queries meus concorrentes aparecem para criar estratégia de conteúdo
- Como usuário, quero receber alerta quando um concorrente me ultrapassar em visibilidade

---

#### 4.1.4 Otimização e Recomendações

**Descrição:** Sugestões acionáveis para melhorar presença em IA

**Funcionalidades:**
- [ ] Análise de gaps de conteúdo
- [ ] Recomendações de tópicos para criar
- [ ] Sugestões de estruturação de conteúdo
- [ ] Checklist de otimização GEO
- [ ] Score de "AI-Readiness" do site

**Fatores de Otimização:**
- Structured Data (Schema.org)
- Autoridade de domínio
- Citações e menções externas
- Clareza e factualidade do conteúdo
- Atualizações recentes

**User Stories:**
- Como SEO Lead, quero saber quais conteúdos criar para aparecer em mais queries de IA
- Como usuário, quero um checklist prático do que otimizar no meu site

---

#### 4.1.5 Alertas e Notificações

**Descrição:** Sistema de alertas configurável

**Tipos de Alerta:**
- [ ] Menção negativa detectada
- [ ] Informação incorreta identificada
- [ ] Queda de visibilidade (> X%)
- [ ] Concorrente ultrapassou em query
- [ ] Nova query relevante identificada

**Canais:**
- [ ] Email
- [ ] Slack (Enterprise)
- [ ] Microsoft Teams (Enterprise)
- [ ] Webhook/API

---

#### 4.1.6 Relatórios

**Descrição:** Geração de relatórios automatizados

**Tipos:**
- [ ] Relatório semanal de performance
- [ ] Relatório mensal executivo
- [ ] Relatório de análise competitiva
- [ ] Relatório de correções necessárias

**Formatos:**
- [ ] PDF
- [ ] Excel/CSV
- [ ] Apresentação (PowerPoint/Google Slides)
- [ ] Dashboard interativo (link)

**Personalização:**
- [ ] Logo da empresa (white-label)
- [ ] Seleção de métricas
- [ ] Período customizado
- [ ] Agendamento automático

---

### 4.2 Módulos Avançados (Roadmap)

#### Fase 2 - Q2 2025
- [ ] API pública para integrações
- [ ] Integração com Google Analytics
- [ ] Suporte a mais idiomas (EN, ES)
- [ ] App mobile (iOS/Android)

#### Fase 3 - Q3 2025
- [ ] AI Content Generator (criar conteúdo otimizado)
- [ ] Integração com CMS (WordPress, etc.)
- [ ] Marketplace de integrações
- [ ] Ferramenta de correção automatizada

---

## 5. Arquitetura Técnica

### 5.1 Stack Tecnológico

| Camada | Tecnologia |
|--------|------------|
| Frontend | React, TypeScript, Tailwind CSS, Framer Motion |
| Backend | Supabase (PostgreSQL, Auth, Edge Functions) |
| AI/ML | Lovable AI Gateway (Gemini, GPT) |
| Monitoramento | Edge Functions com scheduling |
| Analytics | PostHog / Mixpanel |
| Infra | Lovable Cloud |

### 5.2 Diagrama de Arquitetura

```
┌─────────────────────────────────────────────────────────────┐
│                      HARPIA AI PLATFORM                      │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  ┌──────────────┐     ┌──────────────┐    ┌──────────────┐  │
│  │   Frontend   │────▶│  Supabase    │───▶│  LLM APIs    │  │
│  │   (React)    │     │  (Backend)   │    │  (External)  │  │
│  └──────────────┘     └──────────────┘    └──────────────┘  │
│         │                    │                    │          │
│         ▼                    ▼                    ▼          │
│  ┌──────────────┐     ┌──────────────┐    ┌──────────────┐  │
│  │   Auth UI    │     │  PostgreSQL  │    │   ChatGPT    │  │
│  │   Dashboard  │     │  Edge Funcs  │    │   Gemini     │  │
│  │   Reports    │     │  Storage     │    │   Claude     │  │
│  └──────────────┘     └──────────────┘    │   Perplexity │  │
│                                           └──────────────┘  │
└─────────────────────────────────────────────────────────────┘
```

### 5.3 Modelo de Dados (Principais Entidades)

```sql
-- Organizações/Empresas
organizations (
  id, name, plan, created_at
)

-- Marcas monitoradas
brands (
  id, org_id, name, domain, keywords[], created_at
)

-- Concorrentes
competitors (
  id, brand_id, name, domain
)

-- Consultas/Queries monitoradas
queries (
  id, brand_id, query_text, category, is_active
)

-- Resultados de monitoramento
mentions (
  id, query_id, llm_model, response_text, 
  sentiment, has_brand, accuracy_score,
  created_at
)

-- Alertas
alerts (
  id, org_id, type, message, is_read, created_at
)

-- Relatórios gerados
reports (
  id, org_id, type, period_start, period_end,
  file_url, created_at
)
```

---

## 6. Planos e Precificação

### 6.1 Estrutura de Planos

| Recurso | Starter | Professional | Enterprise |
|---------|---------|--------------|------------|
| **Preço** | R$ 497/mês | R$ 1.297/mês | Sob consulta |
| Marcas monitoradas | 3 | 10 | Ilimitado |
| Modelos de IA | 5 principais | Todos | Todos + custom |
| Queries por marca | 50 | 200 | Ilimitado |
| Concorrentes | - | 5 | Ilimitado |
| Relatórios | Semanais | Diários | Custom |
| Alertas | Email | Email + tempo real | + Slack/Teams |
| Suporte | Email | Prioritário | Dedicado |
| API | - | - | ✓ |
| White-label | - | - | ✓ |

### 6.2 Modelo de Conversão

```
Free Trial (14 dias) → Starter → Professional → Enterprise
        ↓
    Churn Recovery
   (Win-back email)
```

---

## 7. Roadmap de Desenvolvimento

### 7.1 MVP (Q1 2025) - 8 semanas

**Objetivo:** Produto funcional para early adopters

| Semana | Entrega |
|--------|---------|
| 1-2 | Setup técnico, Auth, Onboarding |
| 3-4 | Dashboard básico, Cadastro de marca |
| 5-6 | Engine de monitoramento (3 LLMs) |
| 7 | Sistema de alertas básico |
| 8 | Relatório semanal, Testes, Launch |

**Critérios de Sucesso MVP:**
- [ ] 20 empresas em beta fechado
- [ ] NPS > 30
- [ ] < 3 bugs críticos/semana

### 7.2 V1.0 (Q2 2025)

- Todos os LLMs principais
- Análise competitiva completa
- Recomendações de otimização
- Relatórios avançados

### 7.3 V2.0 (Q3-Q4 2025)

- API pública
- Integrações (Slack, GA, CMS)
- AI Content Generator
- Expansão internacional

---

## 8. Riscos e Mitigações

| Risco | Probabilidade | Impacto | Mitigação |
|-------|---------------|---------|-----------|
| APIs de LLMs mudam/bloqueiam | Alta | Alto | Múltiplos métodos de acesso, cache |
| Concorrentes estabelecidos | Média | Alto | Foco em mercado BR, nicho específico |
| Custo de API alto | Alta | Médio | Otimização de queries, caching |
| Churn alto | Média | Alto | Onboarding forte, CS proativo |
| Complexidade técnica | Média | Médio | MVP enxuto, iterações rápidas |

---

## 9. Métricas de Produto

### 9.1 Funil de Aquisição

```
Visitantes → Trial → Ativados → Pagantes → Retidos
   100%       30%      60%        40%       85%
```

### 9.2 Métricas de Engajamento

| Métrica | Definição | Meta |
|---------|-----------|------|
| Activation Rate | % que configura 1ª marca em 24h | > 60% |
| Feature Adoption | % usando cada feature | > 40% |
| Session Duration | Tempo médio por sessão | > 8 min |
| Return Rate | % voltando em 7 dias | > 50% |

### 9.3 Métricas de Negócio

| Métrica | Definição | Meta |
|---------|-----------|------|
| CAC | Custo de Aquisição de Cliente | < R$ 500 |
| LTV | Lifetime Value | > R$ 5.000 |
| LTV/CAC | Razão de eficiência | > 3x |
| Payback | Meses para recuperar CAC | < 6 meses |

---

## 10. Go-to-Market

### 10.1 Estratégia de Lançamento

**Fase 1 - Beta Fechado (4 semanas)**
- 20 empresas selecionadas
- Feedback intensivo
- Iterações rápidas

**Fase 2 - Lançamento Suave (4 semanas)**
- Abertura para lista de espera
- PR e conteúdo educativo
- Webinars de demonstração

**Fase 3 - Lançamento Público**
- Campanha de marketing full
- Parcerias com agências
- Programa de afiliados

### 10.2 Canais de Aquisição

| Canal | Estratégia | Budget % |
|-------|------------|----------|
| Content/SEO | Blog sobre GEO, guias | 30% |
| LinkedIn Ads | Targeting por cargo | 25% |
| Parcerias | Agências digitais | 20% |
| Eventos | Palestras, webinars | 15% |
| Indicação | Programa de referral | 10% |

---

## 11. Apêndices

### 11.1 Glossário

| Termo | Definição |
|-------|-----------|
| **GEO** | Generative Engine Optimization - otimização para IA generativa |
| **AIO** | AI Optimization - sinônimo de GEO |
| **LLM** | Large Language Model (ChatGPT, Gemini, etc.) |
| **Share of Voice** | % de menções vs. total do mercado |
| **Sentiment** | Análise de tom (positivo/negativo/neutro) |

### 11.2 Referências

- [State of AI Report 2024](https://www.stateof.ai/)
- [GEO: Generative Engine Optimization](https://arxiv.org/abs/2311.09735)
- [How AI Search is Changing Brand Discovery](https://www.mckinsey.com/)

### 11.3 Changelog do Documento

| Versão | Data | Autor | Mudanças |
|--------|------|-------|----------|
| 1.0 | Dez 2024 | Harpia Team | Versão inicial |

---

**Aprovações:**

| Papel | Nome | Data | Assinatura |
|-------|------|------|------------|
| Product Owner | | | |
| Tech Lead | | | |
| CEO | | | |

---

*Documento confidencial - Harpia AI © 2024*
