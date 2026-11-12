<h1 align="center">Fábio Vieira Gambarini</h1>

<p align="center">
  <strong>Desenvolvedor de soluções</strong><br />
  Aplicações · Automações · Integrações
</p>

<p align="center">
  Gosto de transformar problemas do dia a dia em ferramentas úteis — no trabalho e em projetos próprios.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vieirafabiog"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/vieirafabiog"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<p align="center">
  <a href="#sobre-mim">Sobre</a> ·
  <a href="#tecnologias">Tecnologias</a> ·
  <a href="#experiencia">Experiência</a> ·
  <a href="#projetos">Projetos</a> ·
  <a href="#certificacoes">Certificados</a> ·
  <a href="#estatisticas">GitHub</a>
</p>

---

<a id="sobre-mim"></a>
## 👋 Sobre mim

Trabalho como desenvolvedor de soluções na **Transportes Poloni S.A.**, criando aplicações, automações, integrações e relatórios para apoiar os processos internos.

Fora do trabalho, estou sempre aprendendo sobre programação, computação e sistemas. Também gosto de games — principalmente **Call of Duty** e **Delta Force** — e quero criar projetos open source que ajudem a resolver problemas reais. Se tiver uma ideia ou uma dor que gostaria de ver resolvida, pode me chamar.

<a id="tecnologias"></a>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Desenvolvimento_com_IA-412991?style=flat-square&logo=openai&logoColor=white" alt="Desenvolvimento com IA" />
  <img src="https://img.shields.io/badge/AppSheet-4285F4?style=flat-square&logo=google&logoColor=white" alt="AppSheet" />
  <img src="https://img.shields.io/badge/Power_Apps-742774?style=flat-square&logo=powerapps&logoColor=white" alt="Power Apps" />
  <img src="https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white" alt="Power Automate" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/APIs-005571?style=flat-square&logo=fastapi&logoColor=white" alt="APIs" />
  <img src="https://img.shields.io/badge/OutSystems%20(learning)-5C2D91?style=flat-square&logo=outsystems&logoColor=white" alt="OutSystems (em aprendizado)" />
</p>

---

<a id="experiencia"></a>
## 💼 Experiência

#### Transportes Poloni S.A. · jan. 2024–atual

| Período | Cargo e atividades |
| --- | --- |
| jun. 2025–atual | **Desenvolvedor de Soluções**<br />Crio aplicações internas, automatizo processos, integro sistemas e preparo relatórios. |
| abr. 2024–atual | **Analista de Dados** |
| abr. 2024–set. 2026 | **Controle de Médias de Consumo e Telemetria**<br />Acompanhava o consumo de diesel por motorista e rota, analisava anomalias e trabalhava com relatórios no Power BI. |
| jan. 2024–abr. 2024 | **Operador de Checklist e Rastreamento**<br />Atendia motoristas e trabalhava com sistemas de rastreamento. |

#### Experiências anteriores

| Período | Empresa e função |
| --- | --- |
| jan. 2023–jan. 2024 | **LT Motos Iconha** · Mecânico de Motos / Auxiliar de Escritório<br />Manutenção básica de motocicletas e motores monocilíndricos; apoio na identificação de problemas mecânicos e elétricos. |
| fev. 2021–jun. 2022 | **Transportadora Jolivan Ltda.** · Jovem Aprendiz<br />Organização de papeletas e contato com motoristas. |

---

<a id="projetos"></a>
## 🧩 Meus Projetos

### 🟠 [D1Sheet](https://github.com/vieirafabiog/D1Sheet) · OData v4 para Cloudflare D1

<p>
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare Workers" />
  <img src="https://img.shields.io/badge/Cloudflare_D1-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare D1" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/OData_v4-0078D4?style=flat-square" alt="OData v4" />
</p>

Conecta bancos **Cloudflare D1 (SQLite)** ao **AppSheet**, **Power BI**, **Excel** e outras ferramentas por meio de uma API OData v4.

<p align="center">
  <strong>AppSheet · Power BI · Excel</strong> &nbsp;→&nbsp;
  <strong>D1Sheet · Cloudflare Workers</strong> &nbsp;→&nbsp;
  <strong>Cloudflare D1</strong>
</p>

<table>
  <tr>
    <td width="50%" valign="top"><strong>O problema</strong><br />Ferramentas como AppSheet, Power BI e Excel precisam de uma API compatível para acessar os dados no D1.</td>
    <td width="50%" valign="top"><strong>A solução</strong><br />O D1Sheet expõe o banco como uma API OData v4, sem exigir que você mantenha um servidor próprio.</td>
  </tr>
</table>

<table>
  <tr>
    <td width="33%" valign="top"><strong>Esquema automático</strong><br />Gera metadados do banco em <code>/$metadata</code>.</td>
    <td width="33%" valign="top"><strong>Consultas OData</strong><br />Traduz filtros, seleção de campos, ordenação e paginação.</td>
    <td width="33%" valign="top"><strong>CRUD e segurança</strong><br />Suporta operações de leitura e escrita, Basic Auth e consultas parametrizadas contra SQL injection.</td>
  </tr>
