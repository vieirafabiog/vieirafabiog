# Fábio Vieira Gambarini

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vieirafabiog)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vieirafabiog)

<p align="center">
  <a href="#sobre-mim">Sobre mim</a> ·
  <a href="#tecnologias">Tecnologias e Ferramentas</a> ·
  <a href="#experiencia">Experiência</a> ·
  <a href="#projetos">Meus Projetos</a> ·
  <a href="#certificacoes">Certificações e Cursos</a> ·
  <a href="#estatisticas">Estatísticas</a>
</p>

---

<a id="sobre-mim"></a>
### 👨‍💻 Sobre mim

Sou desenvolvedor de soluções na Transportes Poloni S.A., onde trabalho com aplicações, automações e integrações para facilitar processos internos. Também crio relatórios para análise de dados.

Fora do trabalho, estudo programação, computação e sistemas. Gosto de games, principalmente **Call of Duty** e **Delta Force**, e quero criar projetos open source que ajudem a resolver problemas reais. Se tiver uma ideia ou um problema que gostaria de ver resolvido, pode me chamar.

---

<a id="tecnologias"></a>
### 🛠️ Tecnologias e Ferramentas

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Desenvolvimento_com_IA-412991?style=flat-square&logo=openai&logoColor=white" alt="Desenvolvimento com IA" />
  <img src="https://img.shields.io/badge/AppSheet-4285F4?style=flat-square&logo=google&logoColor=white" alt="AppSheet" />
  <img src="https://img.shields.io/badge/Power_Apps-742774?style=flat-square&logo=powerapps&logoColor=white" alt="Power Apps" />
  <img src="https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white" alt="Power Automate" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/APIs-005571?style=flat-square&logo=fastapi&logoColor=white" alt="APIs" />
  <img src="https://img.shields.io/badge/OutSystems%20(learning)-5C2D91?style=flat-square&logo=outsystems&logoColor=white" alt="OutSystems (learning)" />
</p>

---

<a id="experiencia"></a>
### 💼 Experiência Profissional

#### Transportes Poloni S.A. · jan. 2024–atual

- **Desenvolvedor de Soluções** · jun. 2025–atual
  - Crio aplicações internas, automatizo processos, integro sistemas e preparo relatórios.
- **Analista de Dados** · abr. 2024–atual
- **Controle de Médias de Consumo e Telemetria** · abr. 2024–set. 2026
  - Acompanhava o consumo de diesel por motorista e rota, analisava anomalias e trabalhava com relatórios no Power BI.
- **Operador de Checklist e Rastreamento** · jan. 2024–abr. 2024
  - Atendia motoristas e trabalhava com sistemas de rastreamento.

#### LT Motos Iconha · jan. 2023–jan. 2024

- **Mecânico de Motos / Auxiliar de Escritório**
  - Fazia manutenção básica em motocicletas e motores monocilíndricos, além de ajudar a identificar problemas mecânicos e elétricos.

#### Transportadora Jolivan Ltda. · fev. 2021–jun. 2022

- **Jovem Aprendiz**
  - Organizava papeletas e mantinha contato com motoristas.

---

<a id="projetos"></a>
### 🗂️ Meus Projetos

#### 🗄️ [D1Sheet](https://github.com/vieirafabiog/D1Sheet) — Gateway OData v4 para Cloudflare D1

Ponte serverless construída em **TypeScript + Cloudflare Workers** que transforma qualquer banco **Cloudflare D1 (SQLite)** em uma API **OData v4** completa e segura para **Google AppSheet**, **Power BI**, **Excel** e ferramentas corporativas.

