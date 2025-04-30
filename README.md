# André Hideaki Wakugawa

## Introdução

![](https://github.com/AndreWakugawa/portfolio/blob/main/blob/foto.jpg)

Tenho 25 anos, sou bacharel em Imagem e Som pela Universidade Federal de São Carlos e graduando do Tecnólogo em Banco de Dados pela FATEC Prof. Jessen Vidal.
Fui estagiário de TI na empresa KLG do Brasil durante 1 ano entre o período de mai/2024 - mai/2025.

Faça uma breve introdução sobre você. Fale de sua formação e carreira. Caso aplicável, fale de publicações ou apresentações em eventos da área de computação.

## Contatos
* [GIT](https://github.com/AndreWakugawa)
* [LinkedIn](https://br.linkedin.com/in/andrewakugawa)

## Meus Principais Conhecimentos
* Oracle Database
* PostgreSQL
* PL/SQL
* PL/pgSQL
* Java
  * Spring Boot
  * JPA & Hibernate
  * Spring Security
  * JWT, Bearer Tokens, Session Cookies
* Apache Spark
* Docker e docker compose
* Python
* Javascript e Typescript
* AWS
* Object Oriented Programming (OOP)

## Meus Projetos

### Em 2023-1
O primeiro projeto desenvolvido durante a graduação foi proposto pela empresa-cliente fictícia PBLTeX com o desafio de desenvolver desenvolver uma aplicação de Avaliação 360° para uso interno da instituição de ensino. 

A solução foi entregue pela equipe de desenvolvimento DevMinds na qual atuei como Product Owner. A aplicação com o nome de 'eVal360' foi desenvolvida para uso em terminal, com algumas janelas de dashboards que aparecem em algumas interações. Um arquivo csv foi utilizado como um pseudo banco de dados. Como um desafio do próprio grupo, decidimos desenvolver 100% em Python.

O projeto teve os seguintes requisitos:
- Autenticação (login)
> Uma comparação dos inputs de email e senha com dados existentes no arquivo 'usersDB.csv' que simula uma tabela de usuários.
- Controle de acesso
> Uma simples verificação do nível do usuário disponível em 'usersDB.csv' que direciona para rotas diferente caso o nível seja de **Administrador** ou **Usuário**.
- Controle de turmas e times
> Criação de turmas (cursos) e times (equipes) dentro dessas turmas com validação de um usuário por equipe dentro de uma mesma turma.
- Controle de Sprints
> Possibilidade de configuração da quantidade e duração em dias das Sprints durante a criação de uma turma nova.
- Dashboards gerenciais
> Visualização em gráficos para gestores analisarem as notas dos fatores de avaliação de individuos em uma turma e médias de uma turma com identificação visual para fatores com notas acima e abaixo da média.

[Repositório do eVal360](https://github.com/AndreWakugawa/DevMinds)

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
- Colaborei com a modelagem dos 'headers' dos arquivos CSV;
- Realizei o tratamento lógico na comparação das informações de input com os dados do CSV para login, hierarquia de turma, times e pessoas.
- Implantei a lógica de criação de sprints relacionadas à turmas;
- Colaborei com a lógica do login com a verificação do input do usuário com os dados disponiveis no CSV;
- Adicionei as funcionalidades CRUD para o gerenciamento de turmas.

\* Todas as contribuições foram realizadas utilizando Python e CSV.

#### Hard Skills
- Python: aprendi a fazer com consultas;

#### Soft Skills
- Metodologias ágeis e SCRUM: aprendi e apliquei com a equipe, organizando entregáveis por partes e em prazos definidos.
- Gerenciamento de projeto: estudei e apliquei algumas táticas como brainstorm, SMART e PICK para definir características do projeto, prioridades, ideias realistas e inalcançáveis para guiar o início do projeto.
- Trabalho em equipe: realizei as tarefas, que foram dispostas igualmente entre os membros da equipe considerando o conhecimento de cada um, e ofereci apoio a quem teve dificuldades, evitando 'roubar' a tarefa para mim;
- Comunicação com o cliente: aprendi como me comunicar com cliente e como realizar perguntas para extrair informações que vão ajudar na tomada de decisões;
- Comunicação: compartilhamento de informações em dailies, sprint reviews e reuniões;
- Iniciativa: procurei técnicas de gerenciamento de projeto, apresentei para a equipe e apliquei durante o desenvolvimento. Dessa maneira, foi mais simples identificar o escopo e as características do projeto e dar um pontapé inicial no desenvolvimento;

### Em 2023-2
Fale sobre o projeto desenvolvido. Apresente a empresa parceira, o problema e a solução entregue pela equipe (mínimo de um parágrafo por item). Recomenda-se o uso de figuras (ou até mesmo vídeos) para ilustrar os principais projetos.

[GIT](https://www.git.com)

#### Tecnologias Utilizadas
Apresente brevemente as tecnologias utilizadas. Uma tecnologia por linha. Indique qual a importância de cada tecnologia para o projeto.

#### Contribuições Pessoais
Apresente suas contribuições no projeto. Foque nas funcionalidades em que você mais atuou. Descreva sua atuação em detalhes, especificando que tecnologias você utilizou.

#### Hard Skills
Apresente as hard skills que você utilizou/desenvolveu durante o projeto e o nível de proficiência alcançado. Exemplo: CSS - Sei fazer com autonomia

#### Soft Skills
Apresente as soft skills que você utilizou/desenvolveu durante o projeto e em quais situações elas foram fundamentais. Exemplo: Comunicação - Precisei exercitar minhas habilidades de comunicação para viabilizar as reuniões semanais levando em conta as disponibilidades dos membros, que não cursavam as mesmas disciplinas.

### Em 2024-1
  O problema foi apresentado pela parceira Dom Rock, uma empresa de dados e tecnologia de São José dos Campos que oferece serviços de tratamento de dados. A parceira recebe diversas entradas de dados como arquivos .xlsx ou .csv até mais complexos como gravações de voz e fotos e trata as informações através de uma pipeline que transforma os dados em consumíveis para a empresa cliente tomar decisões com base em dados.
  
  O desafio proposto envolveu o início da pipeline de dados da empresa parceira, sendo dividido em três etapas. A primeira (denominada Landing Zone) envolve a entrada de um arquivo. No caso do desafio proposto, um arquivo .csv. a segunda (denominada Bronze) tratava-se da definição do identificador único das informações do arquivo (ID), a escolha de colunas que geram um hash e a exclusão de informações sem relevância. Por fim, a terceira etapa (denominada Silver) é onde foram aplicadas as regras de negócio, além da possibilidade de criar relacionamentos de 'De/Para' para a conversão de informação para dados mais consumívels.

  A equipe Wiz propôs e entregou a solução 'Pipeline Configurator', uma aplicação web desenvolvida com front-end Vue.js, servidor Java Spring Boot e banco de dados MySQL.

Fale sobre o projeto desenvolvido. Apresente a empresa parceira, o problema e a solução entregue pela equipe (mínimo de um parágrafo por item). Recomenda-se o uso de figuras (ou até mesmo vídeos) para ilustrar os principais projetos.

[GIT](https://github.com/AndreWakugawa/dom-rock-pipeline-configurator)

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
Apresente as hard skills que você utilizou/desenvolveu durante o projeto e o nível de proficiência alcançado. Exemplo: CSS - Sei fazer com autonomia
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






