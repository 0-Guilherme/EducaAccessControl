# EducaAccessControl
>>> Enfim, tentei fazer mais de um método de explicação, não sei qual vai ficar melhor, deixei um de maneira resumida no inicio e um com a descrição tela por tela, mas ainda não sei qual é melhor. Fiquem a vontade para mudar o que for necessário!

Este projeto tem como objetivo desenvolver um aplicativo que facilita o gerenciamento de alunos, professores e fornecedores na universidade, incluindo cadastro, validação de documentos e processos de pagamento.

## Visão Geral

O aplicativo de gestão universitária visa otimizar a administração de cadastros e validação de informações, além de gerenciar os pagamentos de maneira ágil e simples. Ele oferece diferentes funcionalidades para atender a alunos, professores, administradores e fornecedores de forma eficiente. O sistema automatiza processos e melhora a experiência de todos os usuários.

## Funcionalidades do Aplicativo

### Cadastro de Conta
- Cadastro de conta de aluno, professor ou fornecedor.
- Preenchimento de informações pessoais (nome, CPF, e-mail, etc.).
- Upload de documentos obrigatórios (ex: RG, diploma, CNPJ).
- Validação de dados e documentos pelo administrador.
- Edição de cadastro em caso de dados incorretos ou incompletos.
- Exibição do status do cadastro (Aguardando Validação, Aprovado, Rejeitado).

### Login e Acesso
- Login com e-mail e senha.
- Opção para recuperação de senha.
- Mensagem de boas-vindas com o logo da universidade.
- Redirecionamento para a tela de seleção de formulário conforme tipo de usuário.

### Seleção de Formulário
- Escolha entre cadastro de Aluno, Professor ou Fornecedor.
- Exibição dos documentos necessários para cada tipo de cadastro.
- Link para corrigir dados caso a validação tenha sido rejeitada.

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
- Visualização do resumo de pagamento (valor, prazo, forma de pagamento).
- Status de pagamento (Pendente, Concluído, Erro no pagamento).
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
- Exportação de relatórios (PDF, 

----------------

---

## 1. Tela de Cadastro no Sistema
**Objetivo:** Iniciar o processo de cadastro, permitindo a escolha entre Pessoa Física ou Jurídica.

### Funcionalidades:
- Botões para selecionar:
  - **Pessoa Física**
  - **Pessoa Jurídica**

---

## 2. Tela de Escolha para Pessoa Física ou Jurídica
**Objetivo:** Direcionar o usuário para o fluxo correto conforme a sua escolha.

### Fluxos:
- **Pessoa Jurídica:** Leva diretamente para a tela de cadastro de Fornecedor.
- **Pessoa Física:** Apresenta opções para escolher entre Professor ou Aluno.

---

## 3. Tela de Cadastro de Pessoa Jurídica (Fornecedor)
**Objetivo:** Coletar os dados e documentos necessários de Pessoas Jurídicas.

### Funcionalidades:
- Formulário com os seguintes campos:
  - Nome da Empresa
  - CNPJ
  - Endereço
  - Representante Legal
- Upload de documentos obrigatórios (ex.: contrato social, comprovante de endereço).
- Validação dos campos no frontend para garantir que os dados estejam corretos antes de enviar.
- Botão para envio do formulário.

---

## 4. Tela de Escolha de Pessoa Física
**Objetivo:** Permitir que o usuário escolha entre os perfis de Professor ou Aluno.

### Funcionalidades:
- Botões para selecionar:
  - **Professor**
  - **Aluno**

---

## 5. Tela de Cadastro de Pessoa Física - Professor
**Objetivo:** Coletar os dados necessários de Professores.

### Funcionalidades:
- Formulário com os seguintes campos:
  - Nome
  - CPF
  - Área de Atuação
  - Especialidade
- Upload de documentos obrigatórios (ex.: RG, diplomas).
- Botão para envio do formulário.

---

## 6. Tela de Cadastro de Pessoa Física - Aluno
**Objetivo:** Coletar os dados necessários de Alunos.

### Funcionalidades:
- Formulário com os seguintes campos:
  - Nome
  - CPF
  - Curso
  - Matrícula
  - Data de Nascimento
- Upload de documentos obrigatórios (ex.: RG, comprovante de matrícula).
- Botão para envio do formulário.

---

## 7. Tela de Pagamento (Para Alunos)
**Objetivo:** Gerenciar os pagamentos realizados pelos Alunos.

### Funcionalidades:
- Resumo do pagamento, incluindo:
  - Valor
  - Prazo
  - Forma de pagamento disponível (boleto, cartão de crédito, etc.).
- Status do pagamento:
  - **Pendente**
  - **Concluído**
  - **Erro no Pagamento**
- Botão para reencaminhar o pagamento em caso de 

## Casos de Uso

![Descrição da Imagem](Documentacao/req_img_1.png)

## Diagrama de Classe
![Descrição da Imagem](Documentacao/diag_img_1.png)

## Colocar as outras Imagens
