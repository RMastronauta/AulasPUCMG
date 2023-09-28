
# Matriz de Rastreabilidade de Requisitos

Uma ferramenta para garantir a cobertura e rastreabilidade de requisitos desde sua origem até a implementação e teste.

## Template

### 1. Requisitos de Alto Nível → Requisitos Detalhados

| ID | Descrição | Fonte | ID Requisito Detalhado(s) | Entrega da EAP | Prioridade | Responsável | Comentários |
|----|-----------|------|---------------------------|----------------|-----------|------------|------------|
| RF1 | Administrador cadastrar usuário no sistema | Entrevista | RF11 | Cadastrar usurário| média | Marcus Vinccius | Senha com mais de 13 caracteres |
| RF2 | Administrador cadastrar as informações das metas do usuário | Entrevista |RF1 | Cadastrar metas  | média | Marcus Vinccius | |
| RF3 | Visualizar o seu desempenho na empresa | Entrevista | RF1,RF4,RF5,RF6 ,RF7,RF8,RF9, RF10|  | Alta | Izabela Cecília | Visualizar desempenho |
| RF4 | Fazer o apontamento de horas de suas tarefas | Entrevista | RF1,RF4,RF5,RF6 ,RF7,RF8,RF9, RF10 | Apontar horas | Alta | Rodrigo Mendes |  |
| RF5 | Visualizar os apontamentos semanais | Entrevista | RF1,RF4,RF5,RF6 ,RF7,RF8,RF9, RF10 | Visualizar apontamentos | Média | Rodrigo Mendes |  |
| RF6 | visualizar suas tarefas e de seu setor durante a semana | Entrevista | RF1,RF4,RF5,RF6 ,RF7,RF8,RF9, RF10 | Exibir tarefas | Media| Marcus Vinicius |  |
| RF7 | visualizar um histórico das tarefas e apontamentos de todos setores | Entrevista | RF1,RF4,RF5,RF6 ,RF7,RF8,RF9, RF10 | exibir histórico | Alta| Marcus Vinicius |  |
| RF8 | realizar a manutenção dos requisitos mínimos de metas dos colaboradores | Entrevista | RF1,RF4,RF5,RF6 ,RF7,RF8,RF9, RF10 | realizar manutenção | Media| Ramon rodrigues |  |
| RF9 | enviar comunicados para os colaboradores | Entrevista |  | enviar comunicados | Media| Izabela Cecilia |  |
| RF10 | Administrador cadastrar avisos | Entrevista |  | cadastrar avisos | Alta| Rodrigo Mendes |  |
| RF11 | Usuário efetuar login| Entrevista | |  | média | Marcus Vinccius | |



**Entrega da EAP:** Refere-se à entrega específica do projeto na Estrutura Analítica de Projetos (EAP) com a qual o requisito está alinhado. 

**Prioridade:** Indica o nível de importância ou urgência de um requisito. Pode ser classificada em:

- **Alta:** Requisitos críticos que devem ser implementados o mais rápido possível.
- **Média:** Requisitos importantes, mas que podem ser adiados se necessário.
- **Baixa:** Requisitos desejáveis, mas que têm menor impacto se não forem implementados imediatamente.

### 2. Requisitos Detalhados → Testes

| ID | Descrição | ID Teste(s) | Entrega da EAP | Prioridade | Responsável | Status | Comentários |
|----|-----------|------------|----------------|-----------|------------|-------|------------|
| RD### | - | T### | (Referência à entrega específica da EAP) | (Alta, Média, Baixa) | - | - | - |

## Exemplo de Uso

### 1. Requisitos de Alto Nível → Requisitos Detalhados

| ID | Descrição | Fonte | ID Requisito Detalhado(s) | Entrega da EAP | Prioridade | Responsável | Comentários |
|----|-----------|------|---------------------------|----------------|-----------|------------|------------|
| RAL001 | Usuário deve poder fazer login no sistema | Documento | RD001, RD002 | Login | Alta | João Silva | Login com e sem 2FA |
| RAL002 | Usuário deve poder visualizar seu perfil | Entrevista | RD003 | Perfil | Média | Maria Souza | Inclui foto e e-mail |

### 2. Requisitos Detalhados → Testes

| ID | Descrição | ID Teste(s) | Entrega da EAP | Prioridade | Responsável | Status | Comentários |
|----|-----------|------------|----------------|-----------|------------|-------|------------|
| RD001 | Sistema deve aceitar credenciais válidas | T001 | Login | Alta | Pedro Costa | Completo | - |
| RD002 | Sistema deve rejeitar credenciais inválidas | T002 | Login | Alta | Ana Lima | Em Progresso | Falha ocasional |
| RD003 | Usuário deve ver nome, e-mail e data de cadastro | T003 | Perfil | Média | Roberto Alves | Não Iniciado | - |

