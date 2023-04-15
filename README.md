# Serviço de Notificações

Este é um projeto Node.js que utiliza NestJS com testes, Prisma e microserviços para criar um micro-serviço de notificação, que pode ser usado para notificar outras partes de uma aplicação.

## Funcionalidades

O Serviço de Notificações oferece as seguintes funcionalidades:

- Enviar notificações para outras partes da aplicação através de um serviço de mensageria.
- Criar, editar e excluir notificações.
- Listar notificações.

## Instalação

Para instalar o Serviço de Notificações, siga os seguintes passos:

1.  Clone o repositório.
2.  Instale as dependências com o comando `npm install`.
3.  Configure as variáveis de ambiente no arquivo `.env`.
4.  Execute as migrações do banco de dados com o comando `npm run prisma:migrate`.
5.  Inicie o serviço com o comando `npm run start`.

## Testes

Para executar os testes do Serviço de Notificações, utilize o comando `npm run test`.

## Prisma

O Prisma é uma ferramenta de ORM utilizada neste projeto para gerenciar o banco de dados. Você pode encontrar mais informações sobre o Prisma na [documentação oficial](https://www.prisma.io/docs/).

## Microserviços

O Serviço de Notificações utiliza a arquitetura de microserviços para se comunicar com outras partes da aplicação. Você pode encontrar mais informações sobre microserviços na [documentação do NestJS](https://docs.nestjs.com/microservices/basics).

## Licença

O Serviço de Notificações possui [licença MIT](https://chat.openai.com/LICENSE).
