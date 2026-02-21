# Sistema de Agendamento Online - Humana Saúde

## Descrição do Projeto

Sistema web responsivo para agendamento de consultas médicas e exames laboratoriais destinado aos beneficiários do plano de saúde Humana Saúde. O sistema permite que os usuários realizem agendamentos de forma autônoma, visualizem seus próximos compromissos e acessem o histórico completo de atendimentos.

## Objetivos do Sistema

- Permitir agendamento online de consultas e exames
- Oferecer acesso 24/7 via desktop e dispositivos móveis
- Reduzir a dependência de atendimento telefônico
- Facilitar a gestão de agendamentos pelos beneficiários
- Proporcionar visualização de histórico completo de atendimentos

## Funcionalidades

O sistema possui 4 telas principais:

1. **Login** - Autenticação de usuários via CPF e senha
2. **Dashboard** - Visão geral dos próximos agendamentos e estatísticas
3. **Agendamento** - Formulário para agendar consultas e exames
4. **Histórico** - Listagem e filtros de todos os agendamentos realizados

## Tecnologias Utilizadas

### Frontend
- React 18.3.1
- TypeScript
- Tailwind CSS 4.1
- React Router 7.13
- Vite 6.3
- Lucide React

### Backend (Proposto)
- Node.js
- Express.js
- PostgreSQL
- JWT (Autenticação)

### Ferramentas
- Figma Make (Prototipação)
- dbdiagram.io (Modelagem de dados)
- Trello (Gestão de projeto)
- Git/GitHub (Controle de versão)

## Banco de Dados

O sistema utiliza 4 tabelas principais:
- **pacientes** - Cadastro de beneficiários
- **especialidades** - Especialidades médicas e tipos de exames
- **profissionais** - Médicos e laboratórios
- **agendamentos** - Registro de consultas e exames


## Identificação do Aluno

**Nome:** Everton Nascimento Sousa   
**Curso:** ADS - Análise e Desenvolvimento de Sistemas
**Instituição:** UEMA - Universidade Estadual do Maranhão 
**Disciplina:** Projeto de Software 
**Professor:** Wesley Dominices 

## Observações

Este é um protótipo educacional desenvolvido com dados simulados. Para uso em produção seria necessário implementar backend completo, banco de dados real e medidas de segurança adequadas.

## Licença

Projeto desenvolvido para fins educacionais - 2026
