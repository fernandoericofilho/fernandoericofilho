# 👋 Olá, eu sou Fernando Medeiros

🚀 Backend Engineer especializado em Java, Spring Boot, Arquitetura de Software e IA Generativa.

Atuo no desenvolvimento de aplicações backend, integrações distribuídas, APIs REST, mensageria e soluções utilizando RAG (Retrieval-Augmented Generation), LLMs e arquiteturas multiagentes.

Além da atuação técnica, também participo ativamente da formação de desenvolvedores dentro do ambiente corporativo, conduzindo mentorias, treinamentos técnicos e iniciativas de capacitação voltadas para engenharia de software, arquitetura backend e IA Generativa.

Atualmente estou conduzindo treinamentos corporativos sobre:
- Spring AI
- LangChain4j
- RAG
- Multiagentes
- Guardrails
- Observabilidade para LLMs
- Engenharia de Contexto
- Arquitetura aplicada à IA Generativa

Também sou responsável por iniciativas de formação e mentoria técnica para desenvolvedores iniciantes através da **Tech Starter Academy**, projeto gratuito voltado para capacitação prática e preparação para o mercado de tecnologia.

📈 Na primeira turma da iniciativa, **3 desenvolvedores foram contratados após o treinamento**.

🚀 Atualmente estamos conduzindo a segunda turma e acompanhando os demais alunos com mentorias, direcionamento técnico, preparação para entrevistas, evolução de portfólio e apoio contínuo para acelerar a entrada no mercado.

---

# 🧠 Áreas de Atuação

- Backend Engineering
- APIs REST
- Microsserviços
- Arquitetura de Software
- Mensageria e Processamento Assíncrono
- Sistemas Distribuídos
- Event Driven Architecture
- IA Generativa
- RAG (Retrieval-Augmented Generation)
- Engenharia de Contexto
- Engenharia de Prompts
- Observabilidade
- Mentoria Técnica
- Formação de Desenvolvedores
- Treinamentos Corporativos

---

# 🛠️ Tecnologias

## Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

## Arquitetura & Integração
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-000000?style=for-the-badge&logo=apachekafka&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-005571?style=for-the-badge)

## Cloud & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

## Banco de Dados
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

## Observabilidade
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)

## IA Generativa
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-0A66C2?style=for-the-badge)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge)

---

# 🏫 Tech Starter Academy

Projeto gratuito voltado para formação de desenvolvedores iniciantes e preparação para o mercado de tecnologia.

## 🚀 O que trabalhamos

- Java
- Spring Boot
- APIs REST
- Git e Gitflow
- Banco de Dados
- SQL e Normalização
- Flyway
- Docker
- Kafka
- Kubernetes
- AWS
- Splunk
- Grafana
- Prometheus
- Arquitetura de Software
- Entrevistas Técnicas
- Soft Skills
- Organização de GitHub e LinkedIn

## 🎯 Objetivo

Capacitar desenvolvedores com:
- fundamentos sólidos
- prática orientada ao mercado
- projetos reais
- comunicação técnica
- preparação para entrevistas
- postura profissional

📚 As aulas acontecem todos os sábados.

🔗 LinkedIn da iniciativa:
https://www.linkedin.com/company/tech-starter-academy

---

# 📌 Projetos em Destaque

## Sobre o `base_project`

O `base_project` é um template didático e reutilizável pensado para bootcamps, exercícios em sala e projetos iniciais. Ele oferece uma arquitetura mínima pronta, convenções e um conjunto de "agents" (personas e prompts) para apoiar revisões de código, QA e práticas de ensino.

Principais características:

- Projeto Kotlin + Spring Boot com fluxo completo (Controller → DTO → Mapper → Service → Repository).
- Build com Gradle Wrapper (`./gradlew`) e script `bootstrap.sh` para execução rápida de testes e inicialização.
- Migrations com Flyway em `src/main/resources/db/migration` (ex.: `V1__create_greeting_record.sql`).
- Exemplo de persistência em H2 (pronto para trocar por PostgreSQL em ambientes reais).
- Diretório `agents/` com vários agentes/personas prontos para uso em exercícios e PRs.

