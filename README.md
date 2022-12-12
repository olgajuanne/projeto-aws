<h1 align="center"> API Node.js com Serverless Framework em ambiente AWS </h1>



## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [AWS](https://aws.amazon.com/pt/)
- JavaScript e JSON
- [Node e NPM](https://nodejs.org/)
- Serverless


## 💻 Projeto

 Neste projeto contém infraestrutura em nuvem AWS com API Gateway, DynamoDB, AWS Lambda e AWS CloudFormation utilizando o framework Serverless para o desenvolvimento baseada em Infraestrutura as a Code. 

## ⚙️ Funcionalidades do projeto

#### Pré requisitos:

- possuir uma conta na AWS e instalar Node.js na máquina.
- Instalar o AWS CLI: https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html

### Setup Inicial

#### Credenciais AWS

- Criar usuário: AWS Management Console -> IAM Dashboard -> Create New User -> <nome do usuário> -> Permissions "Administrator Access" -> Programmatic Access -> Dowload Keys
- No terminal: `aws configure` -> colar as credenciais geradas anteriormente

#### Configurar o framework Serverless

 `npm i -g serverless`

 `serverless deploy -v` 


## :memo: Licença

Esse projeto está sob a licença MIT.

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

---