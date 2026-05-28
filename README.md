# AI Refund Analysis System with n8n

Sistema inteligente de análise automatizada de pedidos de reembolso utilizando IA, n8n, Google Gemini, Gmail, Telegram e Google Sheets.

---

# Visão Geral

Este projeto automatiza o processo de análise de solicitações de reembolso recebidas via webhook.

A inteligência artificial interpreta a solicitação, identifica cenários específicos e executa ações automáticas de comunicação e encaminhamento.

O fluxo inclui:
- Análise automática de contexto
- Identificação de clientes VIP
- Validação de prazo de garantia
- Encaminhamento inteligente
- Envio automático de e-mails
- Notificações via Telegram
- Estrutura de decisão automatizada

---

# Cenário do Projeto

Empresas que trabalham com produtos digitais normalmente recebem diversos pedidos de reembolso diariamente.

Grande parte desses casos exige:
- análise manual
- validação de prazo
- verificação de cliente
- comunicação com financeiro
- resposta ao cliente

Além do tempo operacional, isso gera:
- demora no atendimento
- sobrecarga da equipe
- inconsistência na comunicação
- baixa escalabilidade

Pensando nisso, desenvolvi um fluxo inteligente utilizando IA para automatizar a análise e comunicação desses pedidos.

---

# Mensagem recebida via Telegram

![Mensagem Telegram](./imagens/mensagem-telegram.jpeg)

---

# Workflow completo no n8n

![Fluxo Completo](./imagens/fluxo-completo.png)

---

# Execução do fluxo

![Fluxo Sucesso](./imagens/fluxo-sucesso.png)

---

# E-mail automático enviado ao cliente

![E-mail Reembolso](./imagens/email-reembolso.png)

---

# Tecnologias Utilizadas

- n8n
- Google Gemini AI
- Gmail
- Telegram
- Google Sheets
- Structured Output Parser
- IA Generativa

---

# Fluxo da Automação

1. Solicitação recebida via Webhook
2. IA analisa o pedido de reembolso
3. Sistema identifica:
   - prazo expirado
   - perfil do cliente
   - contexto da solicitação
4. Workflow executa decisões condicionais
5. E-mail automático enviado ao cliente
6. Equipe interna notificada via Telegram
7. Fluxo registra e organiza o atendimento

---

# Funcionalidades

## Análise Inteligente
- Interpretação automática da solicitação
- Identificação de clientes VIP
- Classificação contextual

## Comunicação Automatizada
- Respostas automáticas por e-mail
- Notificações via Telegram
- Mensagens personalizadas

## Estrutura de Decisão
- Fluxos condicionais
- Tratamento automático de exceções
- Encaminhamento inteligente

## Operação Automatizada
- Workflow sem intervenção manual
- Escalabilidade operacional
- Padronização do atendimento

---

# Melhorias Futuras

- Dashboard de solicitações
- Histórico de reembolsos por cliente
- Integração com CRM
- Registro automático em planilha
- Aprovação humana antes do envio
- SLA automático
- Banco vetorial
- Multiagentes IA

---

# Autor

## Murilo Guimarães Costa

Especialista em Projetos, Automação e IA Aplicada.

### Áreas de atuação
- Open Finance
- Gestão de Projetos
- Inteligência Artificial
- n8n Automation
- Integrações

### GitHub
https://github.com/Murilo58
