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
| Objetivo do projeto | Facilitar a gestão de uma academia voltada a pessoas com 60 anos ou mais, com foco em segurança, saúde e acompanhamento adequado das atividades físicas. |
| Contexto e escopo | O sistema contempla cadastro de alunos, liberação médica, ficha de saúde, aulas adaptadas, reservas, e controle de acesso por perfil. |

## 2. Stakeholder e fonte

| Campo | Preenchimento |
|---|---|
| Stakeholder (nome ou papel) | Funcionário da academia / gestão da academia |
| Relação com o projeto | Usuário operacional do sistema |
| Contato ou setor (se aplicável) | Recepção e gestão da academia |
| Técnica e data da elicitação | Entrevista / levantamento de requisitos em grupo; [a preencher] |
| Responsável pelo registro | Grupo APS — UDF |

## 3. Requisito elicitado

| Campo | Preenchimento |
|---|---|
| ID do requisito | RF10 |
| Necessidade relatada pelo stakeholder | "Preciso saber se o aluno tem liberação médica válida antes de deixar ele reservar ou participar de aula. Se a autorização estiver vencida, quero receber alerta para tomar a devida ação." |
| Descrição consolidada | O sistema deve registrar a liberação médica do aluno, informar data de emissão, validade e nome do médico, sinalizar vencimento e impedir reservas sem autorização válida. |
| Justificativa ou benefício esperado | Reduz riscos à saúde dos alunos, evita aulas inadequadas e melhora a rotina da recepção e da gestão da academia. |
| Tipo | Funcional (corresponde ao RF10 — Registrar e validar liberação médica) |
| Dependências ou dúvidas | Depende do cadastro do aluno e do mecanismo de alerta de vencimento. Dúvida a esclarecer: "Como o sistema deve tratar uma liberação vencida quando o aluno já reservou aulas futuras?" Sugestão: bloquear novas reservas e avisar o cliente sobre o vencimento. |

## 4. Regras de negócio

| ID | Regra de negócio relacionada | Fonte ou responsável pela validação |
|---|---|---|
| RN05 | A reserva exige liberação médica válida. | Academia / profissional de saúde |
| RN06 | A liberação médica vale por 12 meses a partir da emissão. | Academia / profissional de saúde |
| RN02 | Cada usuário só acessa as funcionalidades do seu perfil. | Sistema / gestão |

## 5. Prioridade

**Classificação MoSCoW (marque uma):** [X] Must have (essencial)  [ ] Should have (importante)  [ ] Could have (desejável)  [ ] Won't have nesta versão (fora do escopo atual)

**Justificativa da prioridade:** A liberação médica é pré-condição para a participação segura em aulas e, portanto, essencial para o funcionamento do sistema.

## 6. Critérios de aceitação

| ID | Dado/Quando | Então (resultado esperado) | Evidência ou forma de verificação |
|---|---|---|---|
| CA-01 | Dado que o funcionário cadastra a liberação médica com data de emissão, validade e nome do médico, quando salvar | Então o sistema registra a autorização e a torna válida para uso. | Registro exibido na ficha do aluno. |
| CA-02 | Dado que a liberação está próxima do vencimento (30 dias), quando o sistema processar a validação | Então o sistema emite alerta ao aluno e ao funcionário. | Mensagem de aviso na interface. |
| CA-03 | Dado que a liberação está vencida, quando o aluno tentar reservar uma aula | Então o sistema bloqueia a reserva e exige atualização da autorização. | Mensagem de bloqueio em linguagem simples. |

## 7. Validação e rastreabilidade

| Campo | Preenchimento |
|---|---|
| Situação | [X] Pendente de validação  [ ] Validado  [ ] Necessita revisão |
| Validado por / data | [a preencher] |
| Observações e decisões | Requisito consolidado a partir do RF10 (Registrar e validar liberação médica) da Ficha de Requisitos da Unidade 1. A validação da vigência é essencial para resguardar a segurança do aluno. |
| Links relacionados | `Unidade1/Atividade.md` (Ficha de Requisitos); `Unidade2/atividade.md` (Casos de Uso) |
