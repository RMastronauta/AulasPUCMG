
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
| RD003 | Usuário deve ver nome, e-mail e data de cadastro | T003 | Perfil | Média | Marco Tulio | Em Andamento | - |
| RN004 | software deve aceitar credenciais válidas | T004 | Login | Alta | Rodrigo Mendes | Finalizado | - |
| RN005 | software deve rejeitar credenciais inválidas | T005 | Login | Alta | Ramon Mendes | Finalizado | - |
| RN006 | software deve verificar se o ADM que está cadastrando usuário | T006 | Cadasto usuário | Alta | Izabela Cecilia | Finalizado | - |
| RN007 | software deve verificar o o ADM que está cadastrando as métricas| T007 | métricas | Alta | Ramon Mendes | Finalizado | - |
| RN008 | Todos Usuarios deve receber comunicado | T008 | comunicado | Alta | Ramon Mendes | Finalizado | - |
| RN008 | Usuário deve ver seu desempenho na empresa | T009 | Métricas | Alta | Marco Tulio | Em Andamento | - |
| RN008 | Usuário deve ver seus apontamentos | T0010 | Apontamentos | média | Marco Tulio | Em Andamento | - |
| RN008 | Softeare deve apresentar as tarefas do seu devido departamento | T0011 | Tarefas | Media | Marco Tulio | Finalizado | - |
| RN008 | ADM deve conseguir alterar as métricas dos usuários | T0011 | Tarefas | Media | Marco Tulio | Finalizado | - |

## Exemplo de Uso

### 1. Requisitos de Alto Nível → Requisitos Detalhados

| ID | Descrição | Fonte | ID Requisito Detalhado(s) | Entrega da EAP | Prioridade | Responsável | Comentários |
|----|-----------|------|---------------------------|----------------|-----------|------------|------------|
| RNF1 | Seguir design disponibilizado pela empresa | Entrevista |  | template | Alta | Marco Tulio | Validação do Usuário |
| RNF2 | O software deve realizar as métricas de desempenho de usuário | Entrevista |  | Calculo de métricas | Alta | Ramon Mendes |  |
| RNF3 | O software deve fazer o cálculo de pontos do colaborador | Entrevista |  | Calculo de métricas | Alta | Rodrigo Mendes |  |
| RNF4 | linguagem mysql | Entrevista |  | Calculo de métricas | Alta | Marco Tulio |  |
| RNF5 | Java para back end | Entrevista |  | Calculo de métricas | Alta | Izabela Cecilia |  |
| RNF6 | framework next.js | Entrevista |  | Calculo de métricas | Alta | Marco Tulio |  |
| RNF7 | Tempo de resposta de 5 segundos | Entrevista |  | Calculo de métricas | Alta | Rodrigo Mendes |  |
| RNF8 | o software deve ser capaz de funcionar corretamente sem falhas | Entrevista |  | Calculo de métricas | Alta | Izabela Cecilia  Rodrigo Mendes|  |
| RNF9 | O software dev | Entrevista |  | Calculo de métricas | Alta | Izabela Cecilia  Rodrigo Mendes|  |
| RNF10 | o software deve ser fácil de manter e modificar | Entrevista |  | Calculo de métricas | Alta | Marco Tulio |  |

### 2. Requisitos Detalhados → Testes

| ID | Descrição | ID Teste(s) | Entrega da EAP | Prioridade | Responsável | Status | Comentários |
|----|-----------|------------|----------------|-----------|------------|-------|------------|
| RN001 | Testar o tempo de resposta de todas as APIs para garantio o menor tempo de resposta | T001 | Eficiencia | Alta | Rodrigo Mendes Ramon Mendes | Em Progresso | - |
| RN002 | Testar métricas do usuário calculada pelo software | T002 | métricas | Alta | Izabela Cecilia | Em Progresso | - |
| RN003 | Teste de pontos calculados pelo software | T003 | Pontos | Média | Izabela Cecilia Ramon Mendes | Finalizado | - |
| RN004 | Teste de criptografia e segurança do software | T004 | Pontos | Média | Izabela Cecilia Rodrigo Mendes | Em Andamento | - |


