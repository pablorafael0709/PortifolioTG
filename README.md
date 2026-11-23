# Portfólio de Pablo Rafael Rosa da Silva

## Apresentação do Aluno

<img src="img/foto.png" width="200" alt="Foto de Pablo Rafael Rosa da Silva">

Meu nome é **Pablo Rafael Rosa da Silva**, tenho 26 anos e sou aluno do curso de **Tecnologia em Análise e Desenvolvimento de Sistemas** da Faculdade de Tecnologia de São José dos Campos – Prof. Jessen Vidal (Fatec-SJC).

### Histórico acadêmico

Antes da Fatec, cursei Ciência da Computação na Universidade de São Paulo (USP), no campus de Ribeirão Preto.

### Motivação para entrar na Fatec

Cheguei à área de tecnologia quase por acaso e consegui ingressar no curso de Ciência da Computação da USP, em Ribeirão Preto. Com a pandemia, porém, não consegui concluir a graduação e precisei deixar a cidade. Foi minha família que me recomendou a Fatec, e assim pude retomar os estudos na instituição, com o objetivo de conquistar meu diploma de ensino superior e, com ele, novas oportunidades na vida.

### Histórico profissional

| Empresa | Período | Cargo | Atribuições |
| --- | --- | --- | --- |
| Infinity Academy 3D (Parque Tecnológico de São José dos Campos) | 01/2023 a 09/2023 | Pesquisador de iniciação científica | Pesquisa na fronteira tecnológica da realidade virtual, explorando as possibilidades e enfrentando as limitações da tecnologia |
| Micro Assist (São José dos Campos) | 03/2024 a 05/2024 | Suporte técnico | Suporte técnico |
| B2B (São José dos Campos) | 08/2024 a 10/2024 | Suporte e manutenção de redes | Suporte e manutenção de redes de computadores |
| Infinity Academy 3D (como PJ) | 01/2025 a 11/2026 | Desenvolvedor de realidade virtual | Desenvolvimento de aplicações de realidade virtual com C#, .NET e Unity |

### Informações de contato

