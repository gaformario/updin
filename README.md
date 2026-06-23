# Updin: Plataforma de Educação Financeira para Adolescentes

O **Updin** é uma plataforma mobile de educação financeira voltada para adolescentes, com foco no aprendizado prático sobre mesada, consumo consciente, planejamento financeiro e autonomia no uso do dinheiro.

A solução combina **gamificação**, **gestão de mesada**, **missões**, **quizzes educativos**, **ranking** e **acompanhamento parental**, permitindo que responsáveis acompanhem o progresso dos adolescentes e incentivem hábitos financeiros mais saudáveis desde cedo.

## Sobre o projeto

O projeto foi desenvolvido como parte do PGT, com o objetivo de criar um MVP funcional de uma aplicação mobile para educação financeira familiar.

A plataforma possui dois perfis principais de usuário:

- **Responsável:** pode configurar mesadas, criar missões, validar atividades e acompanhar o progresso financeiro e educativo do adolescente.
- **Adolescente:** pode visualizar saldo, consultar extrato, cumprir missões, responder quizzes, acompanhar conquistas e evoluir no ranking.

## Repositórios

- [Frontend mobile](https://github.com/gaformario/updin-frontend-mobile)
- [Backend API](https://github.com/gaformario/updin-backend-api)

## Tecnologias utilizadas

### Frontend Mobile

- React Native
- Expo
- TypeScript

### Backend

- Node.js
- NestJS
- Prisma ORM
- PostgreSQL
- JWT

### Infraestrutura e DevOps

- Docker
- GitHub Actions (CI/CD)
- AWS EC2
- AWS RDS PostgreSQL

## Funcionalidades principais

- Cadastro e autenticação de usuários
- Separação entre perfil de responsável e adolescente
- Gestão de mesada fixa e variável
- Criação e validação de missões
- Consulta de saldo e extrato
- Quizzes educativos
- Sistema de pontuação e ranking
- Notificações
- Acompanhamento parental

## Arquitetura

O Updin foi estruturado em camadas, com uma aplicação mobile consumindo uma API backend responsável pelas regras de negócio, autenticação, persistência dos dados e comunicação com o banco PostgreSQL.

A infraestrutura do MVP utiliza serviços da AWS, com backend hospedado em EC2 e banco de dados PostgreSQL gerenciado no RDS.

## Autores

- Dylan Marques Ashby
- Gabriel Gonçalves Formario
- Luiz Guilherme Machado Bueno Pereira
- Vinicius Skaf Machado Luz
