# Ficha de Requisitos — Aula 02

## Análise e Projeto de Sistemas

**Unidade:** II — Introdução à Análise e Projeto de Sistemas
**Atividade:** Transformação do levantamento do sistema em requisitos funcionais e não funcionais
**Sistema:** Longevo Fit: Academia 60+
**Versão:** 2.0

---

# 1. Identificação do Sistema

| Campo                             | Preenchimento                                                                     |
| --------------------------------- | --------------------------------------------------------------------------------- |
| **Nome do sistema**               | Longevo Fit: Academia 60+                                              |
| **Objetivo**                      | Gerenciar o cadastro de alunos idosos (60+), ficha de saúde, liberação médica, planos, aulas adaptadas, reservas e pagamentos de uma academia voltada ao público 60+. |
| **Público-alvo**                  | Alunos idosos (60+), familiares/cuidadores, professores, profissional de saúde (fisioterapeuta), funcionários e administradores.                              |
| **Responsável pelo levantamento** | Grupo de estudantes                                                               |
| **Versão**                        | 2.0                                                                               |

---

# 2. Requisitos Funcionais

> Requisitos funcionais descrevem **funcionalidades ou serviços que o sistema deve oferecer**.

## RF01 — Cadastrar aluno

| Campo                      | Descrição                                                                                                                                                          |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RF01                                                                                                                                                               |
| **Descrição**              | O sistema deve permitir que funcionários cadastrem novos alunos idosos (60+) na academia.                                                                                      |
| **Prioridade**             | Alta                                                                                                                                                                |
| **Critérios de aceitação** | 1. Deve permitir informar nome, CPF, e-mail, telefone e data de nascimento. 2. Deve exigir data de nascimento e validar idade mínima de 60 anos. 3. Deve exigir ao menos um contato de emergência (nome, parentesco e telefone). 4. Deve impedir o cadastro sem nome, CPF e contato de emergência. 5. Deve informar ao funcionário quando o cadastro for concluído com sucesso.                                                                                                                                                   |
| **Exemplo**                | O funcionário informa os dados de um novo aluno (nascimento em 15/06/1960, tendo 66 anos), registra o contato de emergência (filha, (21) 98765-4321) e seleciona **Cadastrar**. O sistema valida as informações e registra o aluno.                                    |

---

## RF02 — Consultar planos

| Campo                      | Descrição                                                                                                                                                          |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RF02                                                                                                                                                               |
| **Descrição**              | O sistema deve permitir consultar os planos disponíveis na academia.                                                                                              |
| **Prioridade**             | Média                                                                                                                                                               |
| **Critérios de aceitação** | 1. Deve apresentar os planos disponíveis. 2. Deve informar o nome, valor e período de cada plano. 3. Deve indicar quando um plano não estiver disponível.                                                                                                  |
| **Exemplo**                | O aluno acessa a área de planos e consulta as opções disponíveis (Mensal, Trimestral, Anual), verificando o valor e a duração de cada plano.                                                               |

---

## RF03 — Reservar aula

| Campo                      | Descrição                                                                                                                                                          |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RF03                                                                                                                                                               |
| **Descrição**              | O sistema deve permitir que alunos realizem reservas em aulas adaptadas disponíveis.                                                                                        |
| **Prioridade**             | Alta                                                                                                                                                                 |
| **Critérios de aceitação** | 1. Deve verificar se o aluno está cadastrado. 2. Deve verificar se o aluno possui um plano ativo. 3. Deve verificar se o aluno possui liberação médica válida. 4. Deve verificar se a aula é compatível com o nível de mobilidade do aluno. 5. Deve verificar se existem vagas disponíveis. 6. Deve registrar a reserva e confirmar ao aluno.                                                                                                                  |
| **Exemplo**                | O aluno idoso acessa a lista de aulas (filtradas para seu nível de mobilidade), seleciona uma aula de alongamento às 14h (para a qual possui liberação médica válida) e confirma a reserva. O sistema verifica a compatibilidade, disponibilidade de liberação e vagas, registrando o agendamento.                                                                                           |

---

## RF04 — Cancelar reserva

| Campo                      | Descrição                                                                                                                                                          |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RF04                                                                                                                                                               |
| **Descrição**              | O sistema deve permitir que o aluno cancele uma reserva de aula realizada anteriormente.                                                                           |
| **Prioridade**             | Alta                                                                                                                                                                 |
| **Critérios de aceitação** | 1. Deve apresentar as reservas realizadas pelo aluno. 2. Deve permitir selecionar uma reserva para cancelamento. 3. Deve solicitar a confirmação do cancelamento. 4. Deve liberar a vaga após o cancelamento.                                                                                                                                 |
| **Exemplo**                | O aluno acessa suas reservas, seleciona uma aula para a qual não poderá comparecer e confirma o cancelamento. O sistema cancela a reserva e libera a vaga.         |

