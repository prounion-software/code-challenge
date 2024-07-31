# Code Challenge para posição de Programador Node Jr. na [ProUnion](https://prounion.com.br)

<p style="text-align:center">
   <h2>🚨⚠️🚨⚠️🚨⚠️🚨⚠️ Atenção ⚠️🚨⚠️🚨⚠️🚨⚠️🚨</h2>
</p>

**Update: 31/07/2024**

Devido a grande quantidade de candidaturas, estamos pausando novas avaliações.

Neste momento estamos realizando as entrevistas e processos seletivos de quem já se candidatou, e todos sem exceção são muito talentosos e competentes, realizaram os desafios com maestria. Isso nos deixa muito contentes, saber que temos grandes talentos chegando na nossa área de desenvolvimento de software.

Você ainda pode mandar seus desafios, mas nosso foco atual será organizar o time com o pessoal que está chegando, para uma próxima oportunidade buscar dentre aos demais que resolveram esses desafios.

Atenciosamente,<br>
**Equipe ProUnion**

<p style="text-align:center">
   <h2>🚨⚠️🚨⚠️🚨⚠️🚨⚠️🚨⚠️🚨⚠️🚨⚠️🚨⚠️🚨</h2>
</p>

---

Os dois desafios listados abaixo são seu ingresso para a candidatura para vagas de programador Node Jr. na [ProUnion](https://prounion.com.br).

Somos uma software house de pequeno porte mas em expansão, todos trabalhamos em home office.

Ao concluir os desafios, envie o endereço dos repositórios para **contato@prounion.com.br** com o assunto `Code Challenge` e com suas informações de contato como LinkedIn, Currículo e etc.

## Dados sobre a vaga

- Regime de contratação: **CLT**;
- Salário: **R$ 2.500,00**;
- Local de trabalho: **100% remoto**;
- Carga horária (semanal): **40 horas**;

#### Dúvidas gerais

- **Ensino**: _Não é necessário ensino superior_, mas deve ter conhecimento suficiente para entregar os desafios abaixo;
- **Posso me candidatar como estagiário ou trainee?**: Não, no momento não estamos com algum programa de estágio aberto.
- **Preciso realizar os dois desafios?**: Sim, os dois são importantes para entendermos quais conhecimentos você domina e de que forma organiza seu código;
- **Até quando posso mandar desafios?**: Por enquanto não há data limite, estamos aumentando gradativamente os times de desenvolvimento. Envie seu projeto assim que se sentir confiante em apresentá-los;
- **Posso colocar esses projetos no meu portfólio?**: Sim, com certeza. Na verdade, nós recomendamos que monte um portfólio para você com estes e outros projetos que achar interessante.
- **Posso fazer alterações no projeto, por exemplo trocar o ExpressJS pelo Koa.JS?**: _Claro que sim, desde que não altere as funcionalidades solicitadas na aplicação_ e descreva o motivo dessa alteração em relação ao escopo no README.md. Caso contrário, o avaliador irá acreditar que você não seguiu os requisitos.
- **Posso adicionar funcionalidades não solicitadas, como adicionar uma documentação do Swagger?**: Pode, porém o que será avaliado primariamente são os requisitos solicitados. Concentre-se nos requisitos primeiro, cuidado com _**overengineering**_.
- **Preciso deixar a aplicação "rodando", no ar em algum serviço tipo Vercel?**: Não.
- **O que vem depois?**:
  - Todos que cumprirem os requisitos dos projetos receberam um feedback a respeito;
  - Aos que se destacarem, serão convidados para uma entrevista via Google Meet para um bate-papo técnico e apresentação da empresa;

<p align="center">
  <img src="./img.svg" />
</p>

---

### Desafio 01: Aplicação de Lista de Tarefas (To-Do List)

#### Requisitos:

1. **Backend (Node.js com Express):**

   - Crie uma API RESTful com as seguintes rotas:
     - `GET /tasks`: Retorna todas as tarefas;
     - `POST /tasks`: Adiciona uma nova tarefa;
     - `PUT /tasks/:id`: Atualiza uma tarefa existente;
     - `DELETE /tasks/:id`: Remove uma tarefa;
   - Utilize um banco de dados em memória, como uma lista, para armazenar as tarefas durante a execução da aplicação.

2. **Frontend (Vue.js ou React):**

   - Crie uma interface de usuário para gerenciar as tarefas;
   - A interface deve permitir:
     - Visualizar a lista de tarefas;
     - Adicionar uma nova tarefa;
     - Editar uma tarefa existente;
     - Remover uma tarefa;
   - Utilize chamadas à API para interagir com o backend.

3. **Requisitos Adicionais:**
   - Utilize TypeScript tanto no frontend quanto no backend.
   - Implemente validações básicas para garantir que uma tarefa tenha um título antes de ser criada ou atualizada.
   - Adicione estilos básicos para tornar a interface mais amigável (CSS simples ou frameworks como Bootstrap/Tailwind).

#### Entregáveis:

- Código fonte completo em um repositório público Git (por exemplo, GitHub ou GitLab).
- Instruções claras sobre como executar o projeto localmente (README).
- Testes básicos (opcional, mas **será um grande diferencial**).

### Critérios de Avaliação:

- **Funcionalidade:** O quão bem a aplicação atende aos requisitos descritos;
- **Organização do código:** Qualidade do código, incluindo organização, clareza e uso de boas práticas;
- **Uso de TypeScript:** Correta aplicação de tipagem estática com TypeScript;
- **Documentação:** Clareza das instruções e comentários no código;
- **Estilo:** Aparência e usabilidade da interface de usuário.

---

### Desafio 02: Sistema de Gerenciamento de Usuários

#### Requisitos:

1. **Backend (Node.js com Express):**

   - Crie uma API RESTful com as seguintes rotas:
     - `GET /users`: Retorna todos os usuários;
     - `POST /users`: Adiciona um novo usuário;
     - `PUT /users/:id`: Atualiza um usuário existente;
     - `DELETE /users/:id`: Remove um usuário;
   - Utilize um banco de dados relacional (PostgreSQL ou MySQL) para armazenar os dados dos usuários;
   - Inclua um esquema básico para o usuário com campos como `id`, `nome`, `email`, e `senha`. _(Utilize uma estratégia segura para armazenamento de senha)_;
   - Não utilize ORMs _(como Prisma, TypeORM, etc)_, o objetivo aqui é sabermos como está seu nível de conhecimento em bancos de dados relacionais.

2. **Frontend (Vue.js ou React):**

   - Crie uma interface de usuário para gerenciar os usuários.
   - A interface deve permitir:
     - Visualizar a lista de usuários;
     - Adicionar um novo usuário;
     - Editar um usuário existente;
     - Remover um usuário;
   - Utilize chamadas à API para interagir com o backend.

3. **Docker:**

   - Crie um `Dockerfile` para o backend Node.js;
   - Crie um `Dockerfile` para o frontend (se necessário);
   - Utilize o `docker-compose` para orquestrar o backend, frontend e o banco de dados relacional;
   - Certifique-se de que todos os serviços possam ser iniciados com um único comando (`docker-compose up`).

4. **Requisitos Adicionais:**
   - Utilize TypeScript tanto no frontend quanto no backend;
   - Implemente validações básicas para garantir que um usuário tenha um nome e email válidos antes de ser criado ou atualizado;
   - Adicione autenticação básica (por exemplo, JWT) para proteger as rotas de criação, atualização e remoção de usuários;
   - Adicione estilos básicos para tornar a interface mais amigável (CSS simples ou frameworks como Bootstrap/Tailwind).

#### Entregáveis:

- Código fonte completo em um repositório público Git (por exemplo, GitHub ou GitLab);
- Instruções claras sobre como executar o projeto localmente (README), incluindo instruções para rodar com Docker;
- Arquivos de configuração do Docker (`Dockerfile`, `docker-compose.yml`).
- Testes básicos (opcional, mas **será um grande diferencial**).

### Critérios de Avaliação:

- **Funcionalidade:** O quão bem a aplicação atende aos requisitos descritos;
- **Organização do código:** Qualidade do código, incluindo organização, clareza e uso de boas práticas;
- **Uso de TypeScript:** Correta aplicação de tipagem estática com TypeScript;
- **Uso de Docker:** Configuração correta e eficiente dos containers;
- **Documentação:** Clareza das instruções e comentários no código;
- **Estilo:** Aparência e usabilidade da interface de usuário.
