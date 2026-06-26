<div align="center">

# Antonio R. Faria Neto

**Engenharia de Controle e Automação · ADS · Infra & Security**

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/netodev404)
[![Email](https://img.shields.io/badge/-contato-black?style=flat&logo=gmail&logoColor=white)](mailto:seu@email.com)
![Mogi das Cruzes · SP](https://img.shields.io/badge/Mogi%20das%20Cruzes-SP-333?style=flat)

</div>

---

Estudante de **Engenharia de Controle e Automação** + **ADS**, com foco em infraestrutura e segurança da informação. Penso em sistemas antes de escrever código — isso muda a qualidade do que é construído.

Atualmente desenvolvendo a **Rydex**: plataforma SaaS B2B enterprise de recrutamento inteligente para o setor de construção civil, combinando IA, automação via WhatsApp e arquitetura multi-tenant de nível corporativo.

---

### Stack

<div align="center">

[![Backend](https://skillicons.dev/icons?i=python,fastapi,postgres,docker&perline=4)](https://skillicons.dev)
[![Frontend](https://skillicons.dev/icons?i=js,html,css,nodejs&perline=4)](https://skillicons.dev)
[![Infra](https://skillicons.dev/icons?i=linux,git,nginx,bash&perline=4)](https://skillicons.dev)

</div>

---

### Rydex — SaaS B2B em desenvolvimento ativo

> *"Não vendemos preço. Vendemos TEMPO."*

Plataforma enterprise para recrutamento inteligente no setor de construção civil.

**O que está rodando:**

- **Backend** — FastAPI assíncrono com 13+ endpoints REST, middleware de segurança em todas as respostas, rate limiting por IP e background tasks
- **Banco de dados** — PostgreSQL com 13 tabelas, arquitetura multi-tenant por `empresa_id` (UUID), índices de performance e migrations versionadas com Alembic
- **IA** — Gemini AI com arquitetura rules-first: regras locais antes de chamar a API, reduzindo custo e latência. NLP calibrado para linguagem informal de trabalhadores de obra
- **WhatsApp** — WAHA via Docker com webhook seguro, deduplicação de mensagens em memória e integração com n8n para orquestração de fluxos
- **Segurança** — JWT + bcrypt, headers OWASP (CSP, HSTS, X-Frame-Options), CORS restrito, conformidade LGPD com mascaramento de dados pessoais nos logs
- **Frontend** — Dashboard operacional + Manager com KPIs em tempo real, mapa Leaflet com georreferenciamento, modo dark/light, sistema de partículas Canvas API — tudo em JS vanilla, sem frameworks
- **Infra** — Docker Compose com PostgreSQL, WAHA e n8n isolados, Uvicorn ASGI, variáveis de ambiente tipadas com Pydantic v2

**Stack completa:** `Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `Gemini AI` `n8n` `WAHA` `Docker` `JWT` `bcrypt` `Pydantic v2` `httpx` `Leaflet` `Google Sheets API` `ReportLab` `Resend` `JavaScript ES2022`

---

<div align="center">
<sub>Domínio registrado · Deploy previsto em 4–6 semanas</sub>
</div>