- [E-mail (pablo7r@outlook.com)](mailto:pablo7r@outlook.com)
- [GitHub](https://github.com/pablorafael0709)
- [LinkedIn](https://www.linkedin.com/in/pablo-rafael-silva-9ab4771ba/)

### Principais conhecimentos

- Java e Spring Boot (APIs REST e testes automatizados com JUnit)
- Python (Flask, pytest e LangGraph)
- Integração com modelos de IA usando LangChain4j (RAG com Hugging Face) e LangGraph
- HTML, CSS, TypeScript, React, React Native com Expo e Next.js
- Bancos de dados relacionais PostgreSQL e MySQL
- Mensageria com RabbitMQ
- Docker
- C#, .NET e Unity (realidade virtual)
- Suporte técnico e redes de computadores
- Git e GitHub, incluindo GitHub Actions
- Metodologia ágil Scrum

---

## Projetos API

<details>
<summary>API-SCRUM - Site de treinamento na metodologia Scrum</summary>

### Primeiro Semestre – 2023-1

#### Empresa Parceira

Fatec São José dos Campos. O professor Antônio Egydio atuou como cliente e foi o responsável pelos requisitos.

#### Problema

Organizações que adotam o Scrum costumam treinar seus colaboradores com materiais dispersos e muito teóricos, que explicam o framework sem mostrar, com exemplos práticos, como aplicar cada papel, evento e artefato no dia a dia. Além disso, a empresa não tem como medir se o colaborador realmente entendeu o conteúdo, o que leva a aplicações incorretas da metodologia nos projetos.

#### Solução

Para resolver o problema proposto, a equipe Hexabees desenvolveu o **API-SCRUM**, uma **aplicação web** de treinamento em Scrum que a empresa pode usar para capacitar seus colaboradores. O site apresenta o time Scrum, os artefatos e os eventos do framework com conceitos, referências, vídeos e exemplos práticos. Também oferece modelos dos artefatos para download, traz páginas sobre soft skills e sobre casos de sucesso de empresas que usam o Scrum e inclui questionários de avaliação parciais e um final, incorporados às páginas, para medir o aprendizado do colaborador. Uma barra de navegação reúne os tópicos principais, para que o colaborador possa voltar a qualquer conteúdo quando quiser.

#### Link do Repositório Git

[github.com/HEXABEES/API-SCRUM](https://github.com/HEXABEES/API-SCRUM)

#### Tecnologias Utilizadas

| Tecnologia | Onde foi utilizada |
| --- | --- |
| Python e Flask | Servidor da aplicação e rotas de cada página do site |
| Jinja2 | Templates HTML com herança de um layout base comum a todas as páginas |
| HTML e CSS | Estrutura e estilo das páginas de conteúdo e dos questionários |
| Bootstrap | Componentes visuais e responsividade |
| Google Forms | Questionários de avaliação parciais e final, incorporados às páginas |
| Figma | Wireframe e protótipo navegável apresentado ao cliente |
| Git e GitHub | Versionamento do código e documentação das sprints |

#### Contribuições Pessoais

Nesse projeto atuei como desenvolvedor (Scrum Team) da equipe Hexabees. Desenvolvi a página de casos de sucesso, que corresponde à história de usuário US17 da terceira sprint. Para isso, criei o template HTML da página, estendendo o layout base com Jinja2, e a rota correspondente na aplicação Flask. Na página, apresentei um gráfico com o percentual de uso do Scrum em comparação com outras metodologias e textos sobre como empresas conhecidas, como Google, Amazon, Microsoft, IBM e Nokia, aplicam o framework, com as imagens de cada uma organizadas na pasta de arquivos estáticos. Também iniciei o template da página de downloads e atualizei o README do repositório.

#### Hard Skills

| Tecnologia | Nível de proficiência |
| --- | --- |
| Python e Flask | faço/uso com ajuda |
| HTML e CSS | faço/uso com ajuda |
| Jinja2 | faço/uso com ajuda |
| Git e GitHub | faço/uso com ajuda |

#### Soft Skills

Usei **proatividade** e **comunicação** logo na apresentação da primeira sprint. O grupo estava muito nervoso e ninguém queria apresentar, então eu me dispus a apresentar o trabalho da equipe, mesmo tendo que improvisar em cima da hora, e garanti que a entrega fosse mostrada ao cliente.

</details>

<details>
<summary>Code Wave - Assistente virtual que responde perguntas sobre documentos</summary>

### Segundo Semestre – 2023-2

#### Empresa Parceira

Fatec São José dos Campos. O professor Giuliano Araujo Bertoti atuou como cliente e foi o responsável pelos requisitos.

#### Problema

Informações importantes de uma organização costumam ficar espalhadas em documentos longos, como manuais, normas e relatórios. Para encontrar uma resposta específica, a pessoa precisa abrir o arquivo certo e ler ou buscar trechos manualmente, o que consome tempo e muitas vezes leva a respostas incompletas ou imprecisas. Quanto maior e mais técnico o documento, mais difícil é localizar rapidamente a informação de que se precisa.

#### Solução

Para resolver o problema proposto, a equipe Code Wave desenvolveu o **Code Wave**, uma **aplicação desktop** que funciona como assistente virtual. O usuário faz login, importa um documento e escreve uma pergunta em linguagem natural, e o assistente responde com base no conteúdo desse documento. Para isso, o texto é dividido em parágrafos, convertido em vetores (embeddings) por um modelo da Hugging Face e consultado por meio de geração aumentada por recuperação (RAG), técnica que entrega ao modelo de linguagem apenas os trechos relevantes para a pergunta. O histórico de uso fica registrado em um banco de dados MySQL e pode ser consultado em uma tela própria.

#### Link do Repositório Git

[github.com/felipereira10/Code-Wave-2-API](https://github.com/felipereira10/Code-Wave-2-API)

#### Tecnologias Utilizadas

| Tecnologia | Onde foi utilizada |
| --- | --- |
| Java | Linguagem de toda a aplicação |
| Java Swing | Telas de login, cadastro, importação de documentos, busca e histórico |
| LangChain4j | Cadeia de perguntas e respostas com recuperação de trechos do documento (RAG) |
| Hugging Face (all-MiniLM-L6-v2 e modelo de chat) | Geração dos embeddings dos parágrafos e das respostas em linguagem natural |
| MySQL e JDBC | Armazenamento e consulta do histórico de uso |
| Gradle | Gerenciamento de dependências e build do projeto |
| Figma | Protótipo das telas |
| Git e GitHub | Versionamento e entregas das sprints por tags |

#### Contribuições Pessoais

Nesse projeto atuei como desenvolvedor (Dev Team) da equipe Code Wave e fui responsável pelo núcleo de inteligência artificial do assistente. Na primeira sprint, implementei em Java, com a biblioteca LangChain4j, o fluxo de perguntas e respostas sobre um documento. Nesse fluxo, o texto é dividido em parágrafos, transformado em embeddings pelo modelo all-MiniLM-L6-v2 da Hugging Face, armazenado em um repositório vetorial em memória e consultado por uma cadeia de recuperação conversacional que envia ao modelo de chat apenas os trechos relevantes. Na segunda sprint, criei a tela de importação de documentos em Java Swing, com seleção de arquivo e campo de pergunta ligados a esse fluxo. Na última sprint, desenvolvi a tela de histórico de uso, com o modelo de dados do registro e a classe de conexão JDBC com o MySQL. Também reorganizei o projeto em pacotes de conexão, modelos e telas, integrei ao back-end as telas de login, cadastro, busca e importação criadas pelos colegas e migrei a configuração do Gradle.

#### Hard Skills

| Tecnologia | Nível de proficiência |
| --- | --- |
| Java | faço/uso com autonomia |
| Java Swing | faço/uso com autonomia |
| LangChain4j e RAG | faço/uso com ajuda |
| MySQL e JDBC | faço/uso com ajuda |
| Gradle | faço/uso com ajuda |
| Git e GitHub | faço/uso com ajuda |

#### Soft Skills

Usei **proatividade** e **solução de problemas** quando ninguém da equipe conseguia conectar as telas do front-end ao back-end. A dificuldade vinha da linguagem Java e das IDEs, já que as telas tinham sido feitas no NetBeans e o back-end estava em outro projeto. Assumi essa tarefa e fiz a integração, reorganizando o código em pacotes de conexão, modelos e telas e trazendo as telas dos colegas para o projeto do back-end, que passou a funcionar como uma aplicação única.

</details>

<details>
<summary>Diagnóstico Inteligente - Plataforma de diagnóstico de treinamentos para a Entrenova</summary>

### Terceiro Semestre – 2025-2

#### Empresa Parceira

Entrenova, empresa da área de educação corporativa que oferece trilhas de capacitação para empresas e suas equipes.

#### Problema

Antes de contratar um programa de capacitação, as empresas clientes da Entrenova raramente conseguem apontar com precisão onde estão seus principais problemas. Sem esse levantamento, a indicação de treinamento fica genérica e o cliente tem dificuldade de perceber o valor do serviço antes de comprar. Além disso, analisar cada empresa de forma personalizada exige um tempo que a Entrenova não consegue dedicar a todos os contatos que chegam.

#### Solução

Para resolver o problema proposto, a equipe DeepCode desenvolveu o **Diagnóstico Inteligente de Treinamentos e Mercado**, uma **aplicação web**. O gestor responde a um formulário único que avalia quatro dimensões da empresa e, a partir das respostas, um modelo de IA (Google Gemini) gera um relatório de diagnóstico personalizado. Uma dimensão é liberada gratuitamente e as outras três ficam bloqueadas, com uma chamada para compra. O gestor recebe o link do relatório por e-mail, escolhe um plano (Ouro, Diamante ou Premium) e, após o pagamento, desbloqueia o relatório completo e um painel com trilhas, aula de exemplo, gestão da conta e da equipe e um chatbot de dúvidas.

#### Link do Repositório Git

[github.com/API-DeepCode/API3_Entrenova](https://github.com/API-DeepCode/API3_Entrenova)

#### Tecnologias Utilizadas

| Tecnologia | Onde foi utilizada |
| --- | --- |
| Next.js e React | Páginas da aplicação e rotas de API, como a de geração do diagnóstico |
| TypeScript | Linguagem de todo o front-end e das rotas de API |
| Tailwind CSS e Radix UI (shadcn/ui) | Estilização e componentes da interface |
| Firebase (Firestore) | Armazenamento das respostas dos formulários e dos relatórios |
| Google Gemini | Geração dos diagnósticos personalizados a partir das respostas do formulário |
| Nodemailer | Envio automático do e-mail com o link do relatório |
| PDFKit | Geração do relatório em PDF enviado por e-mail |
| Git e GitHub | Versionamento do código e documentação das sprints |

#### Contribuições Pessoais

Nesse projeto atuei como desenvolvedor (Team Member) da equipe DeepCode, no front-end da aplicação, com Next.js, React e TypeScript. Desenvolvi a tela de pagamento, etapa do fluxo de compra dos planos. A página identifica pela URL o plano escolhido (Ouro, Diamante ou Premium), apresenta o resumo com preço e benefícios e traz o formulário de dados do cartão, com máscaras para número, validade e código de segurança. Ao confirmar, a tela simula o processamento e redireciona para a rota de retorno do pagamento, que libera o relatório completo. Também liguei a página inicial a esse novo fluxo e criei a folha de estilos própria da tela.

#### Hard Skills

| Tecnologia | Nível de proficiência |
| --- | --- |
| Next.js e React | faço/uso com ajuda |
| TypeScript | faço/uso com autonomia |
| CSS | faço/uso com autonomia |
| Git e GitHub | faço/uso com autonomia |

#### Soft Skills

Usei **comunicação** e **empatia** em um momento em que a equipe estava perdida em relação ao que o cliente pedia e ao que iríamos entregar, e as reuniões ficaram tensas. Durante essas reuniões, procurei acalmar os colegas mais exaltados e manter a conversa produtiva. Com os ânimos mais calmos, conseguimos clarear as ideias e alinhar o que seria entregue.

</details>

<details>
<summary>Sistema JJM Log - Plataforma de integração de setores e atividades</summary>

### Quarto Semestre – 2024-2

#### Empresa Parceira

JJM Log, empresa do setor de logística.

#### Problema

Na JJM Log, as informações e as atividades dos diferentes setores ficam dispersas. Comunicados, escalas e horários, documentos dos colaboradores, instruções de cada função e checklists de saída e retorno de veículos circulam por canais diferentes, sem um ponto central de consulta. Isso dificulta a integração entre os setores e o acompanhamento das tarefas, e faz com que novos colaboradores dependam de outras pessoas para aprender a própria rotina.

#### Solução

Para resolver o problema proposto, a equipe DriftOps desenvolveu o **Sistema JJM Log**, uma **aplicação web** que reúne em um só lugar as informações e as atividades da empresa. Os administradores cadastram usuários, clientes e veículos e anexam documentos aos perfis. Os colaboradores acessam uma página inicial com informações da empresa e atalhos, seu perfil com documentos, informativos, escalas e tutoriais por função, agenda de reuniões, quadro de tarefas, chat por equipes e uma página de estatísticas com gráficos. No cadastro, o administrador define se cada novo usuário terá perfil de administrador ou de colaborador, e as telas foram pensadas também para o acesso pelo celular.

#### Link do Repositório Git

[github.com/DriftOps/API-IV](https://github.com/DriftOps/API-IV) (front-end em [API-IV_Front-end](https://github.com/DriftOps/API-IV_Front-end))

#### Tecnologias Utilizadas

| Tecnologia | Onde foi utilizada |
| --- | --- |
| React e TypeScript | Páginas, componentes e navegação do front-end |
| React Router | Rotas entre as páginas do sistema |
| Ant Design, Materialize e Font Awesome | Componentes visuais e ícones da interface |
| Chart.js (react-chartjs-2) | Gráficos da página de estatísticas |
| Axios | Comunicação do front-end com a API |
| Node.js e Express | API do back-end, com as operações de cadastro de usuários, clientes e processos |
| MySQL | Banco de dados do sistema |
| Figma | Wireframe e protótipo navegável |
| Trello e Slack | Organização das tarefas e comunicação da equipe |
| Git e GitHub | Versionamento do front-end e do back-end em repositórios separados |

#### Contribuições Pessoais

Nesse projeto atuei como desenvolvedor (Dev Team) da equipe DriftOps, no front-end, com React e TypeScript. Criei a tela de perfil do colaborador e, nela, o botão de seleção de arquivos para a importação de documentos. Desenvolvi a página de tarefas, com cards por categoria em que o usuário adiciona e seleciona tarefas, que ficam salvas no navegador (localStorage). Na página de estatísticas, implementei gráficos de pizza e de barras com Chart.js e react-chartjs-2. Também criei o chat por equipes na barra lateral, em que o usuário escolhe a equipe, troca mensagens e anexa arquivos, registrei as novas páginas no roteador da aplicação e ajustei o layout do rodapé e do perfil.

#### Hard Skills

| Tecnologia | Nível de proficiência |
| --- | --- |
| React | faço/uso com autonomia |
| TypeScript | faço/uso com ajuda |
| CSS | faço/uso com autonomia |
| Chart.js | faço/uso com ajuda |
| Git e GitHub | faço/uso com autonomia |

#### Soft Skills

Usei o **trabalho em equipe** quando um colega do front-end estava com dificuldades em React e CSS. Como eu já vinha trabalhando nas páginas de perfil, tarefas e estatísticas, ajudei esse colega com o que tinha aprendido nelas, para que a parte dele também avançasse e o grupo mantivesse o ritmo das entregas.

</details>

<details>
<summary>SyncDesk - Sistema de atendimento, triagem e escalonamento de chamados</summary>

### Quinto Semestre – 2026-1

#### Empresa Parceira

Pro4Tech, empresa de tecnologia e consultoria.

#### Problema

No atendimento ao cliente, as solicitações chegam sem nenhuma triagem inicial e as conversas não ficam registradas em um histórico único. Com isso, é difícil saber em que etapa cada chamado está, quem é o responsável por ele e quando foi escalonado ou encerrado. Os clientes precisam repetir informações a cada contato, e os gestores não têm dados confiáveis para acompanhar o desempenho da equipe de suporte.

#### Solução

Para resolver o problema proposto, a equipe Titus Systems desenvolveu o **SyncDesk**, um sistema de atendimento formado por um **aplicativo mobile** para o cliente e uma **aplicação web** para atendentes e administradores, ambos ligados a uma API central. O cliente abre o atendimento pelo aplicativo, passa por uma triagem automatizada com perguntas e botões de resposta e depois conversa em tempo real com o atendente. Os chamados têm ciclo de vida completo (abertura, atribuição, escalonamento e encerramento), com busca no histórico, notificações, avaliação ao final do atendimento e dashboards de auditoria.

<img src="https://raw.githubusercontent.com/Titus-System/SyncDesk/main/docs/diagramas/arquitetura.png" width="600" alt="Arquitetura do SyncDesk">

#### Link do Repositório Git

[github.com/Titus-System/SyncDesk](https://github.com/Titus-System/SyncDesk) (aplicativo mobile em [syncdesk-mobile](https://github.com/Titus-System/syncdesk-mobile))

#### Tecnologias Utilizadas

| Tecnologia | Onde foi utilizada |
| --- | --- |
| React Native, Expo e TypeScript | Aplicativo mobile do cliente |
| NativeWind (Tailwind CSS) | Estilização do aplicativo mobile |
| React, Vite e React Query | Aplicação web de atendentes e administradores |
| Python, FastAPI e SQLAlchemy | API central, com as regras de negócio, os chamados e a triagem |
| PostgreSQL | Usuários, chamados e permissões |
| MongoDB | Mensagens e interações do chat |
| WebSocket | Chat em tempo real entre cliente e atendente |
| JWT e Expo SecureStore | Autenticação, controle de acesso por perfil e armazenamento seguro dos tokens no aparelho |
| Axios e npm | Biblioteca própria que padroniza a comunicação dos front-ends com a API |
| Docker | Execução dos serviços |
| Pytest | Testes automatizados da API |
| Grafana | Monitoramento e métricas |
| Figma | Protótipos das telas |
| Git e GitHub | Versionamento e organização das tarefas |

#### Contribuições Pessoais

Nesse projeto atuei como desenvolvedor (Dev Team) no aplicativo mobile, em React Native com Expo e TypeScript. Implementei o fluxo completo de redefinição de senha, com as telas de "Esqueci minha senha", de nova senha e de confirmação, integradas ao endpoint de recuperação da API. Também adicionei uma guarda de rota no layout principal, que leva o usuário de volta ao login quando o token é recusado, e configurei o armazenamento dos tokens de acesso no Expo SecureStore. Na tela de login, incluí o aceite obrigatório dos Termos de Uso, com caixa de seleção e o texto dos termos, corrigi um problema de acesso e atualizei a tela de perfil. Melhorei ainda a navegação e a barra de ferramentas das telas de conversas e de solicitações. No chat, implementei o envio de arquivos com a biblioteca expo-document-picker e a exibição do nome do atendente, por meio de hooks próprios e da conexão WebSocket do chat.

#### Hard Skills

| Tecnologia | Nível de proficiência |
| --- | --- |
| React Native e Expo | faço/uso com autonomia |
| TypeScript | faço/uso com autonomia |
| NativeWind (Tailwind CSS) | faço/uso com autonomia |
| WebSocket | faço/uso com ajuda |
| Consumo de APIs REST | faço/uso com autonomia |
| Git e GitHub | faço/uso com autonomia |

#### Soft Skills

Usei **proatividade** e **solução de problemas** logo que cheguei à equipe, quando a redefinição de senha do aplicativo estava atrasada. Estudei como implementar esse fluxo e entreguei as telas de "Esqueci minha senha", de nova senha e de confirmação, integradas à API, dentro do prazo da primeira sprint (05/04/2026).

</details>

<details>
<summary>Synapse - Simulação de regras de comissionamento com inteligência artificial</summary>

### Sexto Semestre – 2026-2

#### Empresa Parceira

Dom Rock, empresa de tecnologia em dados e inteligência artificial, sediada no Parque de Inovação Tecnológica de São José dos Campos.

#### Problema

As regras de comissionamento de vendas mudam com frequência, com novos produtos, campanhas, metas e acordos comerciais. Na maioria das empresas, essas regras não são registradas de forma estruturada. O conhecimento fica com poucas pessoas, regras novas entram em conflito com as antigas e não há rastreabilidade de quem decidiu o quê. Além disso, a área de recursos humanos só descobre o impacto financeiro de uma nova regra depois que ela já está em vigor.

#### Solução

Para resolver o problema proposto, a equipe Titus Systems desenvolveu o **Synapse**, uma **aplicação web** com arquitetura orientada a eventos. O profissional de RH descreve a nova regra de comissionamento por voz ou texto. Agentes de IA, construídos com LangGraph, extraem os parâmetros da regra, pedem a confirmação do usuário e geram o código correspondente. Esse código é executado em um container Docker isolado, sobre os dados históricos reais da empresa, e o resultado é comparado com o cenário atual e com o orçamento. Se a regra não for viável, o sistema sugere adaptações. Todas as decisões do modelo ficam registradas em uma trilha de auditoria, com explicações para o auditor.

#### Link do Repositório Git

[github.com/Titus-System/synapse](https://github.com/Titus-System/synapse)

#### Tecnologias Utilizadas

| Tecnologia | Onde foi utilizada |
| --- | --- |
| Vue 3, TypeScript e Vite | Interface web para envio das regras, acompanhamento dos jobs e visualização dos resultados |
| Java 21 e Spring Boot | API REST, com o estado dos jobs, as atualizações em tempo real e as migrations do banco |
| Python e LangGraph | Serviço codegen, que interpreta as propostas, extrai os parâmetros, gera e explica as regras |
| Python | Serviço worker, que executa as regras e confere os resultados das simulações |
| Docker | Sandbox efêmero e isolado para executar o código gerado |
| RabbitMQ | Comunicação assíncrona entre API, codegen e worker |
| PostgreSQL | Jobs, regras, resultados, artefatos e trilha de auditoria |
| Keycloak | Login e controle de acesso por papel (profissional de RH e auditor) |
| OpenTelemetry, Grafana, Loki e Prometheus | Observabilidade, com logs, métricas e rastreamento |
| JUnit e pytest | Testes automatizados da API (Java) e dos serviços em Python |
| GitHub Actions | Validação automática dos contratos entre os serviços |
| Git e GitHub | Versionamento, branches por tarefa e pull requests |

#### Contribuições Pessoais

Nesse projeto atuei como desenvolvedor (Dev Team) e trabalhei nos três serviços de back-end. Defini o contrato entre o harness de execução e o código gerado pela IA, com documentação, scripts de teste e de validação da saída e um workflow no GitHub Actions que valida os contratos a cada alteração, e criei a regra de referência com o resultado esperado, usada como base de comparação. Na API em Java 21 com Spring Boot, implementei o endpoint `POST /jobs/{id}/parameters`, no qual o usuário confirma os parâmetros extraídos da regra, e o consumidor RabbitMQ da mensagem `regra-extraida`, que reabre o ciclo do job a partir da versão raiz da regra. Também implementei a consulta do detalhamento da simulação por competência e matrícula e a gravação, na trilha de auditoria, do resultado sobre o qual cada etapa agiu. No codegen, em Python com LangGraph, implementei a validação de completude e coerência da regra, a publicação dos conflitos encontrados e a extração do construto de exclusão a partir do texto. No worker, criei os casos de geração com o avaliador do código gerado e a conferência das quebras do resultado. Todas essas entregas foram acompanhadas de testes automatizados (JUnit e pytest) e de documentação.

<details>
<summary><b>Detalhes</b></summary>

| Serviço | Entrega | Tecnologias |
| --- | --- | --- |
| Contratos | Contrato entre o harness e o código gerado, com os scripts `testar-contrato.py` e `validar-saida.py` e o workflow `validar-contratos.yml` | Python, GitHub Actions |
| Contratos | Regra de referência e resultado esperado (T-036) | Python, JSON |
| API | Endpoint `POST /jobs/{id}/parameters` para confirmação dos parâmetros, com testes de controller e de persistência | Java 21, Spring Boot, JUnit |
| API | Consumidor de `regra-extraida`, que reabre o ciclo com a versão raiz e registra métricas | Spring Boot, RabbitMQ |
| API | Quebras absolutas na consulta do job e detalhamento da simulação por competência e matrícula | Spring Boot, PostgreSQL |
| API | Gravação, na trilha de auditoria, do resultado sobre o qual a etapa agiu, com migration SQL (T-301) | Spring Boot, SQL |
| Codegen | Validação de completude e coerência da representação da regra | Python, pytest |
| Codegen | Nó do grafo que publica os conflitos da validação e encerra o ciclo sem falha | LangGraph, RabbitMQ |
| Codegen | Extração do construto de exclusão a partir do texto (T-205) | Python, pytest |
| Worker | Casos de geração e avaliador do código gerado | Python, pytest |
| Worker | Conferência do detalhamento e das quebras do resultado (T-262) | Python, pytest |

</details>

#### Hard Skills

| Tecnologia | Nível de proficiência |
| --- | --- |
| Java e Spring Boot | faço/uso com autonomia |
| Python | faço/uso com autonomia |
| LangGraph | faço/uso com autonomia |
| RabbitMQ | faço/uso com ajuda |
| PostgreSQL e migrations SQL | faço/uso com autonomia |
| JUnit e pytest | faço/uso com autonomia |
| GitHub Actions | faço/uso com ajuda |
| Git e GitHub | consigo ensinar |

#### Soft Skills

Usei **resiliência** e **atitude positiva** na tarefa de extração do construto de exclusão a partir do texto (T-205), quando minha primeira entrega precisou ser corrigida depois da revisão. Reagi de forma profissional, conversei com o Scrum Master da equipe, Pedro Garcia, para entender exatamente qual era o problema e entreguei novamente. Nas correções, ajustei a extração para manter o núcleo da regra como o usuário o descreveu e preservar a condição de limiar ao habilitar a exclusão, além de restaurar a ordem de registro dos construtos.

</details>
