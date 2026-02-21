# Sistema de Agendamento Online - Humana Saúde

## Descrição do Projeto

Sistema web responsivo para agendamento de consultas médicas e exames laboratoriais destinado aos beneficiários do plano de saúde Humana Saúde. O sistema permite que os usuários realizem agendamentos de forma autônoma através de um calendário visual interativo, visualizem seus próximos compromissos e acessem o histórico completo de atendimentos.

## Objetivos do Sistema

- Permitir agendamento online de consultas e exames com calendário visual interativo
- Oferecer acesso 24/7 via desktop e dispositivos móveis
- Reduzir a dependência de atendimento telefônico
- Facilitar a gestão de agendamentos pelos beneficiários
- Proporcionar visualização de histórico completo com filtros avançados
- Oferecer múltiplas formas de autenticação (CPF, email ou carteirinha)

## Funcionalidades

O sistema possui 4 telas principais:

1. **Login** - Autenticação flexível via CPF, email ou número da carteirinha do beneficiário com formatação automática
2. **Dashboard** - Visão geral dos próximos agendamentos com estatísticas e cards informativos
3. **Agendamento** - Sistema em etapas com calendário visual interativo, seleção de horários disponíveis e escolha de profissional
4. **Histórico** - Listagem completa com filtros por tipo, status, busca textual e indicadores visuais de status

### Destaques das Funcionalidades

#### Sistema de Login
- Aceita CPF (com formatação automática xxx.xxx.xxx-xx)
- Aceita email
- Aceita número da carteirinha do beneficiário
- Ícone dinâmico que muda conforme o tipo de entrada
- Validação em tempo real

#### Sistema de Agendamento
- **Fluxo em 4 etapas:** Tipo → Seleção → Agenda → Confirmação
- **Calendário Visual Interativo:** Datas disponíveis destacadas usando react-day-picker
- **Seleção de Horários:** Grid visual com horários disponíveis clicáveis
- **Visualização por Especialidade ou Profissional:** Escolha do médico específico ou qualquer disponível
- **Painel de Resumo:** Acompanhamento em tempo real das seleções
- **Observações Personalizadas:** Campo para informações adicionais

#### Dashboard
- Cards com estatísticas (consultas agendadas, exames pendentes, total de atendimentos)
- Lista de próximos agendamentos
- Avisos e lembretes importantes
- Acesso rápido para novo agendamento

#### Histórico
- Filtros por tipo (consulta/exame)
- Filtros por status (confirmado, concluído, cancelado, pendente)
- Busca textual por especialidade, profissional ou local
- Indicadores visuais de status com ícones e cores
- Resumo estatístico (total, confirmados, concluídos, cancelados)

## Identidade Visual

O sistema segue a identidade visual da Humana Saúde:
- **Cor Principal:** Azul Marinho Escuro (#001B5E)
- **Cor de Destaque:** Laranja (#F7941D)
- **Logo Oficial:** Ícone da Humana Saúde integrado em todas as páginas
- **Design:** Interface moderna, limpa e profissional
- **Responsividade:** Totalmente adaptável para desktop, tablet e mobile

## Tecnologias Utilizadas

### Frontend
- React 18.3.1
- TypeScript
- Tailwind CSS 4.1
- React Router 7.13
- Vite 6.3
- Lucide React (Ícones)
- React Day Picker 8.10.1 (Calendário)
- date-fns 3.6.0 (Manipulação de datas)

### Backend (Proposto)
- Node.js
- Express.js
- PostgreSQL
- JWT (Autenticação)

### Ferramentas
- Figma Make (Prototipação e desenvolvimento)
- dbdiagram.io (Modelagem de dados)
- Trello (Gestão de projeto com 4 sprints)
- Git/GitHub (Controle de versão)

## Banco de Dados

O sistema utiliza 4 tabelas principais:
- **pacientes** - Cadastro de beneficiários (CPF, email, carteirinha, senha, dados pessoais)
- **especialidades** - Especialidades médicas e tipos de exames
- **profissionais** - Médicos e laboratórios vinculados às especialidades
- **agendamentos** - Registro de consultas e exames com data, horário, status e observações

## Melhorias Implementadas

### Interface do Usuário
- ✅ Calendário visual interativo com datas disponíveis destacadas
- ✅ Seleção de horários em formato de grid clicável
- ✅ Login flexível (CPF, email ou carteirinha)
- ✅ Formatação automática de CPF
- ✅ Ícones dinâmicos que se adaptam ao tipo de entrada
- ✅ Painel de resumo em tempo real durante o agendamento
- ✅ Sistema de etapas progressivas no agendamento
- ✅ Filtros avançados no histórico
- ✅ Indicadores visuais de status (confirmado, concluído, cancelado)

### Design e Estética
- ✅ Cores oficiais da Humana Saúde (#001B5E e #F7941D)
- ✅ Logo oficial integrado
- ✅ Interface profissional e corporativa
- ✅ Cards com gradientes e sombras modernas
- ✅ Transições e animações suaves
- ✅ Design totalmente responsivo

## Próximas Funcionalidades (Roadmap)

- [ ] Integração com backend real
- [ ] Autenticação JWT
- [ ] Notificações por email/SMS
- [ ] Cancelamento de agendamentos
- [ ] Reagendamento
- [ ] Upload de documentos/exames
- [ ] Chat com atendimento
- [ ] Integração com sistemas de pagamento
- [ ] Geração de comprovantes em PDF
- [ ] Avaliação de atendimento

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