</table>

**Stack:** TypeScript, Cloudflare Workers, Cloudflare D1 (SQLite) e OData v4.  
**Explore:** [Repositório](https://github.com/vieirafabiog/D1Sheet) · [Site Oficial](https://vieirafabiog.github.io/D1Sheet/)

---

### 🔗 [SheetVerse](https://github.com/vieirafabiog/SheetVerse) · AppSheet + Microsoft Dataverse

<p>
  <img src="https://img.shields.io/badge/Google_AppSheet-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google AppSheet" />
  <img src="https://img.shields.io/badge/Microsoft_Dataverse-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft Dataverse" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare Workers" />
  <img src="https://img.shields.io/badge/OData_v4-0078D4?style=flat-square" alt="OData v4" />
</p>

Um proxy serverless em **JavaScript + Cloudflare Workers** que faz a ponte entre o Google AppSheet e o Microsoft Dataverse.

<table>
  <tr>
    <td width="50%" valign="top"><strong>O problema</strong><br />A conexão exige autenticação OAuth 2.0 e o Dataverse pode retornar metadados extensos, o que complica a configuração no AppSheet.</td>
    <td width="50%" valign="top"><strong>A solução</strong><br />O SheetVerse intermedia a autenticação e filtra os metadados para apresentar apenas as tabelas e colunas necessárias.</td>
  </tr>
</table>

**Recursos:** OData v4, nomes personalizados para tabelas e colunas, cache de tokens e paginação.  
**Explore:** [Repositório no GitHub](https://github.com/vieirafabiog/SheetVerse)

---

### 🎓 Smart Guide · Treinamentos e documentação empresarial
*Em desenvolvimento · Repositório privado*

<table>
  <tr>
    <td width="50%" valign="top"><strong>O problema</strong><br />Documentos e treinamentos ficam espalhados em arquivos Word e PDF, difíceis de encontrar. Às vezes, o conhecimento depende de uma única pessoa.</td>
    <td width="50%" valign="top"><strong>A ideia</strong><br />Organizar conteúdos em uma plataforma interna, acessível pelo celular mesmo offline, com acompanhamento do progresso dos treinamentos.</td>
  </tr>
</table>

---

### 🧩 wApps · Construtor de aplicativos sem lock-in
*Em desenvolvimento · Repositório privado*

<table>
  <tr>
    <td width="50%" valign="top"><strong>O problema</strong><br />Soluções prontas nem sempre atendem necessidades específicas, e algumas ferramentas prendem os projetos à própria plataforma.</td>
    <td width="50%" valign="top"><strong>A ideia</strong><br />Criar um construtor open source que gere front-end e back-end exportáveis para desenvolver sistemas simples e profissionais, sem lock-in.</td>
  </tr>
</table>

---

<a id="certificacoes"></a>
## 📚 Certificados

<details>
  <summary><strong>Hashtag Treinamentos</strong> · 8 certificados</summary>
  <ul>
    <li><a href="https://portalhashtag.com/certificado-hashtag/1779490028209x875424027166070000">FlutterFlow Impressionador</a></li>
    <li><a href="https://portalhashtag.com/certificado-hashtag/1779355106000x104879945392992060">Make Impressionador</a></li>
    <li><a href="https://portalhashtag.com/certificado-hashtag/1779238438775x509192843241455600">Algoritmos e Lógicas de Programação</a></li>
    <li><a href="https://portalhashtag.com/certificado-hashtag/1779227683700x906737916056576000">APIs de Inteligência Artificial</a></li>
    <li><a href="https://portalhashtag.com/certificado-hashtag/1779147418659x249858138051298530">Supabase Impressionador</a></li>
    <li><a href="https://portalhashtag.com/certificado-hashtag/1778977729177x779956605764685800">Power Apps Impressionador</a></li>
    <li><a href="https://portalhashtag.com/certificado-hashtag/1778958421325x830352610897166300">Agentes de IA e N8N Impressionador</a></li>
    <li><a href="https://portalhashtag.com/certificado-hashtag/1778958238568x995471787079762000">Power Automate Impressionador</a></li>
  </ul>
</details>

<details>
  <summary><strong>Professor Otto - Treinamentos</strong> · 1 certificado</summary>
  <ul>
    <li><a href="https://www.ottoprofessor.com/verify/766264d172f291a4ec2896ebbd73d2315f06e2af">Acelera - SQL</a></li>
  </ul>
</details>

---

<a id="estatisticas"></a>
## 📊 Estatísticas

<p align="center">
  <img width="67%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=vieirafabiog&theme=tokyonight" alt="Resumo das estatísticas do GitHub" />
  <img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=vieirafabiog&theme=tokyonight" alt="Linguagens dos repositórios" />
</p>
