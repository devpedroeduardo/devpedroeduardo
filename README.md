<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
  <img alt="Pedro Eduardo, Desenvolvedor Full-Stack" src="./assets/banner-dark.svg" width="100%">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/devpedroeduardo/"><img src="https://img.shields.io/badge/LinkedIn-devpedroeduardo-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://my-portfolio-three-xi-90.vercel.app"><img src="https://img.shields.io/badge/Portf%C3%B3lio-online-111111?style=flat-square&logo=astro&logoColor=white" alt="Portfólio"></a>
  <a href="mailto:pedroedu77@gmail.com"><img src="https://img.shields.io/badge/E--mail-pedroedu77%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="E-mail"></a>
  <img src="https://img.shields.io/badge/Sobral--CE-Brasil-38B2AC?style=flat-square&logo=googlemaps&logoColor=white" alt="Sobral-CE, Brasil">
  <img src="https://img.shields.io/badge/status-aberto%20a%20oportunidades-2EA44F?style=flat-square" alt="Aberto a oportunidades">
</p>

---

### 👋 Sobre mim

Sou desenvolvedor full-stack e trabalho com **agentes de IA no dia a dia**: eles escrevem e revisam código comigo, e eu cuido do que não dá para delegar (escopo, arquitetura, revisão do diff, merge e produção).

Comecei na TI pelo suporte e pela rede. Como **Analista de TI em uma distribuidora**, sustentei o ERP **TOTVS WinThor**, escrevi consultas em **Oracle** e **MySQL** para relatórios de gestão e desenvolvi aplicações internas em **React** e **Node.js** ligando os dados do ERP às regras do negócio. Hoje faço sistemas web completos com **TypeScript, Next.js, NestJS e PostgreSQL**, para empregadores e clientes freelance.

- 🎓 Engenharia de Computação na **UFC** (conclusão prevista para 2027)
- 📚 Formação full-stack de **1.500 horas** pela **Trybe**
- 💼 Aberto a vagas de desenvolvimento e a projetos freelance

---

### 🤖 Desenvolvimento com IA

