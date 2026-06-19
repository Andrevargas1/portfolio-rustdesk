# 📋 Portfólio de Produto — Substituição de Ferramentas de Acesso Remoto

> Case real de raciocínio de Product Owner aplicado a uma iniciativa de infraestrutura, documentado por **André Vargas** durante sua atuação como Analista de Suporte Pleno.

[![Status](https://img.shields.io/badge/status-aprovado%20para%20avalia%C3%A7%C3%A3o%20t%C3%A9cnica-blue)]()
[![Tipo](https://img.shields.io/badge/tipo-case%20corporativo-orange)]()

---

## 📖 Sobre este repositório

Este repositório documenta, em formato de **case de produto**, uma iniciativa real conduzida durante minha atuação como Analista de Suporte Pleno: a substituição de ferramentas pagas de acesso remoto (AnyDesk e TeamViewer) por uma solução open source auto-hospedada (RustDesk).

O objetivo aqui **não é apresentar código** — é demonstrar o raciocínio de produto aplicado: identificação de problema, elaboração de proposta, escrita de user stories, definição de critérios de aceite e priorização de backlog.

📄 **[Baixar o portfólio completo em PDF](./docs/Portfolio_RustDesk.pdf)**

---

## 🎯 O Problema

A equipe de suporte técnico utilizava AnyDesk e TeamViewer para acesso remoto às máquinas dos usuários. O modelo de licenciamento por usuário simultâneo gerava custo recorrente elevado, proporcional ao crescimento do time — com aproximadamente 40 colaboradores e necessidade de 10 acessos simultâneos.

## 💡 A Proposta

Implantação de um **servidor RustDesk auto-hospedado**, eliminando a dependência de licenciamento por usuário e trazendo controle total sobre os dados de sessão (relevante para conformidade com LGPD).

| | |
|---|---|
| **Produto** | Servidor RustDesk auto-hospedado para acesso remoto corporativo |
| **Usuários-alvo** | Equipe de suporte técnico (~40 colaboradores, 10 acessos simultâneos) |
| **Diferencial** | Open source, servidor próprio, sem custo por acesso simultâneo |
| **Objetivo de negócio** | Eliminar custos recorrentes de licenciamento |

## 📝 User Stories (resumo)

| ID | Como... | Quero... | Prioridade |
|---|---|---|---|
| US-01 | Analista de suporte | instalar o servidor RustDesk na infraestrutura da empresa | Alta |
| US-02 | Analista de suporte | autenticar no sistema com credenciais corporativas | Alta |
| US-03 | Analista de suporte | realizar acessos remotos simultâneos em até 10 máquinas | Alta |
| US-07 | Gestor de TI | garantir que os dados das sessões fiquem no servidor interno | Alta |
| US-08 | Analista de suporte | conectar em máquinas Windows, Linux e Mac | Média |

> User stories completas, critérios de aceite e backlog priorizado disponíveis no [PDF completo](./docs/Portfolio_RustDesk.pdf).

## ✅ Resultado

A proposta foi formalizada, apresentada à liderança e **aprovada para avaliação técnica**, demonstrando capacidade de identificar problemas operacionais, propor soluções orientadas a valor e estruturar a iniciativa em formato de produto (Vision Board, backlog, MVP).

---

## 🧠 Habilidades de produto demonstradas

- Identificação de problema real de custo operacional
- Pesquisa e avaliação de solução open source
- Elaboração de proposta técnica e de negócio
- Definição de MVP com menor risco e maior valor
- Comunicação com stakeholders e apresentação à liderança

---

## 👤 Sobre mim

**André Alberto Vargas do Rosário**
Analista de Suporte em transição para Produto | PSPO I em andamento

- 📧 andre.rosario.cccc@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/ACoAAB2YIaQBXNac5mVUaTpfiIa-LvsLpsK4GQ0)
- 📄 [Currículo completo](./docs/CV_Andre_Vargas.pdf)
- 🔗 Veja também: [Case Ghost — Sistema de Gestão de Atendimentos](https://github.com/Andrevargas1/portfolio-ghost)
