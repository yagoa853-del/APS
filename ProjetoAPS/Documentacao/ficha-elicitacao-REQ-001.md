# Ficha de Elicitação de Requisitos

**Curso:** Engenharia de Software
**Disciplina:** Análise e Projeto de Sistemas
**Instituição:** UDF Centro Universitário
**Grupo/integrantes:** Pedro Henrique Silva Monteiro, Pedro Borges Prudente Machado, Yago Alves de Carvalho, Robson Otávio Queiroz Castro, Igor Jesus da Silva Tolentino, Luiz Daniel da Costa Bastos
**Turma:** D2  **Data:** 24/09/2026  **Versão:** 1.0

> Preencha uma ficha para cada requisito identificado. Registre a necessidade na linguagem do stakeholder e esclareça termos ambíguos antes de validar a ficha com ele.

## 1. Identificação do projeto

| Campo | Preenchimento |
|---|---|
| Nome do projeto | Sistema de Gestão para Academias de Musculação |
| Objetivo do projeto | Resolver a dificuldade de controle manual das operações de uma academia (matrículas, planos, aulas, reservas e pagamentos), oferecendo um sistema que centralize e automatize essas rotinas, reduzindo erros e retrabalho para alunos, professores e funcionários. |
| Contexto e escopo | O sistema contemplará o processo de gerenciamento de alunos, consulta e cadastro de planos, reserva e cancelamento de aulas, cadastro e edição de aulas, consulta de pagamentos e consulta de dados cadastrais/reservas, com controle de acesso por perfil de usuário (aluno, professor, funcionário e administrador). |

## 2. Stakeholder e fonte

| Campo | Preenchimento |
|---|---|
| Stakeholder (nome ou papel) | Aluno da academia |
| Relação com o projeto | Usuário final do sistema |
| Contato ou setor (se aplicável) | Alunos matriculados na academia (público-alvo do sistema) |
| Técnica e data da elicitação | Entrevista/levantamento de requisitos em grupo; setembro de 2026 |
| Responsável pelo registro | Grupo APS — UDF |

## 3. Requisito elicitado

| Campo | Preenchimento |
|---|---|
| ID do requisito | REQ-003 |
| Necessidade relatada pelo stakeholder | "Quero conseguir reservar minha vaga em uma aula pelo aplicativo, sem precisar ligar ou ir até a recepção da academia." |
| Descrição consolidada | O sistema deve permitir que o aluno autenticado reserve uma vaga em uma aula disponível, dentro do limite de vagas da turma, e visualize a confirmação da reserva. |
| Justificativa ou benefício esperado | Agiliza o processo de agendamento, evita deslocamentos e ligações desnecessárias, e reduz a sobrecarga da recepção da academia. |
| Tipo | Funcional (corresponde ao RF03 — Reservar aula) |
| Dependências ou dúvidas | Depende do RF05 (Cadastrar e editar aulas), pois só é possível reservar aulas previamente cadastradas. Dúvida a esclarecer: existe limite de reservas simultâneas por aluno? |

## 4. Regras de negócio

| ID | Regra de negócio relacionada | Fonte ou responsável pela validação |
|---|---|---|
| RN-001 | Uma aula não pode receber mais reservas do que o número de vagas disponível na turma. | Coordenação/gestão da academia |
| RN-002 | O aluno só pode reservar aulas incluídas no plano ao qual está vinculado. | Coordenação/gestão da academia |

## 5. Prioridade

**Classificação MoSCoW (marque uma):** [X] Must have (essencial)  [ ] Should have (importante)  [ ] Could have (desejável)  [ ] Won't have nesta versão (fora do escopo atual)

**Justificativa da prioridade:** A reserva de aulas é uma das funcionalidades centrais do sistema (classificada como Prioridade Alta na Ficha de Requisitos da Unidade 1), pois é o principal ponto de contato do aluno com o serviço oferecido pela academia; sem ela, o sistema não cumpre seu objetivo principal.

## 6. Critérios de aceitação

| ID | Dado/Quando | Então (resultado esperado) | Evidência ou forma de verificação |
|---|---|---|---|
| CA-01 | Dado que a aula possui vagas disponíveis, quando o aluno confirmar a reserva | Então o sistema registra a reserva, decrementa o número de vagas disponíveis e exibe uma mensagem de confirmação | Teste manual/automatizado confirmando o registro da reserva e a atualização do número de vagas |
| CA-02 | Dado que a aula já atingiu o limite máximo de vagas, quando o aluno tentar reservá-la | Então o sistema impede a reserva e exibe uma mensagem informando que não há vagas disponíveis | Teste manual/automatizado simulando turma lotada |
| CA-03 | Dado que o aluno já possui uma reserva na mesma aula, quando ele tentar reservar novamente | Então o sistema impede a reserva duplicada e informa que já existe uma reserva ativa para aquela aula | Teste manual/automatizado verificando tentativa de reserva duplicada |

## 7. Validação e rastreabilidade

| Campo | Preenchimento |
|---|---|
| Situação | [X] Pendente de validação  [ ] Validado  [ ] Necessita revisão |
| Validado por / data | A definir |
| Observações e decisões | Requisito consolidado a partir do RF03 (Reservar aula) da Ficha de Requisitos da Unidade 1; será refinado na especificação de casos de uso da Unidade 2. |
| Links relacionados | `Unidade1/Atividade.md` (Ficha de Requisitos); `Unidade2/atividade.md` (Casos de Uso, em desenvolvimento) |
