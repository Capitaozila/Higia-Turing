# Requisitos Funcionais para o Sistema de Gerenciamento de Turing e Recompensas

## 1. Atores
1.1. Diretoria  
1.2. Colaborador

## 2. Requisitos Funcionais

### [RF001] Cadastro de Usuário
O sistema deve permitir que novos usuários sejam cadastrados, registrando as seguintes informações obrigatórias:
  - Nome completo
  - Endereço de e-mail
  - Senha de acesso

### [RF002] Visualizar Saldo e Extrato de Turing
 Visualizar Saldo e Extrato de Turing
O sistema deve permitir que os colaboradores visualizem seu saldo atual de Turing e o extrato detalhado, incluindo:
  - Data das transações
  - Tipo de transação (crédito ou débito)
  - Quantidade de Turing envolvida
  - Descrição da transação

### [RF003] Resgatar Recompensa
O sistema deve permitir que os colaboradores resgatem recompensas disponíveis utilizando seus pontos de Turing, conforme o saldo disponível.

### [RF004] Se Cadastrar na Plataforma
O sistema deve permitir que novos colaboradores se cadastrem na plataforma para obter acesso aos recursos oferecidos.

### [RF005] Gerenciamento de Recompensas
A diretoria deve poder realizar o cadastro, atualização e exclusão de recompensas, incluindo:
  - Nome da recompensa
  - Descrição detalhada
  - Quantidade de Turing necessária para resgate
  - Data de validade (se aplicável)

### [RF006] Adicionar Turing
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

### [NF001] Usabilidade
- O sistema deve ser fácil de usar, com uma interface intuitiva para diretoria e colaboradores.

### [NF002] Segurança
- O sistema deve garantir a segurança e a privacidade dos dados pessoais dos colaboradores, incluindo suas transações de Turing.

### [NF003] Performance
- O sistema deve ser capaz de acessar e atualizar rapidamente as informações, especialmente em situações de alta demanda.

### [NF004] Escalabilidade
- O sistema deve ser escalável para acomodar um grande número de colaboradores e transações de Turing.

### [NF005] Confiabilidade
- O sistema deve ser confiável e estar disponível para uso contínuo, minimizando períodos de inatividade.

### [NF006] Compatibilidade
- O sistema deve ser compatível com diferentes dispositivos (computadores, tablets, smartphones) para facilitar o acesso pelos colaboradores e diretoria.

## Regras de Negócios

### [RN001] Pontos de Turing
- Os pontos de Turing são uma moeda virtual utilizada para recompensar os colaboradores por suas contribuições e conquistas na empresa.

### [RN002] Resgate de Recompensas
- As recompensas disponíveis para resgate devem ser atualizadas regularmente pela diretoria, com base nas preferências e necessidades dos colaboradores.

### [RN003] Adição de Turing
- A adição de pontos de Turing às contas dos colaboradores deve ser feita de forma justa e transparente, de acordo com as políticas e critérios estabelecidos pela empresa.

### [RN004] Relatórios Financeiros
- Os relatórios financeiros gerados pela diretoria devem ser precisos e fornecer insights valiosos sobre a distribuição e utilização de Turing na empresa.

### [RN005] Data de aniversário
- Os colaboradores podem receber pontos de Turing extras em seus aniversários, como forma de reconhecimento e incentivo.