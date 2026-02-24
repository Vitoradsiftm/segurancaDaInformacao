# 🔐 Política de Segurança da Informação (PSI)
## LocaTech Sistemas

**Versão:** 1.0  
**Responsável:** Gestor de TI  
**Data:** 2026  

---

## 📌 1. Apresentação da Organização

A **LocaTech Sistemas** é uma empresa de desenvolvimento de software especializada em sistemas de gestão para locadoras de filmes. Seu principal produto consiste em um sistema web desenvolvido em Java Spring com banco de dados MySQL, responsável pelo gerenciamento de:

- Clientes
- Filmes
- Funcionários
- Categorias
- Locações

Considerando que o sistema armazena dados pessoais e informações financeiras dos clientes, torna-se essencial garantir a proteção adequada contra ameaças físicas, tecnológicas e humanas.

---

## 🎯 2. Objetivo da Política de Segurança da Informação

Estabelecer diretrizes e normas para a proteção dos ativos da LocaTech Sistemas, assegurando os princípios fundamentais da Segurança da Informação:

- Confidencialidade
- Integridade
- Disponibilidade

Esta política aplica-se a todos os colaboradores, prestadores de serviço e terceiros que possuam acesso aos sistemas ou à infraestrutura tecnológica da empresa.

---

## 🏢 3. Governança de Segurança da Informação

### 3.1 Estrutura de Governança

| Cargo | Responsabilidade |
|--------|------------------|
| Diretor Geral | Aprovação da PSI |
| Gestor de TI | Implementação e monitoramento |
| Administrador de Banco de Dados | Proteção e backup dos dados |
| Desenvolvedores | Garantia de código seguro |
| Colaboradores | Cumprimento das normas |

---

## 💾 4. Ativos Críticos da Organização

### 4.1 Ativos Digitais
- Banco de dados MySQL
- Código-fonte do sistema
- Servidor de aplicação
- Credenciais de acesso
- APIs integradas

### 4.2 Ativos Físicos
- Servidor local
- Roteadores
- Estações de trabalho
- Sala de equipamentos

---

## 📍 5. Locais Críticos Protegidos

- Sala do Servidor
- Sala Administrativa
- Ambiente de Backup
- Repositório GitHub Privado

---

## ⚠️ 6. Análise de Riscos

### 6.1 Ameaças Físicas

| Risco | Impacto | Medida Preventiva |
|--------|----------|-------------------|
| Falta de energia | Indisponibilidade do sistema | Uso de nobreak e gerador |
| Incêndio | Perda total de dados | Detector de fumaça e extintores |
| Alagamento | Danos aos equipamentos | Elevação dos servidores |

---

### 6.2 Ameaças Tecnológicas

| Risco | Impacto | Mitigação |
|--------|----------|-----------|
| SQL Injection | Vazamento de dados | Prepared Statements |
| Ransomware | Perda de dados | Backup diário |
| Ataque DDoS | Indisponibilidade | Firewall |
| Vazamento de senha | Acesso indevido | Autenticação Multifator |

---

### 6.3 Ameaças Humanas

| Risco | Impacto | Mitigação |
|--------|----------|-----------|
| Uso indevido do sistema | Vazamento de dados | Controle de perfis |
| Engenharia social | Roubo de credenciais | Treinamento |
| Sabotagem interna | Danos ao sistema | Logs e auditoria |

---

## 🔒 7. Diretrizes Baseadas na Tríade da Segurança

### 7.1 Confidencialidade

- Controle de acesso baseado em perfis (RBAC)
- Criptografia de senhas com BCrypt
- Conexão segura via HTTPS
- Uso de VPN para acesso remoto
- Política de senhas fortes
- Autenticação Multifator (MFA)

---

### 7.2 Integridade

- Controle de versão no GitHub
- Logs de auditoria
- Backup incremental diário
- Restrição de permissões no banco de dados
- Validação de dados no backend

---

### 7.3 Disponibilidade

- Backup diário automático
- Servidor em nuvem redundante
- Uso de nobreak para proteção elétrica
- Monitoramento de uptime
- Plano de contingência ativo

---

## 🚨 8. Plano de Contingência

### 8.1 Falha Elétrica
- Utilização imediata do nobreak
- Acionamento do gerador
- Notificação ao Gestor de TI

### 8.2 Ataque Cibernético
- Isolamento do servidor afetado
- Restauração do backup mais recente
- Análise de logs
- Troca de credenciais

### 8.3 Perda de Dados
- Restauração via backup
- Auditoria de acesso
- Comunicação interna

---

## 📜 9. Regras de Conduta

É proibido aos colaboradores:

- Compartilhar senhas
- Instalar softwares não autorizados
- Utilizar dispositivos pessoais na rede interna sem autorização
- Acessar dados sem necessidade funcional

---

## ⚖️ 10. Consequências pelo Descumprimento

| Infração | Consequência |
|-----------|--------------|
| Compartilhamento de senha | Advertência |
| Vazamento de dados | Suspensão |
| Sabotagem intencional | Demissão por justa causa |
| Acesso indevido | Processo administrativo |

---

## 📅 11. Aplicabilidade

Esta Política de Segurança da Informação entra em vigor a partir da sua publicação no repositório oficial da empresa e deverá ser revisada anualmente ou sempre que houver alterações significativas na infraestrutura tecnológica da organização.

---

## 🎥 12. Apresentação em Vídeo

O vídeo de apresentação desta política encontra-se disponível no link abaixo:

> 📎 (Inserir aqui o link do YouTube como NÃO LISTADO)

---
