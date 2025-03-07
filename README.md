# EducaAccessControl

> **Nota:** Este projeto inclui explicações de maneira resumida no início e com descrições detalhadas tela por tela a seguir. Fique à vontade para ajustar conforme necessário!

## Objetivo do Projeto

Este projeto tem como objetivo desenvolver um aplicativo que facilita o gerenciamento de alunos, professores e fornecedores na universidade. Ele abrange processos de cadastro, validação de documentos e gestão de pagamentos.

## Visão Geral

O aplicativo EducaAccessControl visa otimizar a administração de cadastros e validação de informações, além de gerenciar pagamentos de maneira ágil e simples. Ele foi projetado para atender diferentes perfis de usuários: alunos, professores, administradores e fornecedores, automatizando processos e melhorando a experiência de uso.

## Funcionalidades do Aplicativo

### Cadastro de Conta
- Cadastro de conta de aluno, professor ou fornecedor.
- Preenchimento de informações pessoais (nome, CPF, e-mail, etc.).
- Upload de documentos obrigatórios (ex.: RG, diploma, CNPJ).
- Validação de dados e documentos pelo administrador.
- Edição de cadastro em caso de dados incorretos ou incompletos.
- Exibição do status do cadastro: **Aguardando Validação**, **Aprovado**, **Rejeitado**.

### Login e Acesso
- Login com e-mail e senha.
- Opção para recuperação de senha.
- Mensagem de boas-vindas com o logo da universidade.
- Redirecionamento para a tela de seleção de formulário conforme o tipo de usuário.

### Seleção de Formulário
- Escolha entre cadastro de **Aluno**, **Professor** ou **Fornecedor**.
- Exibição dos documentos necessários para cada tipo de cadastro.
- Link para corrigir dados em caso de validação rejeitada.

### Validação de Cadastro e Documentos (Administrador)
- Visualização das solicitações pendentes de cadastro.
- Ação para aprovar ou rejeitar cadastros.
- Justificativa obrigatória ao rejeitar um cadastro.
- Exibição e download dos documentos enviados pelos usuários.

### Edição de Cadastro
- Correção de dados e documentos após rejeição.
- Envio de novos documentos para aprovação.
- Mensagens informando quais dados ou documentos precisam ser corrigidos.

### Gestão de Pagamentos (Alunos)
- Resumo do pagamento: valor, prazo, forma de pagamento.
- Status do pagamento: **Pendente**, **Concluído**, **Erro no Pagamento**.
- Geração de boleto ou opção de pagamento online.
- Reenvio de pagamento em caso de erro.

### Pós-Cadastro
- **Alunos:** Inscrição em disciplinas, com filtros por curso e semestre.
- **Professores:** Inscrição para ministrar disciplinas, turmas e horários disponíveis.
- **Fornecedores:** Envio de propostas e gerenciamento de contratos.

### Relatórios e Painel Administrativo
- Resumo de cadastros aprovados e pendentes.
- Gráficos de distribuição de alunos por curso e fornecedores por categoria.
- Histórico de validações realizadas.
- Exportação de relatórios em **PDF** ou **Excel**.

## Descrição

### 1. Tela de Cadastro no Sistema
**Objetivo:** Iniciar o processo de cadastro, permitindo a escolha entre Pessoa Física ou Pessoa Jurídica.

### 2. Tela de Cadastro de Pessoa Jurídica
**Objetivo:** Coletar os dados e documentos necessários para cadastro de Pessoas Jurídicas.

**Funcionalidades:**
- Formulário com campos como:
  - Razão Social
  - Nome Fantasia
  - CNPJ
  - ...
- Botão para envio do formulário.

### 2.1 Tela de Cadastro de Fornecedores
**Objetivo:** 

**Funcionalidades:**
- Formulário com campos como:
  - 
  - 
  - 
  - 


### 3. Tela de Cadastro de Pessoa Física
**Objetivo:** Coletar os dados e documentos necessários para cadastro de Pessoas Físicas, como Alunos e Professores.

**Funcionalidades:**
- Formulário com campos como:
  - Nome Completo
  - CPF
  - Data de Nascimento
  - Escolha entre Aluno e Professor
  - Endereço
- Botão para envio do formulário.

### 3.1 Tela de Cadastro de Pessoa Física - Aluno
**Objetivo:** Coletar os dados necessários para Alunos.

**Funcionalidades:**
- Campos como:
  - Nome
  - CPF
  - Curso
  - Matrícula
  - Data de Nascimento
- Upload de documentos obrigatórios (ex.: RG, Comprovante de Matrícula).
- Botão de envio.

### 3.1.1 Tela de Pagamento (Para Alunos)
**Objetivo:** Gerenciar pagamentos realizados pelos Alunos.

**Funcionalidades:**
- Resumo do pagamento, incluindo:
  - Valor
  - Prazo
  - Forma de pagamento (Boleto, Cartão de Crédito).
- Status do pagamento:
  - **Pendente**
  - **Concluído**
  - **Erro no Pagamento**
- Botão para reencaminhar o pagamento em caso de falha.

### 3.2 Tela de Cadastro de Pessoa Física
**Objetivo:** Coletar os dados necessários para Professores.

**Funcionalidades:**
- Campos como:
  - Nome
  - CPF
  - Área de Atuação
  - Especialidade
- Upload de documentos obrigatórios (ex.: RG, Diplomas).
- Botão de envio.

## Casos de Uso

![Casos de Uso](Documentacao/req_img_1.png)

## Diagrama de Classe

![Diagrama de Classe](Documentacao/diag_img_1.png)

> **Nota:** Adicione as imagens complementares à documentação para maior clareza.
