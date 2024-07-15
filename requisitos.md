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

### [RF002] Verificar Saldo e Extrato de Turing

Verificar Saldo e Extrato de Turing
O sistema deve permitir que os colaboradores visualizem seu saldo atual de Turing e o extrato detalhado, incluindo:

- Histórico de turings recebidos:

  - Nome do colaborador
  - ID do colaborador
  - Quantidade de turing recebidos
  - Data das transações

- Quantidade de turing total:
  - Quantidade de turing disponível
  - Quantidade de turing a mais que o último mês

### [RF003] Resgatar Recompensa

O sistema deve permitir que os colaboradores resgatem recompensas disponíveis utilizando seus pontos de Turing, conforme o saldo disponível.

### [RF004] Gerenciamento de Recompensas

A diretoria deve poder realizar o cadastro, atualização e exclusão de recompensas, incluindo:

- Nome da recompensa
- Descrição detalhada
- Quantidade de Turing necessária para resgate

### [RF005] Gerenciar Turing

A diretoria deve poder adicionar ou remover pontos de Turing às contas dos colaboradores, conforme critérios estabelecidos pela empresa.

## 3. Requisitos Não Funcionais

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

## 4. Regras de Negócios

### [RN001] Adição de Turing

- A adição de pontos de Turing às contas dos colaboradores deve ser feita de forma justa e transparente, de acordo com as políticas e critérios estabelecidos pela empresa.

### [RN002] Data de aniversário

- Os colaboradores podem receber pontos de Turing extras em seus aniversários, como forma de reconhecimento e incentivo.

### [RN003] Data de aniversário na empresa

- Os colaboradores podem receber pontos de Turing extras em seus aniversários na empresa, como forma de reconhecimento e incentivo.

### [RN004] Gerenciamento de usuário

- Somente a diretoria pode gerenciar usuários.

### [RN005] Gerenciamento de resgates

- O usuário só poderá resgatar a recompensa se possuir o saldo necessário.

### [RN006] Gerenciamento de recompensas

- A recompensa só poderá ser cadastrada se possuir a quantidade de Turing necessária para resgate.

### [RN007] Tarefas antecipadas

- A diretoria poderá adicionar tarefas para os colaboradores, que ao serem concluídas mais cedo que a data prevista, receberão pontos de Turing extras.

### [RN009] Tarefas concluídas

- Ao concluir uma tarefa, o colaborador receberá pontos de Turing.

### [RN011] Tarefas canceladas

- Caso a tarefa seja cancelada, o colaborador não receberá pontos de Turing. Mas, a diretoria deve notificar o funcionário sobre o cancelamento e dá as devidas justificativas.
