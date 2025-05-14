# André Hideaki Wakugawa

## Introdução

![](https://github.com/AndreWakugawa/portfolio/blob/main/blob/foto.jpg)

Tenho 25 anos, sou bacharel em Imagem e Som pela Universidade Federal de São Carlos e graduando do Tecnólogo em Banco de Dados pela FATEC Prof. Jessen Vidal.
Em 2024 fui admitido como estagiário de TI na empresa KLG do Brasil, onde pude atuar como suporte, analista de dados, engenheiro de dados e desenvolvedor.

## 📫 Contatos

- **[GitHub](https://github.com/AndreWakugawa)** - Meus projetos e contribuições em organizações
- **[LinkedIn](https://br.linkedin.com/in/andrewakugawa)** - Perfil profissional e network

## 💻 Principais Habilidades

### 🗃️ Banco de Dados
- **Relacionais**:
  - Oracle Database e PL/SQL
  - PostgreSQL e PL/pgSQL
- **Não-relacionais**:
  - MongoDB
  - Redis

### 👨‍💻 Linguagens de Programação
- **Java** - Desenvolvimento back-end
- **Python** - Scripts funcionais e automação
- **JavaScript/TypeScript** - Desenvolvimento front-end e consumo de APIs

### 🛠️ Ferramentas e Tecnologias
- **Spring Ecosystem**:
  - Spring Boot (desenvolvimento de APIs)
  - Spring Security (autenticação/autorização)
  - JPA & Hibernate (ORM)
- **Autenticação**:
  - JWTs, Bearer Tokens
- **Processamento de Dados**:
  - Apache Spark (ETL)
- **Infraestrutura**:
  - Docker e Docker Compose
  - AWS (conhecimentos básicos)

### 📚 Conceitos
- **OOP** - Programação Orientada a Objetos
- **Design Patterns** - Factory, Publisher, Observer, Builder, Singleton
- **Metodologias Ágeis** - SCRUM, Kanban

## Meus Projetos

### 📊 eVal360 - Sistema de Avaliação 360° (2023-1)
[🔗 Repositório no GitHub](https://github.com/AndreWakugawa/DevMinds)

O primeiro projeto desenvolvido durante a graduação foi proposto pela empresa-cliente fictícia PBLTeX com o desafio de desenvolver desenvolver uma aplicação de Avaliação 360° para uso interno da instituição de ensino. 

A solução foi entregue pela equipe de desenvolvimento DevMinds na qual atuei como Product Owner. A aplicação com o nome de 'eVal360' foi desenvolvida para uso em terminal, com algumas janelas de dashboards que aparecem em algumas interações. Um arquivo csv foi utilizado como um pseudo banco de dados. Como um desafio do próprio grupo, decidimos desenvolver 100% em Python.

**Principais Funcionalidades**:
- Autenticação de usuários
- Controle de acesso por níveis (Admin/Usuário)
- Gerenciamento de turmas e equipes
- Controle de Sprints com configuração personalizada
- Dashboards gerenciais com visualização de métricas
  
#### Tecnologias Utilizadas
- Visual Studio Code: editor de código-fonte multifuncional. No escopo do projeto utilizado para desenvolvimento da linguagem Python;
- Python: principal e única linguagem de desenvolvimento em que foi desenvolvida a toda a lógica e regras de negócio da aplicação;
- Matplotlib: biblioteca externa de Python que foi utilizada para a montagem e exibição de gráficos para os dashboards;
- Arquivos CSV: arquivos com propósito de servir como um 'pseudo banco de dados' que substituiram o uso de SGBDs, tecnologia na qual não tinhamos conhecimento no começo do curso;
- ClickUp: ferramenta de gestão de projetos para organização e controle interno da equipe;
- Slack: ferramenta para comunicação com o cliente;
- Miro: ferramenta auxiliar na gestão do projeto em que utilizamos para realizar Brainstorms, Sprint reviews, retrospectivas e técnicas de gerenciamento de projeto como as tabelas SMART e PICK;
- Git e Github: controle de versionamento e hospedagem.

#### Contribuições Pessoais
**Minhas Contribuições**:
- **Autenticação Segura**: Implementei o sistema de login com validação de credenciais contra arquivo CSV, simulando um banco de dados básico
- **Gestão Acadêmica**: Desenvolvi o CRUD completo para turmas, incluindo validações de unicidade e relacionamentos
- **Lógica de Sprints**: Criei o sistema de configuração de sprints com duração personalizável por turma
- **Arquitetura de Dados**: Projetei a estrutura de arquivos CSV que serviu como base de dados para toda a aplicação
- **Coordenação**: Atuei como PO, organizando sprints, priorizando backlog e mantendo comunicação constante com stakeholders

#### Hard Skills
- Python: aprendi a fazer com consultas;

#### Soft Skills
- Metodologias ágeis e SCRUM: aprendi e apliquei com a equipe, organizando entregáveis por partes e em prazos definidos.
- Gerenciamento de projeto: estudei e apliquei algumas táticas como brainstorm, SMART e PICK para definir características do projeto, prioridades, ideias realistas e inalcançáveis para guiar o início do projeto.
- Trabalho em equipe: realizei as tarefas, que foram dispostas igualmente entre os membros da equipe considerando o conhecimento de cada um, e ofereci apoio a quem teve dificuldades, evitando 'roubar' a tarefa para mim;
- Comunicação com o cliente: aprendi como me comunicar com cliente e como realizar perguntas para extrair informações que vão ajudar na tomada de decisões;
- Comunicação: compartilhamento de informações em dailies, sprint reviews e reuniões;
- Iniciativa: procurei técnicas de gerenciamento de projeto, apresentei para a equipe e apliquei durante o desenvolvimento. Dessa maneira, foi mais simples identificar o escopo e as características do projeto e dar um pontapé inicial no desenvolvimento;

### 🎓 SGTG - Sistema Gerenciador de TGs (2023-2)
[🔗 Repositório no GitHub](https://github.com/AndreWakugawa/API-2-Semestre-DevMinds/tree/main)

O desafio proposto foi o desenvolvimento de uma ferramenta para gerenciamento de trabalhos de graduação de uso interno da instituição de ensino, sendo o cliente a própria FATEC. A aplicação deve gerir as matérias/semestres, alunos matriculados nas matérias, regras de negócio envolvendo os diferentes tipos de TG, entrega de atividades, atribuição de notas, retorno de feedbacks e geração de relatórios.
A solução entregue foi o SGTG (Sistema Gerenciador de Trabalho de Graduação), uma aplicação em desktop para uso dos próprios professores que ministram as matérias de Trabalho de Graduação. A aplicação recebe como entrada um arquivo de respostas de um Google Forms em CSV e popula os dados dos alunos para seu uso.

#### Tecnologias Utilizadas
- Java: linguagem para manuseio dos dados e manipulação da lógica da aplicação;
- JavaFX: framework Java para criação de telas. Nesse caso utilizado para o desenvolvimento das telas da aplicação em desktop.
- Maven: ferramenta de automação de compilação utilizada para facilitar a importação de bibliotecas externas;
- MySQL: um SGBD para armazenamento dos dados da aplicação;
- IntelliJ IDEA: IDE para desenvolvimento Java;
- Git e Github: controle de versionamento e hospedagem;
- Diagrams.net: ferramenta web para desenho de diagramas, wireframe e UML da aplicação;
- Discord: ferramenta de comunicação interna da equipe, utilizada para compartilhar informações e realizar reuniões quando necessário;
- Slack: ferramenta para comunicação com o cliente;
- MySQL Workbench: ferramenta visual para gerenciamento do MySQL;
- DBeaver: ferramenta de administração de bases de dados relacionais, também utilizado para gerenciar o banco de dados MySQL.

#### Contribuições Pessoais

Inicialmente comecei atuando apenas como desenvolvedor, porém, por volta do início da segunda sprint, a pessoa responsável pelo papel de Product Owner teve que trancar o curso. Com isso, assumi o papel de Product Owner até a entrega final, além de manter minhas responsabilidades como desenvolvedor.

- Modelagem completa do banco de dados (ERD)<details>
<summary>Relacionamento de dados</summary>
<br>
 ![*Print da ferramenta DBeaver](https://github.com/AndreWakugawa/portfolio/blob/main/blob/dbSGTG.png)
</details>

- Criação dos scripts DDL para o MySQL
- Após assumir como Product Owner corri atrás para cobrir as pendências da falta de comunicação que surgiram com o representante anterior;
- Realizei a conexão entre aplicação Java e banco de dados via JDBC e ajudei os membros responsáveis pelo back-end desenvolver as conexões da aplicação Java com o banco de dados;
- Implementação de DAOs e objetos POJO que representam as entidades do banco de dados;
- Colaborei com queries SQL para que busquem as informações corretas no banco de dados;

Apresente suas contribuições no projeto. Foque nas funcionalidades em que você mais atuou. Descreva sua atuação em detalhes, especificando que tecnologias você utilizou.

#### Hard Skills
- Java: primeiro contato com a linguagem, aprendi a utilizar com consultas;
- JavaFX: leve contato com a ferramenta, aprendi a utilizar com consultas e auxilio de outros membros;
- SQL (MySQL): primeiro contato com a linguagem, aprendi a utilizar com autonomia;
- Maven: primeiro contato com a tecnologia, aprendi a utilizar com consultas;
- JDBC: primeiro contato com a tecnologia, aprendi a utilizar com consultas;

#### Soft Skills
- Comunicação com o cliente: tive que assumir o papel durante o andamento do projeto e buscar soluções intermediárias com o cliente para uma entrega cobrindo requisitos que não haviam sido discutidos até então. Com isso, acredito que ajudei na construção de um entregável admissível que evitou a não aceitação de uma sprint.
- Comunicação: me esforcei em ir atrás de informações com o cliente e entregar ao time de desenvolvimento. Com isso foi possível entender e entregar requisitos que estavam faltantes no escopo do projeto até então;
- Iniciativa: tomei iniciativa para aprender diversas tecnologias e linguagens novas, sendo elas Java, JDBC, Maven, SQL (MySQL) e compartilhei o conhecimento sempre que membros da equipe tinham dúvidas.

### ⚙️ Pipeline Configurator (2024-1)
[GIT](https://github.com/AndreWakugawa/dom-rock-pipeline-configurator)

  O problema foi apresentado pela parceira Dom Rock, uma empresa de dados e tecnologia de São José dos Campos que oferece serviços de tratamento de dados. A parceira recebe diversas entradas de dados como arquivos .xlsx ou .csv até mais complexos como gravações de voz e fotos e trata as informações através de uma pipeline que transforma os dados em consumíveis para a empresa cliente tomar decisões com base em dados.
  
  O desafio proposto envolveu o início da pipeline de dados da empresa parceira, sendo dividido em três etapas. A primeira (denominada Landing Zone) envolve a entrada de um arquivo. No caso do desafio proposto, um arquivo .csv. a segunda (denominada Bronze) tratava-se da definição do identificador único das informações do arquivo (ID), a escolha de colunas que geram um hash e a exclusão de informações sem relevância. Por fim, a terceira etapa (denominada Silver) é onde foram aplicadas as regras de negócio, além da possibilidade de criar relacionamentos de 'De/Para' para a conversão de informação para dados mais consumívels.

  A equipe Wiz propôs e entregou a solução 'Pipeline Configurator', uma aplicação web desenvolvida com front-end Vue.js, servidor Java Spring Boot e banco de dados MySQL.

  **Funcionalidades**:
- 🛬 Landing Zone: Entrada de arquivos CSV
- 🥉 Bronze: Definição de IDs únicos e seleção de colunas
- 🥈 Silver: Aplicação de regras de negócio e relacionamentos
  
#### Tecnologias Utilizadas
- HTML: linguagem de programação para criação de páginas Web;
- CSS: linguagem para aplicação de estilos em códigos HTML;
- TypeScript: linguagem variante de JavaScript que adiciona tipagem ao código;
- Vue.js: framework JavaScript para o desenvolvimento de SPA (Single Page Application) e facilitador na criação de códigos reutilzáveis;
- Java: linguagem de programação orientada a objetos;
- Spring Boot: framework Java para desenvolvimento de Rest APIs;
- MySQL: simples SGDB da Oracle para armazenamento de dados da aplicação;
- IntelliJ IDEA: IDE para desenvolvimento Java;
- Visual Studio Code: editor de código-fonte multifuncional. No escopo do projeto utilizado para desenvolvimento de Vue.js;
- Figma: ferramenta utilizada para desenvolvimento de Mockups e Wireframes;
- Discord: ferramenta para comunicação interna do grupo;
- Slack: ferramenta para comunicação com o cliente

#### Contribuições Pessoais
- Colaborei com a modelagem, desenvolvimento e manutenção das tabelas e relacionamentos referentes à etapa Bronze, Silver, Logs;
- Colaborei com o mapeamento de entidades e DTOs das tabelas acima utilizando as anotações oferecidas pelo Spring para identificar chaves estrangeiras, chaves compostas, tipos de dados, nome de colunas, nome de tabelas, etc;
  - (@JoinColumn, @JoinColumns, @ManyToOne, @OneToMany, @Id, @EmbeddedId, @GeneratedValue)
  - Aprendizado e utilização dos dois diferentes tipos de FetchTypes do @GeneratedValue: LAZY e EAGER
- Sugeri e implementei a biblioteca 'ModelMapper' no projeto. A biblioteca permite a conversão de Entidade para DTO e DTO para Entidade de maneira ágil em uma linha de código;
- Implementei o Spring Security com JWTs, separando níveis de acesso entre admin, landing zone, bronze e silver;
- Colaborei com a jornada do dado <Repository, Service, Controller> para várias entidades;
- Desenvolvi vários métodos que implementam a regra de negócio requisitada pelo cliente na camada de serviço;
Apresente suas contribuições no projeto. Foque nas funcionalidades em que você mais atuou. Descreva sua atuação em detalhes, especificando que tecnologias você utilizou.

#### Hard Skills
- Java: sei fazer com autonomia;
- Spring Boot: sei fazer com facilidade (Security, JWT, mapeamento de entidades, repositórios, serviços e controllers);
- SQL: sei fazer com autonomia (DDL e DQL);

#### Soft Skills
- Trabalho em equipe: realizei as tarefas, que foram dispostas igualmente entre os membros da equipe considerando o conhecimento de cada um, e ofereci apoio a quem teve dificuldades, evitando 'roubar' a tarefa para mim;
- Comunicação: atualizações em dailies, sprint reviews e reuniões;
- Iniciativa: propus diversas ferramentas e ideias que foram adotadas ao longo do projeto;
- Solução de problemas: desenvolvi e apliquei algumas das regras de negócio do cliente nos serviços;
- Pensamento analítico: análise e tratamento de dados que foram construídos em um objeto para ser facilmente consumido    

### Em 2025-1
Mesmo formato

### Em 2025-1
Mesmo formato






