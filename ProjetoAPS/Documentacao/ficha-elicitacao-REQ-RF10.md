# Ficha de Elicitação de Requisitos

**Curso:** Sistemas de Informação  
**Disciplina:** Análise e Projeto de Sistemas  
**Instituição:** UDF Centro Universitário  
**Grupo/integrantes:** Pedro Henrique Silva Monteiro, Pedro Borges Prudente Machado, Yago Alves de Carvalho, Robson Otávio Queiroz Castro, Igor Jesus da Silva Tolentino, Luiz Daniel da Costa Bastos  
**Turma:** D2  **Data:** [a preencher]  **Versão:** 1.0

> Registre a necessidade na linguagem do stakeholder e esclareça termos ambíguos antes de validar a ficha com ele.

## 1. Identificação do projeto

| Campo | Preenchimento |
|---|---|
| Nome do projeto | Longevo Fit: Academia 60+ |
| Objetivo do projeto | Facilitar a gestão de uma academia voltada a pessoas com 60 anos ou mais, com foco em segurança, mobilidade, ficha de saúde e acessibilidade. |
| Contexto e escopo | O sistema contempla cadastro de alunos, reservas de aulas adaptadas, liberação médica, ficha de saúde, contatos de emergência, planos, pagamentos e controle de acesso por perfil. |

## 2. Stakeholder e fonte

| Campo | Preenchimento |
|---|---|
| Stakeholder (nome ou papel) | Aluno idoso (60+) |
| Relação com o projeto | Usuário principal do sistema |
| Contato ou setor (se aplicável) | Alunos matriculados na academia |
| Técnica e data da elicitação | Entrevista / levantamento de requisitos em grupo; [a preencher] |
| Responsável pelo registro | Grupo APS — UDF |

## 3. Requisito elicitado

| Campo | Preenchimento |
|---|---|
| ID do requisito | RF03 |
| Necessidade relatada pelo stakeholder | "[substituir pela fala real da entrevista]" |
| Descrição consolidada | O sistema deve permitir que o aluno autenticado reserve uma aula compatível com seu nível de mobilidade, verificando plano ativo, liberação médica válida, disponibilidade de vaga e confirmação da reserva. |
| Justificativa ou benefício esperado | Agiliza o processo de agendamento, reduz dependência de terceiros e evita que o aluno reserve aulas inadequadas. |
| Tipo | Funcional (corresponde ao RF03 — Reservar aula) |
| Dependências ou dúvidas | Depende do cadastro do aluno, do plano ativo, da liberação médica e da classificação da aula por nível de mobilidade. Dúvida a esclarecer: "O que acontece se a liberação médica vencer com aulas já reservadas?" Sugestão: reservas futuras além da validade são canceladas e o aluno é avisado. |

### Exemplo de fala em rascunho

> "Quero reservar minha aula sem depender da minha filha, mas com letras grandes e poucos botões."

## 4. Regras de negócio

| ID | Regra de negócio relacionada | Fonte ou responsável pela validação |
|---|---|---|
| RN01 | Um aluno só pode reservar uma aula com vaga disponível. | Academia / gestão do sistema |
| RN04 | O aluno só reserva aulas se tiver plano ativo e pagamento em dia. | Academia / gestão do sistema |
| RN05 | A reserva exige liberação médica válida. | Profissional de saúde / gestão da academia |
| RN07 | O aluno só reserva aulas compatíveis com seu nível de mobilidade. | Profissional de saúde / gestão da academia |

## 5. Prioridade

**Classificação MoSCoW (marque uma):** [X] Must have (essencial)  [ ] Should have (importante)  [ ] Could have (desejável)  [ ] Won't have nesta versão (fora do escopo atual)

**Justificativa da prioridade:** A reserva de aulas é uma funcionalidade central do sistema e precisa considerar liberação médica e compatibilidade com a mobilidade do aluno para evitar riscos.

## 6. Critérios de aceitação

| ID | Dado/Quando | Então (resultado esperado) | Evidência ou forma de verificação |
|---|---|---|---|
| CA-01 | Dado que o aluno está cadastrado e possui plano ativo, quando tentar reservar uma aula | Então o sistema verifica a disponibilidade da aula e a validade da liberação médica. | Tela de confirmação da reserva ou mensagem de bloqueio. |
| CA-02 | Dado que a aula está lotada, quando o aluno tentar reservar | Então o sistema impede a reserva e informa que não há vaga disponível. | Mensagem de erro em linguagem simples. |
| CA-03 | Dado que a aula não é compatível com o nível de mobilidade do aluno, quando tentar reservar | Então o sistema bloqueia a reserva e sugere opções adequadas. | Lista filtrada de aulas compatíveis. |

## 7. Validação e rastreabilidade

| Campo | Preenchimento |
|---|---|
| Situação | [X] Pendente de validação  [ ] Validado  [ ] Necessita revisão |
| Validado por / data | [a preencher] |
| Observações e decisões | Requisito consolidado a partir do RF03 (Reservar aula) da Ficha de Requisitos da Unidade 1. A liberação médica e a compatibilidade de mobilidade foram incorporadas como critérios obrigatórios. |
| Links relacionados | `Unidade1/Atividade.md` (Ficha de Requisitos); `Unidade2/atividade.md` (Casos de Uso) |
