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

## Descrição Tela por Tela

### 1. Tela de Cadastro no Sistema
**Objetivo:** Iniciar o processo de cadastro, permitindo a escolha entre Pessoa Física ou Jurídica.

**Funcionalidades:**
- Botões para selecionar:
  - **Pessoa Física**
  - **Pessoa Jurídica**

### 2. Tela de Escolha para Pessoa Física ou Jurídica
**Objetivo:** Direcionar o usuário para o fluxo correspondente.

**Fluxos:**
- **Pessoa Jurídica:** Encaminha para o cadastro de Fornecedor.
- **Pessoa Física:** Apresenta opções para Professor ou Aluno.

### 3. Tela de Cadastro de Pessoa Jurídica (Fornecedor)
**Objetivo:** Coletar os dados e documentos necessários.

**Funcionalidades:**
- Formulário com campos como:
  - Nome da Empresa
  - CNPJ
  - Endereço
  - Representante Legal
- Upload de documentos obrigatórios (ex.: Contrato Social, Comprovante de Endereço).
- Botão para envio do formulário.

### 4. Tela de Escolha de Pessoa Física
**Objetivo:** Permitir a escolha entre os perfis de Professor ou Aluno.

**Funcionalidades:**
- Botões para selecionar:
  - **Professor**
  - **Aluno**

### 5. Tela de Cadastro de Pessoa Física - Professor
**Objetivo:** Coletar os dados necessários para Professores.

**Funcionalidades:**
- Campos como:
  - Nome
  - CPF
  - Área de Atuação
  - Especialidade
- Upload de documentos obrigatórios (ex.: RG, Diplomas).
- Botão de envio.

### 6. Tela de Cadastro de Pessoa Física - Aluno
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

### 7. Tela de Pagamento (Para Alunos)
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

## Casos de Uso

![Casos de Uso](Documentacao/req_img_1.png)

## Diagrama de Classe

![Diagrama de Classe](Documentacao/diag_img_1.png)

> **Nota:** Adicione as imagens complementares à documentação para maior clareza.
