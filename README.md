<h1 align="center">Hi, I'm Otávio 👋</h1>

<h3 align="center">Tech student looking for a backend development internship<br>Python · FastAPI · Flask · SQL · REST APIs</h3>

<p align="center">
  I build projects from idea to deployment: from a Figma design to working code running on a real server.<br>
  My latest project is a full-stack credit management system (FastAPI, SQLAlchemy, PostgreSQL) deployed on a VPS with Nginx.<br>
  I use AI as a tool to move faster, always focusing on understanding logic, structure and best practices.<br>
  I keep learning through Rocketseat and by building every day.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/Rocketseat-8257E5?style=for-the-badge&logoColor=white" />
</p>

---

## 🎯 O que eu busco

Meu primeiro estágio em **desenvolvimento backend ou full stack**, em um time que leve engenharia a sério.

Eu aprendo construindo: meus projetos saem do papel (e do Figma), passam pelo código e chegam ao ar, em servidor de verdade.

## ⚡ Em 30 segundos

- Projeto **full stack publicado em VPS** (FastAPI + Nginx + systemd), não só rodando na minha máquina
- **API REST** com validação (Pydantic), persistência (SQLAlchemy) e integração com API externa
- Do **protótipo no Figma** ao front-end em HTML, CSS e JavaScript puro
- Uso IA como apoio para acelerar, com foco em **entender lógica, estrutura e boas práticas**

---

## 🚀 Projetos

### 💳 [Sistema de Gestão de Crédito](https://github.com/Kityro/Portfolio)

Portal que consulta dados cadastrais por CPF e apresenta uma análise de crédito de demonstração.

**O que tem dentro**

- API REST em **FastAPI**, com código em camadas (`routes` → `services` → `models`/`schemas`)
- **Pydantic** para validar entrada e controlar o que a API devolve (o `PATCH` só altera campos permitidos)
- **PostgreSQL** com fallback automático para **SQLite**, para o projeto rodar em qualquer máquina
- Integração com API externa (CPFhub.io) e **variáveis de ambiente** para segredos
- **Consulta em lote:** upload de `.txt`/`.csv` com CPFs e download de uma planilha `.xlsx` formatada
- **Simulador de financiamento** com cálculo de prazo e parcela (Tabela Price)
- Servidor estático com **lista de arquivos permitidos**, para não expor código-fonte nem banco por URL
- Script de deploy para **VPS** (Nginx como proxy reverso, serviço no systemd, firewall UFW)

**O que é real e o que é simulado** (transparência importa)

| Campo | Origem |
|---|---|
| Nome e data de nascimento | Reais, via CPFhub.io |
| Score, restrição, dívida, limite e taxa | **Simulados** para demonstração (sem fonte de crédito real) |

**Stack:** Python · FastAPI · SQLAlchemy · Pydantic · PostgreSQL/SQLite · JavaScript · Nginx

🔗 **Código:** [github.com/Kityro/Portfolio](https://github.com/Kityro/Portfolio)

---

### 🎨 [Página de Apresentação](https://github.com/Kityro/Portfolio2) — Figma → código

Meu primeiro projeto e a base da minha evolução. Desenhei no Figma e transformei em página real, com HTML, CSS e JavaScript escritos por mim.

**Stack:** Figma · HTML · CSS · JavaScript · GitHub Pages
🔗 **Código:** [github.com/Kityro/Portfolio2](https://github.com/Kityro/Portfolio2)

---

## 🧰 Ferramentas

`Python` `FastAPI` `Flask` `SQLAlchemy` `Pydantic` `PostgreSQL` `SQLite` `JavaScript` `HTML5` `CSS3` `Figma` `Git/GitHub` `Linux` `Nginx` `openpyxl`

## 🤝 Como eu trabalho

- **Construo para o ar:** um projeto só está pronto quando alguém consegue acessar.
- **Reviso o que a IA gera:** uso como ferramenta, mas preciso saber explicar cada linha.
- **Aponto os próprios defeitos:** prefiro descobrir um problema na minha revisão do que na do time.

---

## 📫 Vamos conversar?

📧 [otavioseto70@gmail.com](mailto:otavioseto70@gmail.com)
💼 [linkedin.com/in/otavio-kityro](https://www.linkedin.com/in/otavio-kityro/)

<p align="center"><i>Obrigado por passar por aqui! 🚀</i></p>