Por que usar como template:

- Reduz tempo de setup: já inclui dependências, build e exemplos de boas práticas.
- Facilita padronização de exercícios e avaliações em turmas.
- Permite adicionar checklists e prompts customizados para automação de revisões.

Como começar rapidamente:

```bash
git clone <seu-repo>
cd base_project
./gradlew clean build       # compila e executa testes
./bootstrap.sh --run        # executa testes e inicia a aplicação (opcional)
```

## 🤖 springAiRag

Treinamento corporativo sobre IA Generativa aplicada para desenvolvedores.

Conteúdo envolvendo:
- Spring AI
- LangChain4j
- LiteLLM
- RAG
- pgvector
- Guardrails
- LangWatch
- Multiagentes
- Observabilidade
- Arquitetura corporativa para IA

Projeto criado para capacitação técnica de desenvolvedores em IA Generativa dentro do ambiente corporativo.

---

## 👨‍🏫 turma2

Projeto de formação técnica para novos desenvolvedores.

Conteúdo abordando:
- Git e Gitflow
- Banco de Dados
- Normalização
- Spring Boot
- DTOs
- Swagger/OpenAPI
- HATEOAS
- Arquitetura REST
- Boas práticas de engenharia
- Flyway
- Testes
- APIs REST

Projeto colaborativo com múltiplos desenvolvedores.

---

## 🚀 junior-dev-starter

Projeto criado para ajudar desenvolvedores iniciantes a se prepararem para entrevistas técnicas e entrada no mercado.

Foco em:
- Soft skills
- Hard skills
- GitHub
- LinkedIn
- Entrevistas técnicas
- Organização profissional
- Roadmaps de estudo
- Projetos práticos

---

## 📊 analysisreport

Sistema de análise de arquivos utilizando Spring Batch.

### Features
- Processamento de arquivos `.dat`
- Parsing de registros
- Geração de relatórios
- Processamento contínuo
- Arquitetura backend orientada a processamento

---

## 📬 poc-email

POC de microserviço para envio de emails utilizando:
- Spring Mail
- AWS SES
- RabbitMQ
- Docker
- PostgreSQL

---

## 🌍 trevally_challenge

Desafio internacional para processamento de CSV com arquitetura em camadas.

### Recursos
- Extração dinâmica de headers
- Persistência em MongoDB
- DTOs
- MapStruct
- Testes unitários
- Docker
- APIs REST

---

## 🔧 refactoring_interview

Projeto focado em refatoração e melhoria de código utilizando boas práticas de engenharia de software.

### Conceitos aplicados
- Clean Code
- Refatoração
- SOLID
- Enums
- Organização de responsabilidades
- Legibilidade e manutenibilidade

---

# 📚 Estudos e Conceitos

Também desenvolvo projetos voltados para:
- Clean Code
- Refatoração
- Richardson Maturity Model
- Arquitetura REST
- Design de APIs
- Observabilidade
- Engenharia de software
- Event Driven Architecture
- Engenharia de Contexto para IA
- Arquitetura Multiagente
- Escalabilidade backend

---

# 📈 Estatísticas GitHub

![GitHub Streak](https://streak-stats.demolab.com?user=fernandoericofilho&theme=tokyonight)

---

# 🌱 Atualmente estudando

- IA Generativa aplicada
- Arquitetura Multiagente
- Observabilidade para LLMs
- Engenharia de Contexto
- Sistemas Distribuídos
- Event Driven Architecture
- Agentes autônomos
- Engenharia de Plataforma para IA

---

# 🤝 Objetivo

Construir soluções escaláveis, compartilhar conhecimento e contribuir para a formação de desenvolvedores com fundamentos sólidos de engenharia de software, arquitetura moderna e IA aplicada.

---

# 📫 Contato

- GitHub: https://github.com/fernandoericofilho
- LinkedIn: https://www.linkedin.com/in/fernandoericofilho/
- Tech Starter Academy:
  https://www.linkedin.com/company/tech-starter-academy
