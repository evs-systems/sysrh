# 🏢 SysRH — Sistema de Gestão Integrada

Sistema interno de gestão de **Recursos Humanos** e **Financeiro**, desenvolvido para centralizar o controle de colaboradores, pagamentos, empresas e processos administrativos em uma interface moderna e responsiva.

## 🌟 Funcionalidades

### 👥 Gestão de Pessoas
- **Colaboradores** — Cadastro completo com dados pessoais, bancários, documentos e controle de período de experiência (45/90 dias)
- **Férias** — Planejamento, agendamento e acompanhamento de férias com cálculo automático de períodos
- **Benefícios** — Gerenciamento de benefícios por colaborador
- **Estagiários** — Controle de contratos com alertas de vencimento

### 💰 Gestão Financeira
- **Pagamentos** — Programação de pagamentos (salários, boletos, fornecedores), conferência dupla e histórico completo
- **Pagamentos em Massa** — Lançamento simultâneo para múltiplos colaboradores
- **Comprovantes** — Anexo de comprovantes com armazenamento no Firebase Storage
- **Pagamentos Recorrentes** — Suporte a lançamentos mensais automáticos

### 🏢 Gestão Empresarial
- **Empresas** — Cadastro de empresas com CNPJ, contrato social e certificados digitais
- **Certificados** — Alertas automáticos de vencimento (30 dias)
- **Contratos** — Monitoramento de contratos a vencer

### ⚙️ Operacional
- **Dashboard** — Visão geral com estatísticas, aniversariantes, alertas e mensagem motivacional diária
- **Agenda** — Calendário de eventos e compromissos
- **Solicitações** — Registro e acompanhamento de adiantamentos, desligamentos e demais processos
- **Relatórios** — Geração de relatórios com opção de impressão
- **Chat Interno** — Mensagens diretas e grupos por setor com notificações em tempo real
- **Histórico de Logs** — Registro imutável de todas as ações realizadas no sistema

### 🛡️ Administração
- **Controle de Acesso** — Matriz de permissões granular (Ler / Editar / Apagar) por módulo e por usuário
- **Perfis por Setor** — Modelos pré-configurados (Administração, RH, Financeiro)
- **Personalização** — Tema claro/escuro, cores de destaque e papéis de parede por usuário

## 💻 Tecnologias

| Camada | Tecnologia |
|---|---|
| Frontend | React 18 (JSX via Babel Standalone) |
| Estilização | Tailwind CSS (CDN) |
| Ícones | Lucide React |
| Autenticação | Firebase Auth |
| Banco de Dados | Cloud Firestore (tempo real) |
| Armazenamento | Firebase Storage |
| Deploy | GitHub Pages |
| PWA | Service Worker + Web App Manifest |

## 📄 Licença

Uso interno — Todos os direitos reservados.
