# Projeto de Sistema de Gestão de planos de telefonia com Dashboard

Este projeto consiste em um sistema de gerenciamento de planos contratados por clientes, onde cada cliente pode ter um ou mais planos associados. O sistema também permite consultar informações sobre planos e clientes, com a estrutura e a arquitetura planejadas para serem escaláveis e de fácil manutenção.

## Como Rodar o Projeto

### Requisitos para o Projeto

- **Node.js** (versão 14 ou superior)
- **NPM** (gerenciador de pacotes do Node.js)
- **VSCode** (recomendado, mas não obrigatório)

### Passos

1. **Clone o repositório:** _git clone https://github.com/usuario/nome-do-repositorio.git_
2. **Instale as dependências do projeto:** Navegue até o diretório do projeto e execute o comando: _npm install_
3. **Execute o projeto:** Para rodar o servidor localmente, use o comando: _npm start_ (Caso não for, procure o Go Live do seu VS Code e clique nele até abrir)
4. **Opção B:** Gravei o funcionamento e postei no Youtube, você poderá assistir clicando aqui. (Vou colocar jajá)
5. **Opção C:** Me chame para uma video-chamada e ficarei feliz em mostrar seu funcionamento!


## Decisões Técnicas e Estrutura do Código

- **Backend Mocado pelo db.json:**
A estrutura do back-end é a seguinte, com relação N:N entre Clientes e Planos: ![image](https://github.com/user-attachments/assets/6e634e77-4ea5-41cb-913f-9a263a82d88e)

### Estrutura de arquivos

A estrutura de arquivos do projeto é a seguinte:
- **db.json**: É o back-end mockado.
- **index.html**: É a tela principal, o dashboard interativo, exibe a visão geral dos clientes, planos contratados e possui filtro de acordo com o período.
- **tela2.html**: É a tela de gerenciamento de planos, onde os planos podem ser gerenciados, buscados, editados, excluidos e visualizados (CRUD).
- **tela3.html**: É a tela de gerenciamento de clientes, onde os clientes podem ser gerenciados, buscados, editados, excluidos e visualizados (CRUD).
- **tela4.html**: É a tela interativa para associar clientes a planos de forma visual (drag-and-drop).
- **package-lock.json**: É gerado automaticamente quando você executa o comando npm install em um projeto Node.js que usa o npm (Node Package Manager).
- **package.json**: Principal pacote com as dependências.

# Telas

### Dashboard
![image](https://github.com/user-attachments/assets/906d08e6-76ce-44f7-94d1-82cb50ff341c)
![image](https://github.com/user-attachments/assets/1ed7a244-8e45-4177-8952-aabf9fca6598)
![image](https://github.com/user-attachments/assets/46215f49-ecac-42ee-b80c-8fce42801c5b)
![image](https://github.com/user-attachments/assets/e5f936f8-5bd4-45ec-8f16-052afb1ed4e5)
![image](https://github.com/user-attachments/assets/2a359c0b-506d-4f92-9ea8-0b192ab822f8)
![image](https://github.com/user-attachments/assets/245d8bf5-9367-4a4f-a1c4-aab240b270be)
![image](https://github.com/user-attachments/assets/513d0475-e75d-400d-a57c-feab56ddf5c3)

### Gerenciamento de Planos
![image](https://github.com/user-attachments/assets/7a12d0e0-3e93-464a-8daa-6a5bdda79857)
![image](https://github.com/user-attachments/assets/85c1d76d-9f3f-4331-bbbe-724c4a634cf0)

### Gerenciamento de Clientes
![image](https://github.com/user-attachments/assets/8029a08f-e649-4c82-b1f3-47a561d84a35)
![image](https://github.com/user-attachments/assets/960f5bc0-9041-4fd6-9391-ae0ac4cfad83)

### Associação de Clientes a Plano
![image](https://github.com/user-attachments/assets/5c730498-2144-411f-be87-b53f7fe35e3f)
![image](https://github.com/user-attachments/assets/e5c8a4ac-de8a-4a7b-bb07-b6f9eb787666)










