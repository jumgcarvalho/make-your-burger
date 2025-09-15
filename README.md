# Monte seu Burger - Projeto com Vue.js e JSON Server

![Status](https://img.shields.io/badge/status-concluído-brightgreen)

Projeto desenvolvido como parte dos estudos de Vue.js 3, focado em praticar conceitos fundamentais como componentização, consumo de APIs, diretivas, reatividade e ciclo de vida dos componentes.

A aplicação permite que o usuário monte um hambúrguer personalizado, escolhendo os ingredientes, e depois gerencie os pedidos em um dashboard, simulando o fluxo de uma hamburgueria.

---

### ✅ Funcionalidades

-   **Montagem de Pedidos:** Formulário para criar um novo hambúrguer escolhendo pão, carne e opcionais.
-   **Dashboard de Pedidos:** Visualização de todos os pedidos feitos em uma tabela.
-   **Gerenciamento de Status:** Atualização do status de cada pedido (Ex: "Solicitado", "Em produção", "Finalizado").
-   **Remoção de Pedidos:** Possibilidade de cancelar/deletar um pedido do sistema.
-   **Feedback ao Usuário:** Mensagens de notificação para ações como criação e atualização de pedidos.

---

### 💻 Tecnologias Utilizadas

-   **Vue.js 3:** Framework principal para a construção da interface.
-   **Vue Router:** Para gerenciamento das rotas da aplicação (Home, Dashboard).
-   **JSON Server:** Para simular uma API RESTful completa e persistir os dados localmente em um arquivo `db.json`.
-   **HTML5** e **CSS3:** Estruturação e estilização da aplicação.

---

### 🛠️ Como Rodar o Projeto

Para executar este projeto em sua máquina local, siga os passos abaixo.

#### Pré-requisitos

-   [Node.js](https://nodejs.org/en/) (versão 16 ou superior)
-   [NPM](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/)

#### Passos para Instalação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    ```

2.  **Navegue até o diretório do projeto:**
    ```bash
    cd seu-repositorio
    ```

3.  **Instale as dependências do projeto:**
    ```bash
    npm install
    ```

#### Executando a Aplicação

Para que a aplicação funcione corretamente, você precisa iniciar **dois servidores simultaneamente** em terminais diferentes: o backend (JSON Server) e o frontend (Vue.js).

1.  **Inicie o Backend (JSON Server):**
    *Abra um terminal e execute o comando abaixo. Ele irá observar o arquivo `db.json` e fornecer uma API na porta 3000.*
    ```bash
    npm run json-server
    ```

2.  **Inicie o Frontend (Vue.js):**
    *Abra um **novo terminal** e execute o comando para iniciar o servidor de desenvolvimento do Vue.*
    ```bash
    npm run serve
    ```

3.  **Acesse a aplicação:**
    *Após iniciar os dois servidores, abra seu navegador e acesse:*
    [http://localhost:8080/](http://localhost:8080/)

---

### 👨‍💻 Autor

Desenvolvido por **Júlia Carvalho**

-   **LinkedIn:** [https://www.linkedin/in/jumgcarvalho)
-   **GitHub:** [https://github.com/jumgcarvalho]
