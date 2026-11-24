<p align="left">
  <a href="../README.md">← Voltar ao perfil</a>
</p>

<h1 align="center">Portfólio de Soluções</h1>

<p align="center">
  <strong>Projetos próprios · Ferramentas · Automações · Cases</strong>
</p>

<p align="center">
  Um espaço para mostrar o que construo com um pouco mais de contexto: o problema real, como pensei a solução e o resultado funcionando.
</p>

<p align="center">
  <a href="#indice">Índice</a> ·
  <a href="#ferramentas-e-integracoes">Ferramentas & Integrações</a> ·
  <a href="#aplicacoes">Aplicações</a> ·
  <a href="#automacoes-e-cases">Automações & Cases</a>
</p>

---

<a id="indice"></a>
## 📌 Visão geral

| Item | Categoria | Stack | Resumo | Página |
| --- | --- | --- | --- | --- |
| **D1Sheet** | Integração · Open Source | TypeScript · Cloudflare Workers · D1 · OData v4 | Expõe bancos Cloudflare D1 como API OData v4 para conectar ao AppSheet, Power BI e Excel sem servidor dedicado. | [Ver detalhes →](./D1Sheet/README.md) |
| **SheetVerse** | Integração · Open Source | JavaScript · Cloudflare Workers · Dataverse · OData v4 | Proxy serverless que faz a ponte entre Google AppSheet e Microsoft Dataverse, simplificando OAuth 2.0 e filtrando metadados. | [Ver detalhes →](./SheetVerse/README.md) |
| **data-2-sql** | Ferramenta Web | TypeScript · SQL | Converte arquivos de dados em diferentes formatos para scripts SQL prontos para importar nos principais bancos. | [Repositório →](https://github.com/vieirafabiog/data2sql) |
| **Smart Guide** | Aplicação · Open Source | TypeScript · Fastify · Expo · PostgreSQL · Docker | Plataforma self-hosted de treinamentos e documentação operacional com acesso pelo celular (offline) e exportação em PDF. | [Ver detalhes →](./Smart%20Guide/README.md) |
| **papyrus** | Aplicação | *Em desenvolvimento* | Gestão eletrônica de documentos com múltiplos storages, metadados estruturados e busca avançada no conteúdo. | *Em breve* |
| **wApps** | Aplicação | *Em desenvolvimento* | Construtor de aplicativos que gera front-end e back-end exportáveis, sem prender o projeto à plataforma. | *Em breve* |

---

<a id="ferramentas-e-integracoes"></a>
## 🔌 Ferramentas & Integrações

### 🟠 [D1Sheet](./D1Sheet/README.md) · Gateway OData v4 para Cloudflare D1

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare Workers" />
  <img src="https://img.shields.io/badge/Cloudflare_D1-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare D1" />
  <img src="https://img.shields.io/badge/OData_v4-0078D4?style=flat-square" alt="OData v4" />
</p>

Ponte serverless entre o **Cloudflare D1 (SQLite)** e ferramentas que falam OData — como Google AppSheet, Power BI e Excel. Lê o esquema do banco automaticamente, traduz filtros para SQLite parametrizado e suporta CRUD completo na edge.

**Acesse:** [Página do projeto](./D1Sheet/README.md) · [Repositório](https://github.com/vieirafabiog/D1Sheet) · [Site e simulador](https://vieirafabiog.github.io/D1Sheet/)

---

### 🔗 [SheetVerse](./SheetVerse/README.md) · AppSheet + Microsoft Dataverse

<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Google_AppSheet-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google AppSheet" />
  <img src="https://img.shields.io/badge/Microsoft_Dataverse-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft Dataverse" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare Workers" />
  <img src="https://img.shields.io/badge/OData_v4-0078D4?style=flat-square" alt="OData v4" />
</p>

Proxy serverless em Cloudflare Workers que intermedeia a conexão entre o **Google AppSheet** e o **Microsoft Dataverse**, cuidando da autenticação OAuth 2.0 (com cache de tokens) e filtrando os metadados para expor só as tabelas e colunas que interessam, com nomes personalizados e paginação.

**Acesse:** [Página do projeto](./SheetVerse/README.md) · [Repositório](https://github.com/vieirafabiog/SheetVerse)

---

### 🔁 [data-2-sql](https://github.com/vieirafabiog/data2sql) · Conversor de dados para SQL

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/SQL-005571?style=flat-square" alt="SQL" />
</p>

Aplicação web criada para evitar trabalho manual na hora de migrar arquivos soltos para banco de dados: basta anexar os dados em diferentes formatos, ajustar os tipos das colunas e gerar o SQL pronto para importar nos principais bancos relacionais.

**Acesse:** [Repositório](https://github.com/vieirafabiog/data2sql) · [Site Oficial](https://data-2-sql.web.app/)

---

<a id="aplicacoes"></a>
## 📱 Aplicações

### 🎓 [Smart Guide](./Smart%20Guide/README.md) · Treinamentos e documentação empresarial
*Em desenvolvimento*

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white" alt="Fastify" />
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo" />
  <img src="https://img.shields.io/badge/PostgreSQL_17-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL 17" />
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker Compose" />
</p>

Plataforma self-hosted para centralizar procedimentos, manuais e treinamentos passo a passo — rodando via Docker Compose com app mobile (pareamento por QR Code e estudo offline), exportação em PDF e storage plugável (Local, S3, Azure ou SharePoint).

**Acesse:** [Página do projeto](./Smart%20Guide/README.md) · [Repositório](https://github.com/vieirafabiog/SmartGuide)

---

### 📃 papyrus · Gestão Eletrônica de Documentos
*Em desenvolvimento · página do portfólio em preparação*

Organiza documentos em uma plataforma centralizada conectada a múltiplos storages, armazenando metadados estruturados junto aos arquivos e permitindo busca avançada direto no conteúdo dos documentos.

**Acesse:** [Repositório](https://github.com/vieirafabiog/papyrus)

---

### 🧩 wApps · Construtor de aplicativos sem lock-in
*Em desenvolvimento · repositório privado · página do portfólio em preparação*

Construtor voltado para criar sistemas internos simples e profissionais gerando código de front-end e back-end exportável, sem prender o projeto à ferramenta usada na criação.

---

<!--
<a id="automacoes-e-cases"></a>
## ⚙️ Automações & Cases de Trabalho

> *Em construção.*

Esta seção vai reunir fluxos, integrações e soluções desenvolvidas no dia a dia profissional (com dados sensíveis preservados), documentando o cenário antes da implementação, a arquitetura adotada e telas do funcionamento.

MODELO RÁPIDO PARA NOVOS ITENS
1. Crie uma pasta em Portifólio/<Nome-do-Item>/ com os prints e um README.md.
2. Adicione ou atualize a linha na tabela do #indice acima apontando para ./Nome-do-Item/README.md.
3. Atualize o título do projeto na categoria correspondente para linkar para ./Nome-do-Item/README.md:

### 🏷️ [Nome do Projeto](./Nome-do-Item/README.md) · Subtítulo curto

Resumo em 2 ou 3 linhas explicando o problema e o que foi construído.

**Acesse:** [Página do projeto](./Nome-do-Item/README.md)
-->
