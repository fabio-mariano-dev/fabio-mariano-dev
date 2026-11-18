# 👨🏽‍💻 Fábio Mariano

### `Full Stack Developer | C# .NET`

> Desenvolvedor focado em construir **soluções web e sistemas empresariais**, transformando regras de negócio em aplicações eficientes, organizadas e escaláveis.

<p align="left">
  <a href="https://github.com/fabio-mariano-dev">
    <img src="https://img.shields.io/badge/GitHub-fabio--mariano--dev-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/fabio-mariano-b024393b3/">
    <img src="https://img.shields.io/badge/LinkedIn-Perfil-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
  </a>
</p>

---
Desenvolvedor com foco no ecossistema **C# / .NET**, atuando no desenvolvimento e manutenção de **sistemas empresariais e ERP**, APIs e soluções voltadas para processos de negócio.

Tenho experiência trabalhando com **regras de negócio, banco de dados, integrações, relatórios e interfaces web**, além de suporte e análise de sistemas, buscando transformar necessidades reais em soluções funcionais e eficientes.

Atualmente, curso **Ciência da Computação** e continuo aprofundando meus conhecimentos em desenvolvimento **Full Stack**, arquitetura de aplicações e tecnologias do ecossistema **.NET**.

---

## 🛠️ Tecnologias & Ferramentas

### Backend

<p align="left">
  <img src="https://skillicons.dev/icons?i=cs,dotnet" alt="C# e .NET"/>
</p>

`C#` `.NET` `.NET Core` `.NET Framework` `ASP.NET Core` `APIs REST` `Dapper` `Entity Framework Core`

### Frontend

<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css" alt="HTML e CSS"/>
</p>

`Blazor` `MudBlazor` `HTML` `CSS`

### Database

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/microsoftsqlserver/microsoftsqlserver-plain.svg" width="45" height="45" alt="SQL Server"/>
</p>

`SQL Server` `Stored Procedures`

### Tools

<p align="left">
  <img src="https://skillicons.dev/icons?i=git,github,visualstudio,vscode" alt="Git, GitHub, Visual Studio e VS Code"/>
</p>

`Git` `GitHub` `Visual Studio` `VS Code`

---

## 📌 Projetos em destaque

Aqui estão alguns dos projetos que representam minha evolução como desenvolvedor.

### 🔹 Projeto 01 — FinanCore

<img width="1330" height="630" alt="dashborad" src="https://github.com/user-attachments/assets/c064a086-19be-4e7d-abd7-0cc7a505355b" />

**Problema:**
A gestão financeira pode se tornar complexa quando contas a pagar, contas a receber e movimentações ficam descentralizadas, dificultando o acompanhamento dos lançamentos e do fluxo financeiro.

**Solução:**
O FinanCore é uma aplicação web para gestão financeira, desenvolvida com arquitetura em camadas e separação de responsabilidades. A aplicação permite organizar contas a pagar e receber, fornecedores e movimentações financeiras, oferecendo uma base estruturada para acompanhar os lançamentos e o fluxo de caixa.

**Tecnologias:**
`C#` `ASP.NET Core` `.NET 10` `Blazor` `SQL Server` `FluentValidation` `JWT`

**Principais funcionalidades:**

- Gestão de contas a pagar
- Gestão de contas a receber
- Cadastro e gerenciamento de fornecedores e clientes
- Registro e acompanhamento de movimentações financeiras
- Fluxo de caixa
- Autenticação e autorização com JWT
- Soft delete e controle de concorrência
- Validações de dados
- API REST integrada à aplicação web

Interface:
<img width="2014" height="880" alt="login" src="https://github.com/user-attachments/assets/13314a06-fe38-4e2c-8f68-90b9b3ba4b2f" />

<img width="2469" height="847" alt="Contas a Pagar" src="https://github.com/user-attachments/assets/c10a9e7f-d35e-41ec-b46c-cfdd8ffdfb1b" />

<img width="2475" height="910" alt="Contas a Receber" src="https://github.com/user-attachments/assets/083e2fd3-783f-4349-a915-3aaaea08c55b" />

