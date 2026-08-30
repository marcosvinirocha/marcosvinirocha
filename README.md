<div align="center">

<a href="https://portifolio-page-flax.vercel.app/">
  <img src="https://raw.githubusercontent.com/marcosvinirocha/marcosvinirocha/master/banner.png" alt="Marcos Vinicius - Software Engineer" width="100%">
</a>

# 👋 Olá, eu sou Marcos Vinicius

### Frontend Engineer | Fullstack Developer

**React.js • Next.js • TypeScript • Node.js • Java • Spring Boot • Quarkus**

Construo produtos digitais com foco em **performance, arquitetura escalável, experiência do usuário e qualidade de código**.

Minha atuação combina engenharia de frontend com visão de backend, conectando **interface, APIs, dados, infraestrutura e entrega contínua** para transformar requisitos de produto em soluções sustentáveis.

<br>

<a href="https://portifolio-page-flax.vercel.app/">
<img src="https://img.shields.io/badge/🌐_PORTFÓLIO-000000?style=for-the-badge" />
</a>
<a href="https://www.linkedin.com/in/marcosoliveirarocha">
<img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:marcosvinicius.udia1256@gmail.com">
<img src="https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

</div>

---

## 🧑‍💻 Sobre mim

Sou **Software Engineer com foco em Frontend**, atuando principalmente com **React, Next.js, TypeScript e JavaScript**.

Tenho experiência na construção e evolução de aplicações web, trabalhando com **arquitetura frontend, Web Performance, Design Systems, APIs REST, testes automatizados e CI/CD**.

Também atuo no backend com **Node.js, Java, Spring Boot e Quarkus**, além de bancos relacionais e NoSQL.

Meu foco é construir software que equilibre:

**Produto + Experiência + Performance + Arquitetura + Qualidade**

Gosto de entender o problema de ponta a ponta — desde o componente renderizado no navegador até a API, banco de dados e infraestrutura que sustentam a aplicação.

---

# 🧠 Core Engineering

### ⚡ Performance

Transformo performance em uma preocupação de arquitetura, não apenas em uma etapa final.

```text
Code Splitting
      ↓
Lazy Loading
      ↓
Bundle Optimization
      ↓
SSR / Rendering Strategy
      ↓
Core Web Vitals
```

Em projetos profissionais, já trabalhei em iniciativas de otimização que reduziram o tempo de carregamento em **30%** através de estratégias de carregamento e otimização de bundles.

---

### 🏗️ Arquitetura Frontend

Construo interfaces pensando além do componente individual.

**Componentização · Design Systems · Modularidade · State Management · SSR · Micro-frontends**

Objetivo:

> permitir que a aplicação cresça sem transformar o código em uma estrutura difícil de evoluir.

---

### 🧪 Qualidade

Qualidade não é apenas escrever código que funciona.

Trabalho com:

**Jest · Vitest · Cypress · Playwright · TypeScript · Code Review · Clean Code**

Estratégia:

```text
Code
 ↓
Type Safety
 ↓
Unit Tests
 ↓
Integration Tests
 ↓
E2E
 ↓
CI
```

---

### 🚀 Entrega

Software precisa chegar ao usuário de forma previsível.

**Git · GitHub Actions · Docker · CI/CD · Automated Testing**

Pipeline ideal:

```text
Push
 ↓
Lint
 ↓
Type Check
 ↓
Tests
 ↓
Build
 ↓
Deploy
```

---

# 🛠️ Tech Stack

## Frontend

<p>
<img src="https://skillicons.dev/icons?i=react,nextjs,vue,ts,js,tailwind,vite" />
</p>

**React.js · Next.js · Vue.js · TypeScript · JavaScript · Tailwind CSS · Vite**

## Backend

<p>
<img src="https://skillicons.dev/icons?i=nodejs,express,java,spring,quarkus" />
</p>

**Node.js · Express · Java · Spring Boot · Quarkus · REST APIs**

## Databases

<p>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,sqlite" />
</p>

**PostgreSQL · MySQL · MongoDB · SQLite**

## DevOps & Cloud

<p>
<img src="https://skillicons.dev/icons?i=githubactions,docker,git,github,jenkins,aws,kubernetes" />
</p>

**Git · GitHub Actions · Docker · Jenkins · AWS · Kubernetes · CI/CD**

## Architecture & Engineering

**Microservices · Micro-frontends · Design Systems · SSR · Core Web Vitals · API Design · Observability · Clean Code**

---

# 🚀 Featured Projects

## 🤖 DevRoast

### AI-powered code analysis & developer tooling

Ferramenta criada para analisar código-fonte e gerar feedback técnico automatizado utilizando **AI Agents**.

### 🎯 Problema

Como automatizar parte de uma revisão técnica mantendo o feedback útil para quem desenvolve?

### 🧠 Decisão arquitetural

A aplicação separa as responsabilidades entre:

```text
┌──────────────┐
│    React     │
│   Frontend   │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│     tRPC     │
│ Type-safe API│
└──────┬───────┘
       │
       ├───────────────┐
       ▼               ▼
┌──────────────┐ ┌──────────────┐
│  AI Agents   │ │ Drizzle ORM  │
│ Code Analysis│ │ Data Layer   │
└──────────────┘ └──────┬───────┘
                        │
                        ▼
                    Database
```

### 🔍 Engineering Decisions

**tRPC**