---

## RF05 — Cadastrar e editar aulas

| Campo                      | Descrição                                                                                                                                                          |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RF05                                                                                                                                                               |
| **Descrição**              | O sistema deve permitir que funcionários cadastrem e editem as aulas oferecidas pela academia, indicando o nível de mobilidade compatível.                                                                    |
| **Prioridade**             | Alta                                                                                                                                                                 |
| **Critérios de aceitação** | 1. Deve permitir informar nome da aula, professor, data, horário, quantidade de vagas e nível de mobilidade (baixo, moderado, alto). 2. Deve impedir o cadastro sem as informações obrigatórias. 3. Deve permitir editar os dados de uma aula existente.                                                                                                  |
| **Exemplo**                | O funcionário cadastra uma aula de hidroginástica para segunda-feira às 10h, define o professor responsável, nível de mobilidade baixo, e informa o limite de 20 alunos.              |

---

## RF06 — Cadastrar e editar planos

| Campo                      | Descrição                                                                                                                                                          |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RF06                                                                                                                                                               |
| **Descrição**              | O sistema deve permitir que funcionários cadastrem e editem os planos oferecidos pela academia.                                                                   |
| **Prioridade**             | Média                                                                                                                                                               |
| **Critérios de aceitação** | 1. Deve permitir informar nome, valor e duração do plano. 2. Deve impedir o cadastro sem nome e valor. 3. Deve permitir editar os dados de um plano existente.                                                                                                |
| **Exemplo**                | O funcionário cadastra o plano **Mensal**, define o valor e a duração de 30 dias. Posteriormente, poderá alterar o valor do plano.                               |

---

## RF07 — Consultar pagamentos

| Campo                      | Descrição                                                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RF07                                                                                                                                                              |
| **Descrição**              | O sistema deve permitir consultar a situação dos pagamentos dos alunos.                                                                                         |
| **Prioridade**             | Alta                                                                                                                                                                |
| **Critérios de aceitação** | 1. Deve permitir consultar os pagamentos vinculados ao aluno. 2. Deve informar pagamentos realizados e pendentes. 3. Deve indicar quando houver pagamento em atraso.                                                                              |
| **Exemplo**                | O funcionário consulta o cadastro de um aluno e verifica que a mensalidade do mês atual está pendente.                                                           |

---

## RF08 — Consultar dados e reservas

| Campo                      | Descrição                                                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RF08                                                                                                                                                              |
| **Descrição**              | O sistema deve permitir que o aluno consulte seus dados cadastrais e suas reservas de aulas.                                                                      |
| **Prioridade**             | Média                                                                                                                                                              |
| **Critérios de aceitação** | 1. O aluno deve visualizar seus dados cadastrados. 2. Deve apresentar as reservas atuais e futuras. 3. Deve permitir visualizar informações como nome da aula, data, horário e professor.                                                                             |
| **Exemplo**                | O aluno acessa seu perfil e consulta seus dados e a lista de aulas que possui reservadas para a semana.                                                             |

---

## RF09 — Registrar ficha de saúde

| Campo                      | Descrição                                                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RF09                                                                                                                                                              |
| **Descrição**              | O sistema deve permitir que o profissional de saúde registre a ficha de saúde do aluno, contendo informações sobre condições, medicamentos, alergias e restrições.                                                                      |
| **Prioridade**             | Alta                                                                                                                                                                |
| **Critérios de aceitação** | 1. Deve permitir informar condições de saúde, medicamentos em uso, alergias e restrições de movimento. 2. Deve registrar a data da última atualização. 3. Somente o aluno, o profissional de saúde e funcionários autorizados visualizam a ficha. 4. Deve impedir acesso não autorizado aos dados sensíveis.                                                                              |
| **Exemplo**                | A fisioterapeuta registra que o aluno tem artrose no joelho e restrição para exercícios de impacto. O sistema armazena a informação com data de atualização e restringe o acesso.                                                           |

---

## RF10 — Registrar e validar liberação médica

