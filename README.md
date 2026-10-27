<h1 align="center">Olá, eu sou o Otávio</h1>

<h3 align="center">Estudante de Análise e Desenvolvimento de Sistemas · Busco estágio em desenvolvimento back-end<br>Python · FastAPI · SQL · APIs REST<br>Em formação: Java · Spring Boot · AWS</h3>

<p align="center">
  Construo projetos da ideia ao ar: do protótipo no Figma a código rodando em servidor de verdade.<br>
  Meu projeto mais recente é um sistema full stack de gestão de crédito (FastAPI, SQLAlchemy, PostgreSQL), publicado em uma VPS com Nginx.<br>
  Continuo aprendendo pela Rocketseat e construindo todos os dias. Agora estou expandindo para Java e Spring Boot.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
</p>

---

## O que eu busco

Meu primeiro estágio em **desenvolvimento back-end ou full stack**, em um time onde eu possa aprender com engenheiros mais experientes e entregar valor desde cedo.

Eu aprendo construindo: meus projetos saem do papel (e do Figma), passam pelo código e chegam ao ar, em servidor de verdade.

## Em 30 segundos

- Projeto **full stack publicado em VPS** (FastAPI + Nginx + systemd), não só rodando na minha máquina
- **API REST** com validação (Pydantic), persistência (SQLAlchemy) e integração com API externa
- Do **protótipo no Figma** ao front-end em HTML, CSS e JavaScript puro
- **Em formação em Java e Spring Boot**, com o primeiro projeto em Java já publicado

---

## Projetos

### [Sistema de Gestão de Crédito](https://github.com/Kityro/Portfolio)

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

**Código:** [github.com/Kityro/Portfolio](https://github.com/Kityro/Portfolio)

---

### [Sistema Bancário em Java](https://github.com/Kityro/sistema-bancario-java)

Meu primeiro projeto em Java: aplicação de console para cadastro de titular, consulta de saldo, depósito e saque.

- Uso de **`BigDecimal`** para valores monetários, evitando erros de precisão
- **Validação de entrada** com expressões regulares (agência com 4 dígitos, conta com 7 dígitos)
- Regras de negócio no saque (não permite valor acima do saldo nem valor menor ou igual a zero)

**Status:** versão 1, em estilo procedural. **Próximos passos:** orientação a objetos (classe `Conta`) e, depois, API REST com Spring Boot.

**Stack:** Java

**Código:** [github.com/Kityro/sistema-bancario-java](https://github.com/Kityro/sistema-bancario-java)

---

### [Página de Apresentação](https://github.com/Kityro/Portfolio2): do Figma ao código

Meu primeiro projeto e a base da minha evolução. Desenhei no Figma e transformei em página real, com HTML, CSS e JavaScript escritos por mim.

**Stack:** Figma · HTML · CSS · JavaScript · GitHub Pages

**Código:** [github.com/Kityro/Portfolio2](https://github.com/Kityro/Portfolio2)

---

## Em estudo

- **Java**: sintaxe, orientação a objetos e coleções
- **Spring Boot**: para construir APIs REST em Java
- **AWS**: introdução a serviços de nuvem
- **Inglês técnico**

## Ferramentas

`Python` `FastAPI` `SQLAlchemy` `Pydantic` `PostgreSQL` `SQLite` `Java` `JavaScript` `HTML5` `CSS3` `Figma` `Git/GitHub` `Linux` `Nginx` `openpyxl`

## Como eu trabalho

- **Construo para o ar:** um projeto só está pronto quando alguém consegue acessar.
- **Reviso o que a IA gera:** uso como apoio para ganhar velocidade, mas preciso saber explicar cada trecho do código.
- **Aponto os próprios defeitos:** prefiro descobrir um problema na minha revisão do que na do time.

## Sobre mim

Curso Análise e Desenvolvimento de Sistemas na Anhanguera (2025–2027). Falo português, inglês e japonês (intermediário).

Antes de programar, trabalhei na linha de produção da Suzuki, no Japão, com meta rígida e controle de qualidade zero-defeito, e em vendas na Magazine Luiza, onde bati 105% das metas como líder comercial interino. Levo dessas experiências disciplina, atenção a detalhes e responsabilidade por resultado.

---

## Vamos conversar?

E-mail: [otavioseto70@gmail.com](mailto:otavioseto70@gmail.com)
LinkedIn: [linkedin.com/in/otavio-kityro](https://www.linkedin.com/in/otavio-kityro/)

<p align="center"><i>Obrigado por passar por aqui!</i></p>
