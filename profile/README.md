<div align="center">

# Elizabete Fabri · Portfólio

**Desenvolvedora Frontend** · Angular · Arquitetura de Frontend · Micro Frontends

[![Portfólio](https://img.shields.io/badge/Portfólio-elizabetesousafabri.com.br-7c3aed?style=for-the-badge&logo=googlechrome&logoColor=white)](https://elizabetesousafabri.com.br)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-elizabetefabri-0A66C2?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NSAyMC40NWgtMy41NnYtNS41N2MwLTEuMzMtLjAyLTMuMDQtMS44NS0zLjA0LTEuODUgMC0yLjE0IDEuNDUtMi4xNCAyLjk0djUuNjdIOS4zNFY5aDMuNDF2MS41NmguMDVjLjQ4LS45IDEuNjQtMS44NSAzLjM3LTEuODUgMy42IDAgNC4yNyAyLjM3IDQuMjcgNS40NnY2LjI4ek01LjM0IDcuNDNhMi4wNiAyLjA2IDAgMSAxIDAtNC4xMyAyLjA2IDIuMDYgMCAwIDEgMCA0LjEzek03LjEyIDIwLjQ1SDMuNTZWOWgzLjU2djExLjQ1ek0yMi4yMiAwSDEuNzdDLjc5IDAgMCAuNzcgMCAxLjczdjIwLjU0QzAgMjMuMjMuNzkgMjQgMS43NyAyNGgyMC40NWMuOTggMCAxLjc4LS43NyAxLjc4LTEuNzNWMS43M0MyNCAuNzcgMjMuMiAwIDIyLjIyIDB6Ii8+PC9zdmc+)](https://www.linkedin.com/in/elizabetefabri)
[![GitHub](https://img.shields.io/badge/GitHub-elizabetefabri-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/elizabetefabri)

</div>

Esta organização reúne os **projetos do meu portfólio**: aplicações reais, com código aberto, documentação,
testes, CI e deploy. Cada repositório tem um `README` com contexto, decisões técnicas e como executar.

---

## ⭐ Em destaque: portfólio em Micro Frontends

[**mfe-elizabetefabri-portfolio**](https://github.com/elizfab/mfe-elizabetefabri-portfolio): o portfólio
construído como **monorepo Nx** com **Angular 22** e **Module Federation**. Um app host carrega em tempo de execução
micro frontends que são publicados de forma independente.

```
              ┌──────────── shell (host) ────────────┐
              │ layout · menu · home · mf.manifest   │
              └─────┬──────────────┬──────────────┬──┘
          runtime   │              │              │
            ┌───────▼───┐   ┌──────▼────┐   ┌─────▼─────┐
            │ projects  │   │  about    │   │ contact   │
            └───────────┘   └───────────┘   └───────────┘
                  deploys independentes · libs compartilhadas
```

## 📂 Projetos

| Projeto | O que é | Stack | Links |
| --- | --- | --- | --- |
| 🧩 **MFE Portfólio** | Portfólio em micro frontends: host + remotes carregados em runtime | Angular 22 · Nx · Module Federation · Vitest | [Repo](https://github.com/elizfab/mfe-elizabetefabri-portfolio) |
| 🩺 **Carteira de Saúde** | Carteira de vacinação e histórico de saúde com múltiplos perfis e impressão A4 | Angular · NgRx · ng-zorro-antd | [Demo](https://carterinha-vacinacao.vercel.app) · [Repo](https://github.com/elizfab/carteira-saude) |
| 💊 **Dose Certa** | Controle de medicação, exames e medidas de saúde, com lembretes por período do dia | Angular · PrimeNG · NgRx · Go · MongoDB | [Demo](https://dosescerta.vercel.app) · [Repo](https://github.com/elizfab/dosecerta) |
| 📓 **PDI** | Apresentação pública do Plano de Desenvolvimento Individual, com tema claro/escuro | Angular · Puppeteer | [Demo](https://pdi.elizabetesousafabri.com.br) · [Repo](https://github.com/elizfab/pdi) |
| 📚 **Caderno Inteligente** | Painel de estudos, projetos, quiz e culinária, com login e dashboard de progresso | Angular · PrimeNG · NgRx · Chart.js · Go · MongoDB | [Repo](https://github.com/elizfab/caderno-inteligente) |
| 🛒 **Suplementos Store** | E-commerce com vitrine, carrinho, favoritos e checkout, integrado a API própria | Angular · NgRx · PrimeNG · Go · MongoDB · Docker | Repositório privado |

## 🛠️ Stack

![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Nx](https://img.shields.io/badge/Nx-143055?style=flat-square&logo=nx&logoColor=white)
![NgRx](https://img.shields.io/badge/NgRx-BA2BD2?style=flat-square&logo=ngrx&logoColor=white)
![Sass](https://img.shields.io/badge/SCSS-CC6699?style=flat-square&logo=sass&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## 🔁 Como os projetos são desenvolvidos

- **Fluxo Git:** `feature/<atividade>` → `develop` → `main`, com branches protegidas.
- **PRs automáticos** a cada push de feature, com revisão automática via **Danger** (padrões de branch, título
  Conventional Commits, testes, dependências e regras de arquitetura).
- **CI** com lint, testes e build em todo push.
- **Documentação viva:** cada projeto tem roadmap, decisões técnicas e guia de execução.

---

<div align="center">

📫 Vamos conversar? [LinkedIn](https://www.linkedin.com/in/elizabetefabri) · [Portfólio](https://elizabetesousafabri.com.br)

</div>