| Campo                      | Descrição                                                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RF10                                                                                                                                                              |
| **Descrição**              | O sistema deve permitir o cadastro e validação de liberação médica, indicando quando está vencida ou prestes a vencer.                                                                      |
| **Prioridade**             | Alta                                                                                                                                                                |
| **Critérios de aceitação** | 1. Deve informar data de emissão, validade e nome do médico. 2. Deve indicar liberações vencidas ou prestes a vencer (30 dias). 3. Deve sinalizar ao funcionário e ao aluno quando não há liberação válida. 4. Deve impedir reserva de aulas sem liberação válida.                                                                              |
| **Exemplo**                | O funcionário cadastra o atestado emitido em 10/09/2026, com validade de 12 meses. O sistema registra e valida a data. Quando faltam 30 dias para vencer, o sistema avisa o aluno.                                                           |

---

## RF11 — Gerenciar contato de emergência

| Campo                      | Descrição                                                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RF11                                                                                                                                                              |
| **Descrição**              | O sistema deve permitir que o aluno e funcionários gerenciem os contatos de emergência do aluno.                                                                      |
| **Prioridade**             | Média                                                                                                                                                              |
| **Critérios de aceitação** | 1. Deve informar nome, parentesco e telefone do contato. 2. Deve permitir editar e remover contatos. 3. O professor pode consultar o contato durante a aula. 4. Deve exigir ao menos um contato para concluir o cadastro.                                                                              |
| **Exemplo**                | O aluno informa a filha como contato (Maria Silva, filha, (21) 98765-4321) e o professor a consulta antes da aula em caso de necessidade.                                                           |

---

## RF12 — Classificar aulas por nível de mobilidade

| Campo                      | Descrição                                                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RF12                                                                                                                                                              |
| **Descrição**              | O sistema deve classificar as aulas de acordo com o nível de mobilidade exigido e listar ao aluno apenas aulas compatíveis.                                                                      |
| **Prioridade**             | Média                                                                                                                                                                |
| **Critérios de aceitação** | 1. Deve classificar aulas como baixo, moderado ou alto. 2. Deve listar ao aluno apenas aulas compatíveis com seu nível. 3. Deve permitir que o profissional de saúde altere o nível de mobilidade do aluno. 4. Deve validar a compatibilidade no momento da reserva.                                                                              |
| **Exemplo**                | Aluno de nível de mobilidade baixo vê apenas hidroginástica e alongamento, enquanto aluno de nível moderado pode também reservar pilates. O profissional de saúde pode reclassificar o aluno conforme sua evolução.                                                           |

---

## RF13 — Vincular familiar ou cuidador

| Campo                      | Descrição                                                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RF13                                                                                                                                                              |
| **Descrição**              | O sistema deve permitir que o aluno vincule um familiar ou cuidador para acompanhar informações de reservas e pagamentos.                                                                      |
| **Prioridade**             | Baixa (Could Have)                                                                                                                                                                |
| **Critérios de aceitação** | 1. Deve exigir autorização explícita do aluno para vincular um familiar. 2. O familiar visualiza apenas reservas e pagamentos, nunca a ficha de saúde. 3. O aluno pode revogar o vínculo a qualquer momento. 4. Deve registrar a data do vínculo e revogação.                                                                              |
| **Exemplo**                | A filha do aluno recebe convite de vinculação, aceita, e passa a consultar se a mensalidade do pai está paga e quais aulas ele reservou. Não consegue acessar informações médicas.                                                           |

---

# 3. Requisitos Não Funcionais

> Requisitos não funcionais descrevem **características, restrições e condições de qualidade** que o sistema deve atender.

## RNF01 — Segurança

| Campo                      | Descrição                                                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RNF01                                                                                                                                                             |
| **Descrição**              | O sistema deve controlar o acesso às funcionalidades de acordo com o perfil do usuário e proteger dados sensíveis de saúde conforme LGPD.                                                                         |
| **Prioridade**             | Alta                                                                                                                                                                |
| **Critérios de aceitação** | 1. Os usuários devem realizar autenticação antes de acessar funções restritas. 2. Funcionalidades administrativas devem estar disponíveis somente para funcionários autorizados. 3. Dados de saúde são dados pessoais sensíveis (LGPD) e devem ter acesso restrito a profissionais de saúde e funcionários autorizados. 4. Fichas de saúde não devem ser visíveis ao aluno ou a familiares.                                                                                                                                       |
| **Exemplo**                | Um aluno acessa o sistema, mas não consegue acessar a tela de cadastro e edição de planos. O profissional de saúde acessa apenas a ficha de saúde e liberação médica, não dados de pagamento.                        |

---

## RNF02 — Desempenho

