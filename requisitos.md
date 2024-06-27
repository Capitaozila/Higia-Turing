# Requisitos Funcionais para o Sistema de Gerenciamento de Turing e Recompensas

## 1. Atores
1.1. Diretoria  
1.2. Colaborador

## 2. Funcionalidades do Sistema (Requisitos Funcionais)

### 2.1. Cadastro de Usuário
O sistema deve permitir que novos usuários sejam cadastrados, registrando as seguintes informações obrigatórias:
  - Nome completo
  - Endereço de e-mail
  - Senha de acesso

### 2.2. Visualizar Saldo e Extrato de Turing
O sistema deve permitir que os colaboradores visualizem seu saldo atual de Turing e o extrato detalhado, incluindo:
  - Data das transações
  - Tipo de transação (crédito ou débito)
  - Quantidade de Turing envolvida
  - Descrição da transação

### 2.3. Resgatar Recompensa
O sistema deve permitir que os colaboradores resgatem recompensas disponíveis utilizando seus pontos de Turing, conforme o saldo disponível.

### 2.4. Se Cadastrar na Plataforma
O sistema deve permitir que novos colaboradores se cadastrem na plataforma para obter acesso aos recursos oferecidos.

### 2.5. Gerenciamento de Recompensas
A diretoria deve poder realizar o cadastro, atualização e exclusão de recompensas, incluindo:
  - Nome da recompensa
  - Descrição detalhada
  - Quantidade de Turing necessária para resgate
  - Data de validade (se aplicável)

### 2.6. Adicionar Turing
A diretoria deve poder adicionar pontos de Turing às contas dos colaboradores, conforme critérios estabelecidos pela empresa.

<!-- ### 2.7. Gerar Relatório Financeiro
A diretoria deve poder gerar relatórios financeiros com informações agregadas sobre a distribuição e utilização de Turing, incluindo:
  - Total de Turing distribuídos
  - Total de Turing resgatados
  - Saldo de Turing por colaborador
  - Gráficos e estatísticas de utilização -->

## 3. Relacionamentos entre Casos de Uso

### 3.1. Relacionamentos de Inclusão
- O caso de uso "Resgatar Recompensa" inclui "Visualizar Saldo e Extrato de Turing" para garantir que o colaborador possa verificar seu saldo antes de resgatar uma recompensa.

### 3.2. Relacionamentos de Exclusão
- Não há relacionamentos de exclusão entre os casos de uso do sistema.

## 4. Requisitos Não Funcionais

### 4.1. Usabilidade
- O sistema deve ser fácil de usar, com uma interface intuitiva para diretoria e colaboradores.

### 4.2. Segurança
- O sistema deve garantir a segurança e a privacidade dos dados pessoais dos colaboradores, incluindo suas transações de Turing.

### 4.3. Performance
- O sistema deve ser capaz de acessar e atualizar rapidamente as informações, especialmente em situações de alta demanda.

### 4.4. Escalabilidade
- O sistema deve ser escalável para acomodar um grande número de colaboradores e transações de Turing.

### 4.5. Confiabilidade
- O sistema deve ser confiável e estar disponível para uso contínuo, minimizando períodos de inatividade.

### 4.6. Compatibilidade
- O sistema deve ser compatível com diferentes dispositivos (computadores, tablets, smartphones) para facilitar o acesso pelos colaboradores e diretoria.