<img width="2478" height="946" alt="Movimentacoes" src="https://github.com/user-attachments/assets/2fbaee88-f623-49e0-803a-56aa81715196" />

<img width="1343" height="628" alt="fluxo de caixa" src="https://github.com/user-attachments/assets/bd8932d3-ddf4-4eba-94eb-685a3158893f" />

🔗 **[Ver projeto](https://github.com/fabio-mariano-dev/FinanCore)**

---

### 🔹 Projeto 02 — CotaCompras

<img width="1358" height="636" alt="image-1795009287937" src="https://github.com/user-attachments/assets/e0e41cb1-661e-44fa-9e25-70534171114f" />

**Problema:**
Em muitas empresas a compra ainda acontece por e-mail e planilha: o setor pede por mensagem, o comprador cota por telefone e não fica registrado quem aprovou nem por que um fornecedor foi escolhido.

**Solução:**
O CotaCompras é um sistema de compras corporativas que leva o pedido da requisição interna até a aprovação da proposta vencedora. Os fornecedores respondem às cotações por um portal próprio, o comprador compara as propostas no mapa comparativo e cada etapa fica registrada no histórico. Todo o acesso a dados é feito por stored procedures executadas com Dapper.

**Tecnologias:**
`C#` `ASP.NET Core` `.NET 10` `Blazor WebAssembly` `MudBlazor` `SQL Server` `Stored Procedures` `Dapper` `FluentValidation` `JWT` `xUnit`

**Principais funcionalidades:**

- Requisições de compra com aprovação ou rejeição com motivo
- Geração de cotação a partir da requisição aprovada, com sugestão de fornecedores por categoria
- Portal do fornecedor: cada empresa vê e responde apenas às próprias cotações
- Mapa comparativo com o menor preço de cada item em destaque
- Justificativa obrigatória ao escolher uma proposta que não é a de menor valor
- Segregação de funções: quem escolhe a proposta não pode aprová-la
- Controle de concorrência com rowversion e histórico de todas as etapas
- Testes SQL das procedures, testes unitários e testes de integração com a API real

https://github.com/user-attachments/assets/8f6afe82-60b8-4787-a68f-6b55dc8b52f3

🔗 **[Ver projeto](https://github.com/fabio-mariano-dev/CotaCompras)**

---
## 📊 GitHub Stats

<p align="left">
  <img
    src="https://github-readme-stats.vercel.app/api?username=fabio-mariano-dev&show_icons=true&theme=transparent&hide_border=true"
    height="165"
    alt="Estatísticas do GitHub"
  />

  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=fabio-mariano-dev&layout=compact&theme=transparent&hide_border=true"
    height="165"
    alt="Principais linguagens"
  />
</p>

<p align="left">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=fabio-mariano-dev&bg_color=00000000&color=8b949e&title_color=39d353&line=39d353&point=26a641&area=true&area_color=26a641&hide_border=true&custom_title=Contribui%C3%A7%C3%B5es%20nos%20%C3%BAltimos%2031%20dias"
    width="100%"
    alt="Gráfico de contribuições"
  />
</p>

---

## 📚 Atualmente

**Estudando Ciência da Computação e Inglês**

Aprofundando conhecimentos em **C# e .NET**

Evoluindo em **Desenvolvimento Full Stack**

Aprimorando conhecimentos em **SQL Server e banco de dados**

Desenvolvendo projetos para fortalecer meu **portfólio e experiência prática**

---

## 🎯 Objetivos

Busco oportunidades como **Desenvolvedor**, especialmente em projetos que utilizem **C# / .NET** e permitam atuar no desenvolvimento de soluções reais.

Meu objetivo é continuar evoluindo tecnicamente, contribuir para projetos relevantes e construir uma carreira sólida como desenvolvedor.

---

Estou aberto a oportunidades, networking e projetos relacionados a desenvolvimento de software.

<p align="left">
  <a href="https://github.com/fabio-mariano-dev">
    <img src="https://img.shields.io/badge/GitHub-fabio--mariano--dev-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/fabio-mariano-b024393b3/">
    <img src="https://img.shields.io/badge/LinkedIn-Conecte--se-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
  </a>
</p>

---