No [OTILC Store](https://github.com/devpedroeduardo/otilc-store), um e-commerce real com Pix, montei e coordeno um **time de agentes de IA** que trabalha por especificação:

| Papel | Quem | O que faz |
|---|---|---|
| Product Owner | eu | prioridade, escopo, revisão final, merge, produção e segredos |
| Orquestrador | Claude | transforma o pedido em spec, distribui e consolida |
| Devs | Claude Code | back-end, banco e segurança; front-end e docs |
| Revisor | Codex (OpenAI) | revisa todo PR em modo só leitura, de outro fornecedor que o autor |
| CI/CD | modelo leve | vigia o CI, faz a triagem de logs e levanta fatos do repositório |

- **Spec antes de código:** cada mudança nasce de uma spec com critérios de aceite ([37 até agora](https://github.com/devpedroeduardo/otilc-store/tree/main/specs)) e vira um PR revisado. São 50+ PRs mergeados.
- **Regras versionadas:** [`AGENTS.md`](https://github.com/devpedroeduardo/otilc-store/blob/main/AGENTS.md), papéis, roteamento e scorecard em [`docs/agents`](https://github.com/devpedroeduardo/otilc-store/tree/main/docs/agents). Quem executa e quem revisa cada tipo de tarefa se decide por evidência, não por impressão.
- **Rede de segurança:** CI com testes unitários, integração com Postgres real, E2E com Playwright, Semgrep, gitleaks e auditoria de dependências. Agente nenhum faz merge.
- **IA dentro do produto:** no [MyFinPocket](https://github.com/devpedroeduardo/my-finpocket), o Gemini lê a foto de um comprovante e preenche a transação, e gera uma análise dos gastos do mês.

---

### 🚀 Projetos em destaque

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🛒 <a href="https://github.com/devpedroeduardo/otilc-store">OTILC Store</a></h4>
      <p>E-commerce de uma marca de streetwear, feito para um cliente real. Monorepo com API, loja e painel administrativo.</p>
      <ul>
        <li>Estoque à prova de concorrência: 10 compras simultâneas da última peça, só uma passa</li>
        <li>Pix com Mercado Pago: webhook assinado e conciliação com <code>FOR UPDATE SKIP LOCKED</code></li>
        <li>Painel admin com login por cookie httpOnly e permissões por papel</li>
        <li>Construído com um time de agentes de IA, spec a spec</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS">
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>💰 <a href="https://github.com/devpedroeduardo/my-finpocket">MyFinPocket</a></h4>
      <p>Finanças pessoais instalável como app (PWA), com leitura de comprovantes por IA.</p>
      <ul>
        <li>Gemini preenche a transação a partir da foto da nota</li>
        <li>Row Level Security no Supabase e rotas protegidas por middleware</li>
        <li>Jest e Playwright rodando no CI a cada push</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase">
        <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini">
        <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright">
      </p>
      <p><a href="https://my-finpocket.vercel.app/"><b>Ver online »</b></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🏷️ <a href="https://github.com/devpedroeduardo/otilc-landing">OTILC Pré-venda</a></h4>
      <p>Vitrine que validou a marca antes da loja: site estático, sem build, pedidos pelo WhatsApp.</p>
      <ul>
        <li>Lighthouse 98 a 100</li>
        <li>Testes E2E e de acessibilidade</li>
      </ul>
      <p><a href="https://devpedroeduardo.github.io/otilc-landing/"><b>Ver online »</b></a></p>
    </td>
    <td width="50%" valign="top">
      <h4>🛠️ <a href="https://github.com/devpedroeduardo/neo-estech-project">NEO Estech</a></h4>
      <p>Desafio técnico de front-end: gestão de chamados operacionais.</p>
      <ul>
        <li>Next.js, Ant Design, React Query e Zod</li>
        <li>Testes com Vitest e Playwright</li>
      </ul>
      <p><a href="https://neo-estech-project.vercel.app/"><b>Ver online »</b></a></p>
    </td>
  </tr>
</table>

---

### 🛠️ Tecnologias

| Área | Ferramentas |
|---|---|
| **Front-end** | <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"> <img src="https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white" alt="Astro"> |
| **Back-end** | <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"> <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS"> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"> <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP"> <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel"> <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" alt="Zod"> |
| **Banco de dados** | <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"> <img src="https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black" alt="Drizzle ORM"> <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase"> <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" alt="Oracle"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL"> |
| **IA** | <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code"> <img src="https://img.shields.io/badge/Codex-000000?style=flat-square&logo=openai&logoColor=white" alt="Codex"> <img src="https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini API"> <img src="https://img.shields.io/badge/MCP-555555?style=flat-square" alt="MCP"> |
| **Testes** | <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright"> <img src="https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white" alt="Jest"> <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest"> <img src="https://img.shields.io/badge/Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white" alt="Testing Library"> |
| **DevOps e ferramentas** | <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"> <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel"> |
| **Sistemas** | <img src="https://img.shields.io/badge/TOTVS_WinThor-ERP-363636?style=flat-square" alt="TOTVS WinThor"> |

---

### 🗺️ Trajetória

| Período | |
|---|---|
| **2025 a 2026** | **Analista de TI** · Distribuidora Donizete: ERP WinThor, Oracle/MySQL, aplicações internas em React e Node.js |
| **2021 a 2022** | **Estagiário de TI e Redes** · Rações Golfinho: suporte, rede local e estações de trabalho |
| **2020 a 2021** | **Desenvolvimento Web Full-Stack** · Trybe, 1.500 horas |
| **2019 a hoje** | **Engenharia de Computação** · Universidade Federal do Ceará |

<p align="center"><sub>Vamos conversar? <a href="mailto:pedroedu77@gmail.com">pedroedu77@gmail.com</a> · <a href="https://www.linkedin.com/in/devpedroeduardo/">LinkedIn</a></sub></p>
