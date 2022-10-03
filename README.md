# ViVAGAS

## Motivação
O curso de Ciência da Computação na UFCG possui mais de 10 laboratórios focados em diversas áreas da Ciência da Computação. Com isso, nesses laboratórios se tem vários projetos onde os alunos podem atuar como desenvolvedores e pesquisadores. Desde o primeiro período do curso já surge o questionamento entre os alunos: "Como vou conseguir alguma oportunidade em um desses projetos?" e a resposta por meio dos veteranos do curso e professores é a clássica: "fica de olho no email acadêmico porque pode chegar alguma oportunidade de vagas". De fato, todas as oportunidades abertas para a graduação chegam no email acadêmico, mas infelizmente, por diversos motivos alguns dos emails enviados pelos professores não chegam até os alunos, vão para a caixa de spam ou se perdem entre os outros vários emails recebidos no email acadêmico. 
Com base nessa problématica surgiu a Vitrine de Vagas, o ViVAGAS. Será um sistema web que tem o objetivo de centralizar e exibir todas essas vagas disponíveis nos laboratórios do curso.

## Requisitos Funcionais

### Para os professores

- Cadastro utilizando o email acadêmico @computacao
  - Nome do professor(a)
  - Área de atuação 
  - Laboratório associado
  - Email
- Criação do login
- Cadastro da vaga
  - Título da vaga
  - Área da vaga
  - Laboratório
  - Requisitos
  - Texto descritivo
  - Campo para adição de link para formulário de aplicação na vaga.

### Para os alunos
- Exibição do catálogo de vagas
  - O aluno terá acesso ao link do formulário google enviado pelo professor, para que possa aplicar para a vaga. 
- Filtro de vagas por áreas (frontend, backend, dados e etc)
- Filtro por tecnologia requerida (react.js, angular, python e etc)
- Newsletter
  - O aluno poderá preencher um campo com o seu email acadêmico, para receber um email de alerta sempre que houver uma vaga nova.

## Tecnologias
- JavaScript
- React.js
- Styled Components
- Node.js
- firebase

## Deploy
- O deploy do sistema poderia ser feito utilizando alguma VM do LSD.
- Poderia ser hospedado no domínio ufcg.edu.br
