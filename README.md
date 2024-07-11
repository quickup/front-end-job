### Desafio Técnico: Implementação de Interface de Cadastro de Funcionários

Prezado Candidato,

Estamos entusiasmados por tê-lo no nosso processo seletivo para a vaga de Desenvolvedor Frontend. Como parte da avaliação técnica, solicitamos que você implemente uma interface web para a API de cadastros de funcionários, complementando o desafio de backend. A seguir estão os detalhes e requisitos do desafio.

#### Objetivo:
Implementar uma aplicação frontend que consuma a API de cadastros de funcionários previamente implementada. A interface deve permitir listar, criar e editar funcionários, bem como visualizar detalhes específicos de cada funcionário.

#### Requisitos:

##### Tecnologias:
- **Linguagem:** JavaScript ou TypeScript
- **Framework:** Ionic com Angular

##### Funcionalidades da Interface:
1. **Listar Funcionários**
2. **Criar Funcionário**
3. **Editar Funcionário**
4. **Visualizar Detalhes do Funcionário**

##### Especificações da Interface:

1. **Listar Funcionários**
   - **Endpoint:** `GET /employees`
   - **Descrição:** Exibir uma tabela ou lista com todos os funcionários cadastrados.
   - **Colunas:** `name`, `age`, `phone`, `email`, `last_review_summary`

2. **Criar Funcionário**
   - **Endpoint:** `POST /employees`
   - **Descrição:** Exibir um formulário para cadastrar um novo funcionário.
   - **Campos:** `name`, `birth_date`, `address`, `phone`, `email`, `job_title`, `department`
   - **Ação:** Submeter os dados via API para criar o funcionário e atualizar a lista de funcionários.

3. **Editar Funcionário**
   - **Endpoint:** `PUT /employees/{id}`
   - **Descrição:** Exibir um formulário preenchido com os dados do funcionário para edição.
   - **Campos:** `name`, `birth_date`, `address`, `phone`, `email`, `job_title`, `department`
   - **Ação:** Submeter os dados via API para atualizar o funcionário e atualizar a lista de funcionários.

4. **Visualizar Detalhes do Funcionário**
   - **Endpoint:** `GET /employees/{id}`
   - **Descrição:** Exibir uma página ou modal com os detalhes completos do funcionário, incluindo o histórico de avaliações.
   - **Campos:** `name`, `birth_date`, `address`, `phone`, `email`, `job_title`, `department`, `last_review_summary`

##### Requisitos Adicionais:
- **Design Responsivo:** A interface deve ser responsiva e funcionar bem em dispositivos móveis e desktops.
- **UX/UI:** A interface deve ser intuitiva e amigável. Utilize boas práticas de design e acessibilidade.
- **Validação de Formulário:** Implemente validações nos formulários de criação e edição para garantir que todos os campos obrigatórios sejam preenchidos corretamente.
- **Tratamento de Erros:** A interface deve exibir mensagens de erro amigáveis em caso de falha nas requisições API.

##### Organização do Projeto:
- Estruture o projeto de maneira clara, seguindo boas práticas de desenvolvimento e estrutura de diretórios.
- Forneça um README com instruções sobre como configurar e executar o projeto, bem como exemplos de uso da interface.

##### Documentação do Ionic:
- Siga as orientações inclusas na [documentação do Ionic](https://ionicframework.com/docs) para garantir que a aplicação esteja alinhada com as melhores práticas e padrões recomendados.

#### Critérios de Avaliação:
- **Corretude e Funcionalidade:** A interface deve atender a todos os requisitos funcionais descritos.
- **Qualidade do Código:** O código deve ser limpo, bem documentado e seguir boas práticas de desenvolvimento.
- **Estrutura do Projeto:** A organização do projeto deve ser clara e modular.
- **UX/UI Design:** A interface deve ser intuitiva, amigável e visualmente agradável.
- **Tratamento de Erros:** A interface deve lidar adequadamente com possíveis erros e exceções.
- **Performance:** A interface deve ser eficiente e responsiva.

#### Submissão:
- Envie o link para o repositório do GitHub com o código do projeto.
- Inclua instruções claras sobre como configurar e executar a aplicação.

Estamos ansiosos para ver sua solução e discutir os resultados na próxima etapa.