| Campo                      | Descrição                                                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RNF02                                                                                                                                                             |
| **Descrição**              | O sistema deve apresentar respostas em tempo adequado durante o uso normal.                                                                                     |
| **Prioridade**             | Média                                                                                                                                                             |
| **Critérios de aceitação** | Em condições normais de operação, consultas simples devem apresentar o resultado em até 3 segundos.                                                             |
| **Exemplo**                | Ao consultar as aulas disponíveis, o sistema deve apresentar os resultados em até 3 segundos.                                                                   |

---

## RNF03 — Usabilidade

| Campo                      | Descrição                                                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RNF03                                                                                                                                                             |
| **Descrição**              | A interface deve apresentar informações e comandos de forma clara, simples e consistente, com mensagens em linguagem simples sem termos técnicos.                                                                       |
| **Prioridade**             | Alta                                                                                                                                                                |
| **Critérios de aceitação** | 1. Os campos devem possuir rótulos claros. 2. As mensagens de erro devem orientar o usuário em linguagem simples. 3. As principais ações devem ser facilmente identificáveis. 4. Textos devem evitar jargão técnico.                                                                                                 |
| **Exemplo**                | Ao tentar reservar uma aula lotada, o sistema apresenta: "Desculpe, não há vagas nesta aula. Tente outra." (em vez de "Erro 409: Conflito de recurso").                                                                                        |

---

## RNF04 — Disponibilidade

| Campo                      | Descrição                                                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RNF04                                                                                                                                                             |
| **Descrição**              | O sistema deve estar disponível durante o horário de funcionamento da academia.                                                                                 |
| **Prioridade**             | Alta                                                                                                                                                                |
| **Critérios de aceitação** | 1. O sistema deve permanecer acessível durante o horário de funcionamento da academia. 2. Manutenções programadas devem ser realizadas previamente e comunicadas aos usuários.                                                                                               |
| **Exemplo**                | Durante o horário de funcionamento, alunos e funcionários conseguem acessar o sistema para realizar reservas e consultar informações, exceto durante manutenções previamente agendadas.                                                             |

---

## RNF05 — Acessibilidade

| Campo                      | Descrição                                                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Identificação**          | RNF05                                                                                                                                                             |
| **Descrição**              | O sistema deve ser acessível a idosos com dificuldades de visão, mobilidade ou habilidades tecnológicas limitadas.                                                                       |
| **Prioridade**             | Alta                                                                                                                                                                |
| **Critérios de aceitação** | 1. Fonte padrão mínima de 16 pt, ajustável até 200%. 2. Contraste mínimo de 4,5:1 (WCAG AA). 3. Botões com área de toque mínima de 48 px. 4. Reservar uma aula em no máximo 4 toques/cliques a partir da tela inicial. 5. Navegação intuitiva com poucas opções por tela.                                                                              |
| **Exemplo**                | Aluno com dificuldade de visão aumenta a fonte para 18 pt com alto contraste e reserva uma aula apertando apenas 4 botões: Login > Minhas Aulas > Novas Aulas > Confirmar Reserva.                                                           |

---

# 4. Regras de Negócio

| ID | Regra de Negócio |
|---|---|
| **RN01** | Um aluno só pode reservar uma aula com vaga disponível. |
| **RN02** | Cada usuário só acessa as funcionalidades do seu perfil. |
| **RN03** | O cancelamento de uma reserva libera a vaga. |
| **RN04** | O aluno só reserva aulas se tiver plano ativo e pagamento em dia. |
| **RN05** | A reserva exige liberação médica válida. |
| **RN06** | A liberação médica vale por 12 meses a partir da emissão. |
| **RN07** | O aluno só reserva aulas compatíveis com seu nível de mobilidade. |
| **RN08** | O cadastro exige ao menos um contato de emergência. |
| **RN09** | A ficha de saúde só pode ser vista pelo aluno, pelo profissional de saúde e por funcionários autorizados. |

---

# 5. Integrantes do grupo

* Pedro Henrique Silva Monteiro
* Pedro Borges Prudente Machado
* Yago Alves de Carvalho
* Robson Otávio Queiroz Castro
* Igor Jesus da Silva Tolentino
* Luiz Daniel da Costa Bastos

---

# 6. Entregável da atividade

O grupo desenvolveu a especificação dos requisitos para **Longevo Fit: Academia 60+**, contemplando:

* Identificação do sistema;
* 13 requisitos funcionais;
* 5 requisitos não funcionais;
* 9 regras de negócio;
* Prioridade de cada requisito;
* Critérios de aceitação;
* Exemplos de utilização;
* Identificação dos integrantes do grupo.

## Próxima etapa

Os requisitos produzidos nesta ficha servirão como base para a identificação e especificação dos **casos de uso** do Longevo Fit: Academia 60+.