Comunicação type-safe entre frontend e backend, reduzindo duplicação de contratos.

**Drizzle ORM**

Camada de persistência tipada mantendo controle sobre as operações de banco.

**AI Agents**

Isolamento da lógica de análise em uma camada própria para permitir evolução independente da interface.

### 💻 Stack

`React` `TypeScript` `tRPC` `Drizzle ORM` `AI Agents`

---

# 🏭 Smart Inventory

### Industrial inventory management

Sistema para controle de estoque e fluxo de materiais desenvolvido para trabalhar com grandes volumes de dados.

### 🎯 Problema

Como processar operações de inventário mantendo baixa latência e uma experiência de utilização consistente?

### 🧠 Decisão arquitetural

A API utiliza **Java + Quarkus**, priorizando baixo overhead e performance para operações de backend.

```text
Client
  │
  ▼
REST API
  │
  ▼
Quarkus
  │
  ▼
Business Rules
  │
  ▼
Data Layer
```

### 🔍 Engineering Decisions

**Quarkus**

Escolhido para construir uma API Java enxuta e orientada a performance.

**REST**

Contrato simples e desacoplado para comunicação entre clientes e backend.

**Backend-first thinking**

Regras de negócio e processamento foram mantidos no servidor, evitando sobrecarga desnecessária no frontend.

### 💻 Stack

`Java` `Quarkus` `REST APIs`

---

# 🎓 Freelah

### Learning platform

Plataforma de aprendizado focada na criação e consumo de trilhas personalizadas.

### 🎯 Problema

Criar uma experiência modular capaz de acompanhar o usuário durante diferentes etapas do processo de aprendizagem.

### 🧠 Decisão arquitetural

```text
┌──────────────┐
│    React     │
│  Components  │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│   REST API   │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│    Node.js   │
│   Express    │
└──────────────┘
```

### 🔍 Engineering Decisions

**Componentização**

Construção de componentes reutilizáveis para reduzir duplicação.

**REST API**

Separação entre camada de apresentação e regras de negócio.

**Responsive Design**

Interface adaptada a diferentes resoluções e contextos de utilização.

### 💻 Stack

`React` `Node.js` `Express` `Tailwind CSS`

---

# 🔬 Engineering Approach

Acredito que uma boa decisão de frontend precisa considerar o sistema inteiro.

Uma mudança aparentemente simples pode afetar:

```text
UX
 ↓
Rendering
 ↓
Performance
 ↓
API
 ↓
Database
 ↓
Infrastructure
 ↓
Cost
```

Por isso, gosto de analisar problemas considerando **trade-offs técnicos, impacto no produto e capacidade de evolução**.

Meu objetivo não é utilizar a tecnologia mais nova.

É utilizar a tecnologia adequada para o problema.

---

# 🤖 AI & Developer Productivity

Tenho interesse em **AI-assisted development** e ferramentas que aumentem a eficiência do ciclo de desenvolvimento.

Exploro aplicações de IA em:

* Code Analysis
* Refactoring
* Test Generation
* Developer Tooling
* Automation
* Documentation
* Software Quality

O objetivo é utilizar IA como **multiplicador de engenharia**, não como substituto de fundamentos técnicos.

---

# 📚 Atualmente explorando

**AI-assisted development**

**Web Performance**

**Design Systems**

**Frontend Architecture**

**Testing Strategies**

**Cloud & CI/CD**

**Application Security**

**Software Architecture**

---

# 📊 GitHub Activity

<div align="center">

<img height="180em" src="https://github-readme-stats-anuraghazra1.vercel.app/api?username=marcosvinirocha&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>

<img height="180em" src="https://github-readme-stats-anuraghazra1.vercel.app/api/top-langs/?username=marcosvinirocha&layout=compact&langs_count=7&theme=dracula"/>

</div>

### 👾 Contribution Graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/marcosvinirocha/marcosvinirocha/output/pacman-contribution-graph.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/marcosvinirocha/marcosvinirocha/output/pacman-contribution-graph.svg">
  <img alt="GitHub Contribution Graph" src="https://raw.githubusercontent.com/marcosvinirocha/marcosvinirocha/output/pacman-contribution-graph.svg">
</picture>

---

# 🎯 O que você encontrará aqui

Este perfil reúne projetos e experimentos relacionados a:

**Frontend Engineering**

**Fullstack Development**

**Web Performance**

**Software Architecture**

**AI-assisted Development**

**Testing**

**CI/CD**

**Developer Experience**

---

# 🌎 Vamos construir algo?

Estou aberto a oportunidades e projetos envolvendo:

### Frontend Engineering

`React` `Next.js` `TypeScript`

### Fullstack Development

`Node.js` `Java` `REST APIs`

### Engineering

`Performance` `Architecture` `Testing` `CI/CD`

<br>

<div align="center">

<a href="https://portifolio-page-flax.vercel.app/">
<img src="https://img.shields.io/badge/🌐_CONHEÇA_MEU_PORTFÓLIO-000000?style=for-the-badge" />
</a>

<a href="https://www.linkedin.com/in/marcosoliveirarocha">
<img src="https://img.shields.io/badge/💼_CONECTE--SE_NO_LINKEDIN-0A66C2?style=for-the-badge" />
</a>

</div>

<br>

<div align="center">

### ⛏️ Crafting better software, one commit at a time.

</div>