- **Problema enfrentado:** Ferramentas como AppSheet, Power BI e Excel precisam de uma API compatível para acessar dados do Cloudflare D1.
- **Como resolve:** O D1Sheet transforma o banco D1 em uma API OData v4, sem exigir servidores dedicados ou configuração de IPs e firewalls.
- **Destaques:** Introspecção dinâmica de esquema (`/$metadata` em EDMX XML), tradução segura de queries (`$filter`, `$select`, `$orderby`, `$top`, `$skip`, `@odata.nextLink`) 100% parametrizadas contra SQL Injection, CRUD completo (`GET`, `POST`, `PATCH`, `PUT`, `DELETE`) e Basic Auth em tempo constante.
- **Stack:** TypeScript, Cloudflare Workers, Cloudflare D1 (SQLite) e OData v4.
- 🔗 **Links:** [Repositório no GitHub](https://github.com/vieirafabiog/D1Sheet) • [Site do Projeto & Simulador Interativo](https://vieirafabiog.github.io/D1Sheet/)

---

#### 🔗 [SheetVerse](https://github.com/vieirafabiog/SheetVerse) — Proxy OData v4 para AppSheet e Microsoft Dataverse

Proxy serverless desenvolvido em **JavaScript + Cloudflare Workers** para conectar o **Google AppSheet** ao **Microsoft Dataverse**.

- **Problema enfrentado:** Conectar AppSheet ao Dataverse pode exigir lidar com autenticação OAuth 2.0 e com metadados extensos, dificultando a configuração e a sincronização.
- **Como resolve:** O SheetVerse intermedia a autenticação e filtra os metadados, apresentando ao AppSheet apenas as tabelas e colunas necessárias.
- **Destaques:** Compatibilidade com OData v4, esquema virtual com nomes personalizados, cache de tokens e tratamento de paginação.
- **Stack:** JavaScript, Cloudflare Workers, Google AppSheet, Microsoft Dataverse e OData v4.
- 🔗 **Repositório:** [GitHub](https://github.com/vieirafabiog/SheetVerse)

---

#### 🧩 wApps — Construtor de aplicativos sem lock-in
**Em desenvolvimento · Repositório privado**

- **Problema enfrentado:** Criar sistemas simples e profissionais para necessidades específicas que soluções prontas nem sempre atendem, sem ficar preso a uma plataforma.
- **Proposta:** Desenvolver um construtor open source que gere front-end e back-end exportáveis, permitindo criar sistemas personalizados e continuar usando o código fora da ferramenta.
- **Foco:** Liberdade para exportar e evoluir os projetos, sem lock-in.

---

<a id="certificacoes"></a>
### 📜 Certificações e Cursos

**Hashtag Treinamentos**
- [FlutterFlow Impressionador](https://portalhashtag.com/certificado-hashtag/1779490028209x875424027166070000)
- [Make Impressionador](https://portalhashtag.com/certificado-hashtag/1779355106000x104879945392992060)
- [Algoritmos e Lógicas de Programação](https://portalhashtag.com/certificado-hashtag/1779238438775x509192843241455600)
- [APIs de Inteligência Artificial](https://portalhashtag.com/certificado-hashtag/1779227683700x906737916056576000)
- [Supabase Impressionador](https://portalhashtag.com/certificado-hashtag/1779147418659x249858138051298530)
- [Power Apps Impressionador](https://portalhashtag.com/certificado-hashtag/1778977729177x779956605764685800)
- [Agentes de IA e N8N Impressionador](https://portalhashtag.com/certificado-hashtag/1778958421325x830352610897166300)
- [Power Automate Impressionador](https://portalhashtag.com/certificado-hashtag/1778958238568x995471787079762000)

**Professor Otto - Treinamentos**
- [Acelera - SQL](https://www.ottoprofessor.com/verify/766264d172f291a4ec2896ebbd73d2315f06e2af)

---

<a id="estatisticas"></a>
### 📊 Estatísticas no GitHub

<p align="left">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=vieirafabiog&theme=tokyonight" alt="Resumo das estatísticas do GitHub" height="165" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=vieirafabiog&theme=tokyonight" alt="Linguagens dos repositórios" height="165" />
</p>
