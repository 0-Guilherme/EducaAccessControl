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

### 1. Tela Inicial / Login

**Objetivo:** Controlar o acesso ao sistema e direcionar os usuários para as funcionalidades adequadas.

**O que você encontrará:**
- Campos para inserção de e-mail e senha.
- Opção de recuperação de senha em caso de esquecimento.
- Link para criar uma nova conta (cadastro).
- Mensagem de boas-vindas com o logo da universidade.

### 2. Tela de Seleção de Formulário

**Objetivo:** Permitir que o usuário escolha qual tipo de cadastro deseja realizar.

**O que você encontrará:**
- Botões para selecionar entre as opções de cadastro: Aluno, Professor ou Fornecedor.
- Informações claras sobre os requisitos para cada tipo de cadastro (documentos necessários, por exemplo).
- Opção de reenvio para corrigir dados, caso necessário.

### 3. Tela de Cadastro

**Objetivo:** Coletar dados do usuário e os documentos necessários para validação.

**O que você encontrará:**
- Formulário dinâmico que se adapta conforme o tipo de usuário:
  - Aluno: Nome, CPF, curso, matrícula, data de nascimento.
  - Professor: Nome, CPF, área de atuação, especialidade.
  - Fornecedor: Nome da empresa, CNPJ, endereço, representante legal.
- Campo para fazer o upload de documentos obrigatórios (ex: RG, comprovantes, diplomas).
- Validação dos campos no frontend para garantir que os dados estejam corretos antes de enviar.
- Botão para enviar o formulário.

### 4. Tela de Validação pelo Administrador

**Objetivo:** Permitir que o administrador revise, aprove ou rejeite os cadastros e documentos.

**O que você encontrará:**
- Lista de solicitações pendentes para validação, com detalhes do nome do solicitante e tipo de cadastro.
- Detalhamento dos documentos enviados, com opção para fazer download.
- Botões para aprovar ou rejeitar as solicitações, com campo para justificar a decisão.
- Status da solicitação (Aguardando, Aprovado, Rejeitado).

### 5. Tela de Edição de Cadastro

**Objetivo:** Permitir que os usuários corrijam ou atualizem dados ou documentos.

**O que você encontrará:**
- Formulário pré-preenchido com as informações que precisam ser corrigidas.
- Opção para upload de novos documentos.
- Mensagens que informam exatamente quais dados ou documentos precisam ser corrigidos.
- Botão para enviar as correções.

### 6. Tela de Status do Cadastro

**Objetivo:** Informar ao usuário o status do seu cadastro.

**O que você encontrará:**
- Mensagem clara sobre o status do cadastro: "Aguardando Validação", "Rejeitado", "Aprovado".
- Histórico das ações realizadas no cadastro.
- Link para editar os dados, caso haja alguma rejeição.

### 7. Tela de Pagamento (Para Alunos)

**Objetivo:** Gerenciar os pagamentos realizados pelos alunos.

**O que você encontrará:**
- Resumo do pagamento, incluindo valor, prazo e forma de pagamento disponível (boleto, cartão de crédito, etc.).
- Status do pagamento (Pendente, Concluído, Erro no Pagamento).
- Botão para reencaminhar o pagamento em caso de falha.

### 8. Tela de Pós-Cadastro

**Objetivo:** Oferecer funcionalidades após o cadastro, dependendo do tipo de usuário.

**O que você encontrará:**
- **Alunos:** Acesso para inscrição em disciplinas, com filtros por curso e semestre.
- **Professores:** Acesso para inscrição em turmas e horários para lecionar.
- **Fornecedores:** Opções para envio de propostas e gerenciamento de contratos.

### 9. Tela de Relatórios e Painel Administrativo

**Objetivo:** Apresentar informações detalhadas sobre o andamento do sistema para os administradores.

**O que você encontrará:**
- Resumo de cadastros aprovados e pendentes.
- Gráficos de distribuição de alunos por curso e de fornecedores por categoria.
- Histórico de validações realizadas.
- Opções para exportar relatórios (PDF, Excel).

## Casos de Uso

![Descrição da Imagem](Documentacao/req_img_1.png)

## Diagrama de Classe
![Descrição da Imagem](Documentacao/diag_img_1.png)

## Colocar as outras Imagens
