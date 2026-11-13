<div align="center">

# Felipe Souza (`@FelipSza`)

### *Dissolvendo fricção operacional com engenharia de automação e forjando ferramentas que servem de alicerce para mundos maiores.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-1a1b26?style=for-the-badge&logo=linkedin&logoColor=7aa2f7)](#)
[![GitHub](https://img.shields.io/badge/GitHub-1a1b26?style=for-the-badge&logo=github&logoColor=c0caf5)](https://github.com/FelipSza)
[![Email](https://img.shields.io/badge/Contato-1a1b26?style=for-the-badge&logo=gmail&logoColor=f7768e)](#)

</div>

---

### ☕ Sobre Mim

Desenvolvedor focado em resolver gargalos reais na interseção entre **automação fiscal/auditoria tributária**, **arquiteturas tempo real** e **ferramentas criativas**. No dia a dia, transformo regras legais complexas e processos burocráticos em pipelines determinísticos e resilientes; fora dele, construo plataformas *self-hosted* para RPG, suítes autorais *offline-first* e exploro desenvolvimento de jogos.

- 🔭 **Foco atual:** Sistemas *server-authoritative* em tempo real, motores de regras determinísticos com versionamento legal, extensões Chromium MV3 e orquestração de LLMs locais.
- ☕ **Combustível:** Café especial coado na V60.

---

### 🛠️ Stack & Ecossistema

| Domínio | Tecnologias & Ferramentas |
| :--- | :--- |
| **Linguagens & Core** | `TypeScript` · `C#` · `Python` · `Dart` |
| **Backend & Tempo Real** | `Node.js (22+)` · `Fastify 5` · `Socket.IO` · `Express 5` · `Zod` · `Docker` |
| **Banco de Dados & ORMs** | `PostgreSQL (pgvector)` · `SQLite (node:sqlite / FFI)` · `Drizzle ORM` · `Prisma ORM` |
| **Frontend & Extensões** | `React 19` · `Vite` · `Flutter (Desktop/Mobile)` · `Chromium Extensions (Manifest V3)` |
| **IA & Automação** | `Ollama` · `Gemini API` · `RAG Estruturado` · `OCR / Tesseract` · `decimal.js` |
| **Qualidade & Testes** | `Vitest` · `Playwright (E2E)` · `CI/CD (GitHub Actions)` |
| **Game Dev & Design** | `Unity` · `Aseprite` · `Blender` |

---

### ⚙️ Engenharia Fiscal & Automação Corporativa

Sistemas projetados para auditoria tributária, conformidade SPED e automação *Human-in-the-Loop* de fluxos contábeis:

- **[FiscAI SCK](https://github.com/FelipSza)**
  Copiloto de auditoria fiscal de NFS-e que cruza documentos contra o ERP, avalia retenções na fonte (`IRRF`, `CSRF`, `INSS`, `ISS`) e preenche o portal SCK mantendo o analista no controle final.
  `TypeScript` `Fastify 5` `Postgres 17 + pgvector` `Drizzle ORM` `Chrome MV3` `Gemini API`
  - **Motor Determinístico & Precisão Financeira:** Catálogo de regras (`RN01–RN22`) isolado de I/O com aritmética via `decimal.js` (`numeric` no banco) e histórico imutável de vigência da legislação.
  - **IA com Privacidade Estrita:** Validação semântica de subitens da LC 116 via Gemini com pipeline de anonimização prévia (mascaramento automático de CNPJ/CPF, dados bancários e valores) e cache de auditoria.

- **[CND — Automação & Gestão Fiscal](https://github.com/FelipSza)**
  Plataforma completa para coleta autônoma de certidões e monitoramento de regularidade fiscal.
  `Express 5` `TypeScript` `Prisma` `PostgreSQL` `Docker` `Manifest V3`
  - **Extensão v2.1 (Manifest V3):** HUD assistente *in-page* com fluxo *Human-in-the-loop*, bypass de deadlocks e automação profunda nos portais **e-CAC** e **Receita Federal**.
  - **Data Pipeline:** Parsing inteligente de PDFs e exportação analítica nativa em `.xlsx` via SheetJS.

- **[EFD-FIXER](https://github.com/FelipSza)**
  Motor de saneamento, auditoria e conciliação para arquivos **SPED EFD-Contribuições**, com higienização estrita dos Blocos `0`, `C`, `F`, `M` e `1`, reconstrução exata do Bloco `9` para validação no PVA da RFB e conciliação de receitas monofásicas.
  `Python` `SPED` `Auditoria Fiscal`

- **[Extrator de Guias ISS & DCTFWeb](https://github.com/FelipSza)**
  Aplicação desktop para processamento em lote, leitura nativa de PDFs com fallback via OCR (`Tesseract`) e consolidação contábil estruturada.
  `Python` `OCR / Tesseract` `Desktop GUI`

---

### 🌌 Criação, Tempo Real & Game Dev

Plataformas autorais voltadas a RPG de mesa, escrita criativa e desenvolvimento de jogos:

- **[RPGWeaver](https://github.com/FelipSza/RPGWeaver)**
  Mesa virtual (VTT) auto-hospedada com regras agnósticas em JSON, Códice do mundo, sincronização de áudio/mapa em tempo real e estética OLED.
  `TypeScript` `React 19` `Fastify 5` `Socket.IO` `node:sqlite` `Docker` `Playwright`
  - **Arquitetura Server-Authoritative:** Névoa de guerra, tokens ocultos, blocos secretos do Códice e rolagens privadas (`/gr`) são filtrados no servidor por destinatário, impedindo vazamento de dados no cliente.
  - **Motor Agnóstico & Sem `eval`:** Parser próprio de fórmulas e dados (`4d6kh3`, `1d20adv`, explosivos) com editor visual de fichas, barra de ações estilo BG3 e iniciativa integrada.
  - **Confiabilidade & Performance:** Suíte com **198 testes automatizados** (Vitest + Playwright E2E em dois navegadores), backups diários via `VACUUM INTO` e acesso remoto seguro via Tailscale.

- **[LoreWeaver Studio](https://github.com/FelipSza/LoreWeaver-Studio)**
  Suíte multiplataforma para worldbuilding e escrita de ficção seriada com filosofia *Vault-First* & *Offline-First* (zero lock-in via Markdown + YAML Frontmatter).
  `Flutter` `Dart` `Ollama` `SQLite FFI` `Git`
  - **Núcleo de IA (`loreweaver-core`):** RAG semântico contextual sobre o códice da obra com respostas estritas em JSON Mode.
  - **Arquitetura Híbrida & UI:** Indexação relacional com SQLite FFI efêmero, sincronização Git nativa (CLI no Desktop + GitHub REST Tree API no Mobile), Design System *Minimalist OLED Void* (`#050507`) e wiki anti-spoiler.

- **[Tappy-Cat](https://github.com/FelipSza/Tappy-Cat)**
  Protótipo e laboratório focado em arquitetura de *game loop*, física 2D e gerenciamento de ciclo de vida de objetos em cena.
  `C#` `Unity`

---

<div align="center">
  <img height="175px" src="https://github-readme-stats.vercel.app/api?username=FelipSza&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1a1b26" alt="GitHub Stats" />
  <img height="175px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=FelipSza&layout=compact&theme=tokyonight&hide_border=true&bg_color=1a1b26" alt="Top Languages" />
</div>

---

<div align="center">
  <sub>Construindo soluções resilientes para o mundo real e explorando universos através do código.</sub>
</div>
