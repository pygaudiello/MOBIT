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
4. **Opção B:** Gravei o funcionamento e postei no Youtube, você poderá assistir clicando [aqui](https://youtu.be/yvrJsEHyhak)
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
![image](https://github.com/user-attachments/assets/82652d6f-98d5-4eeb-b190-bc00ebe609c2)
![image](https://github.com/user-attachments/assets/02550556-c8a3-4a8d-a5b5-d1e7a3326aae)
![image](https://github.com/user-attachments/assets/1a20058c-a493-4668-8881-22537c557318)
![image](https://github.com/user-attachments/assets/5750bdaf-25ce-44bc-8b71-55e06e915550)
![image](https://github.com/user-attachments/assets/1c91b89b-d8a1-41ca-af10-f9b5276add7b)
![image](https://github.com/user-attachments/assets/0f3698ae-c163-46a8-99ec-6adfe0c9907d)
![image](https://github.com/user-attachments/assets/f917c9fc-4120-4f8a-afb0-5d5b4f0e4e81)


### Gerenciamento de Planos
![image](https://github.com/user-attachments/assets/99408873-5d2f-4abb-9d29-537981da2b93)
![image](https://github.com/user-attachments/assets/8d4371b5-f701-4142-96dd-d4ec4374dc41)
![image](https://github.com/user-attachments/assets/6fb1ee01-1a9b-41b1-84ae-8ec3907dd8d8)


### Gerenciamento de Clientes
![image](https://github.com/user-attachments/assets/9b0e0816-2039-4028-be80-3fa9447209d9)
![image](https://github.com/user-attachments/assets/deab1699-70a6-4a30-9816-b318a1087c69)
![image](https://github.com/user-attachments/assets/3616f802-90e6-4c6e-820c-e41b37482bdb)
![image](https://github.com/user-attachments/assets/1f9571f3-8c70-4aad-ac8d-a713c64541db)



### Associação de Clientes a Plano
![image](https://github.com/user-attachments/assets/5c730498-2144-411f-be87-b53f7fe35e3f)
![image](https://github.com/user-attachments/assets/e5c8a4ac-de8a-4a7b-bb07-b6f9eb787666)










