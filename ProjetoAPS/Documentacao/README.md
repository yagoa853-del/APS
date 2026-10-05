# 📋 Projeto de APS — Longevo Fit: Academia 60+

## Levantamento e Priorização de Requisitos

**Etapa:** Levantamento de Requisitos  
**Técnica de Priorização:** MoSCoW  
**Data:** 10/09/2026  
**Turma:** D2  
**Disciplina:** Análise e Projeto de Sistemas — UDF

---

# 1. Identificação do Grupo

| Integrante | Nome |
| --- | --- |
| 1 | Pedro Henrique Silva Monteiro — [@phsmontheiro-glitch](https://github.com/phsmontheiro-glitch) |
| 2 | Yago Alves de Carvalho — [@yagoa853-del](https://github.com/yagoa853-del) |
| 3 | Igor Jesus da Silva Tolentino — [@igorjesusdasilvatoletntino](https://github.com/igorjesusdasilvatoletntino) |
| 4 | Luiz Daniel da Costa Bastos — [@luizdanieldacostabastosbastos-creator](https://github.com/luizdanieldacostabastosbastos-creator) |
| 5 | Pedro Borges Prudente Machado — [@PedroBPMachado](https://github.com/PedroBPMachado) |
| 6 | Robson Otávio Queiroz Castro — [@robsonotavioqueirozcastroo343-pixel](https://github.com/robsonotavioqueirozcastroo343-pixel) |

---

# 2. Identificação do Projeto

## Nome do projeto

**Longevo Fit: Academia 60+**

## Descrição resumida do projeto

O projeto consiste na especificação de um sistema de software para apoiar a gestão de uma academia voltada a pessoas com 60 anos ou mais. O sistema concentra cadastro de alunos, ficha de saúde, liberação médica, planos, aulas adaptadas, reservas, pagamentos e acessibilidade, com foco em segurança, autonomia e acompanhamento por familiares ou cuidadores.

---

# 3. Problema Identificado

## 3.1 Qual problema será resolvido?

**Resposta:**

O problema identificado é a falta de organização e centralização das informações de saúde, liberação médica, mobilidade e reservas em academias voltadas a idosos. Quando esses dados ficam dispersos, há risco de alunos realizarem aulas inadequadas, de professores não saberem quais limitações existem e de familiares ou cuidadores dependerem de comunicação manual e pouco segura.

## 3.2 Quem é afetado pelo problema?

**Resposta:**

Os principais afetados são os alunos idosos (60+), seus familiares/cuidadores, os professores, o profissional de saúde (fisioterapeuta), os funcionários e os administradores da academia.

## 3.3 Como o problema é resolvido atualmente?

**Resposta:**

Atualmente, boa parte do processo ocorre por telefone, fichas em papel, mensagens e registros manuais. Esse cenário pode dificultar o controle das liberações médicas, da compatibilidade da aula com o nível de mobilidade e da consulta rápida de contatos de emergência.

## 3.4 Principais dificuldades encontradas

- Informações de saúde descentralizadas
- Risco de reservas em aulas inadequadas
- Dificuldade com tecnologia para alguns alunos idosos
- Dependência de familiares ou cuidadores para acompanhar o uso do sistema
- Falta de visibilidade de liberações médicas vencidas ou próximas do vencimento
- Necessidade de acesso restrito a dados sensíveis de saúde

---

# 4. Objetivo do Projeto

## Objetivo

Nosso projeto pretende desenvolver a especificação de um sistema para academias focadas em pessoas com 60 anos ou mais, contribuindo para a organização de dados cadastrais, saúde, reservas, pagamentos e acessibilidade, além de reduzir riscos e facilitar a rotina de alunos, professores e funcionários.

---

# 5. Stakeholders

| ID | Stakeholder | Papel | Necessidade/Interesse | Influência | Principal |
| --- | --- | --- | --- | --- | :---: |
| **ST01** | **Aluno idoso (60+)** | Usuário principal do sistema | Reservar aulas, consultar plano, acompanhar reservas e acessar dados pessoais | **Alta** | ⭐ |
| **ST02** | **Professor** | Responsável pelas aulas | Verificar procedimentos e contato de emergência, acompanhar alunos | Média | |
| **ST03** | **Funcionário** | Operação da academia | Cadastrar alunos, validar liberação médica e acompanhar reservas | Alta | |
| **ST04** | **Administrador** | Gestão da academia | Gerenciar usuários, aulas, planos e permissões | Alta | |
| **ST05** | **Profissional de saúde / fisioterapeuta** | Avaliação e acompanhamento clínico | Registrar ficha de saúde e alterar mobilidade do aluno | Alta | |
| **ST06** | **Familiar / Cuidador** | Acompanhamento do aluno | Consultar reservas e pagamentos, sem acesso à ficha de saúde | Média | |
| **ST07** | **Aluno / público 60+ com dificuldade tecnológica** | Usuário com necessidade de acessibilidade | Usar a interface com clareza, poucos passos e fontes legíveis | Alta | |

## Stakeholder principal

**Stakeholder:** Alunos idosos (60+)  
**Por que ele foi considerado principal?**  
Porque é o público para o qual o sistema foi desenhado e é aquele que concentra as necessidades mais relevantes de acessibilidade, segurança e autonomia.

---

# 6. Levantamento de Informações

| Pergunta | Resposta |
| --- | --- |
| Você usa celular? Para quê? | [a preencher após entrevista com idoso] |
| Tem alguma condição de saúde que limite exercícios? | [a preencher após entrevista com idoso] |
| Prefere ligar, ir presencialmente ou usar o app? | [a preencher após entrevista com idoso] |
| Qual tipo de aula você consegue fazer com mais conforto? | [a preencher após entrevista com idoso] |
| Você prefere receber lembretes por WhatsApp, ligação ou mensagem no app? | [a preencher após entrevista com idoso] |
| Precisa de ajuda de familiar ou cuidador para usar o sistema? | [a preencher após entrevista com idoso] |
| Existe alguma restrição de mobilidade ou de impacto para você? | [a preencher após entrevista com idoso] |

---

# 7. Necessidades Identificadas

| ID | Stakeholder | Necessidade Identificada | Problema Relacionado |
| --- | --- | --- | --- |
| N01 | Aluno idoso | Realizar cadastro com dados e contato de emergência | Dificuldade de registro e falta de identificação do aluno |
| N02 | Aluno idoso | Reservar aulas compatíveis com seu nível de mobilidade | Risco de aula inadequada |
| N03 | Aluno idoso | Consultar reservas e pagamentos | Falta de organização e acompanhamento |
| N04 | Funcionário | Validar liberação médica e controlar acesso | Ausência de controle de autorização |
| N05 | Funcionário | Cadastrar e manter aulas e planos | Falta de atualização da academia |
| N06 | Professor | Consultar contato de emergência durante a aula | Dificuldade de agir em caso de emergência |
| N07 | Administrador | Controlar acesso por perfil | Risco de acesso indevido a dados sensíveis |
| N08 | Academia | Centralizar dados de alunos, reservas e pagamentos | Informações dispersas em diferentes canais |
| N09 | Profissional de saúde | Registrar ficha de saúde | Falta de documentação clínica centralizada |
| N10 | Academia | Garantir liberação médica válida antes da reserva | Risco de aula sem autorização |
| N11 | Professor | Acessar contato de emergência | Necessidade de resposta rápida em aula |
| N12 | Aluno idoso | Visualizar apenas aulas adequadas para seu nível | Reserva em atividades inadequadas |
| N13 | Familiar / Cuidador | Acompanhar reservas e pagamentos | Dependência de contato manual e pouca visibilidade |
| N14 | Aluno idoso | Utilizar a interface com clareza e poucos passos | Dificuldade com tecnologia |

---

# 8. Requisitos Funcionais

| ID | Requisito Funcional | Stakeholder/Fonte | Necessidade | Prioridade |
| --- | --- | --- | --- | --- |
| RF01 | Cadastrar aluno | Aluno / Funcionário | N01 | Alta |
| RF02 | Consultar planos | Aluno | N03 | Média |
| RF03 | Reservar aula | Aluno | N02 | Alta |
| RF04 | Cancelar reserva | Aluno | N03 | Alta |
| RF05 | Cadastrar e editar aulas | Funcionário | N05 | Alta |
| RF06 | Cadastrar e editar planos | Funcionário / Administrador | N05 | Média |
| RF07 | Consultar pagamentos | Aluno / Funcionário | N03 | Alta |
| RF08 | Consultar dados e reservas | Aluno | N03 | Média |
| RF09 | Registrar ficha de saúde | Profissional de saúde | N09 | Alta |
| RF10 | Registrar e validar liberação médica | Funcionário / Academia | N10 | Alta |
| RF11 | Gerenciar contato de emergência | Professor / Aluno | N06 / N01 | Média |
| RF12 | Classificar aulas por nível de mobilidade | Profissional de saúde / Aluno | N02 / N12 | Média |
| RF13 | Vincular familiar ou cuidador | Aluno | N13 | Baixa |

---

# 9. Requisitos de Qualidade / Não Funcionais

| ID | Característica de Qualidade | Requisito | Como será verificado? |
| --- | --- | --- | --- |
| **RQ01** | Desempenho | O sistema deve responder em até 3 segundos em consultas simples. | Testes de tempo de resposta. |
| **RQ02** | Segurança | O sistema deve restringir acesso conforme o perfil do usuário. | Testes com diferentes perfis. |
| **RQ03** | Usabilidade | A interface deve ser clara e compreensível, com linguagem simples. | Testes com usuários e validação de linguagem. |
| **RQ04** | Disponibilidade | O sistema deve estar acessível durante o horário de funcionamento da academia. | Monitoramento e verificações de disponibilidade. |
| **RQ05** | Acessibilidade | O sistema deve suportar fonte ajustável, contraste adequado e interação simples. | Validação por critérios WCAG AA e testes com usuários. |
| **RQ06** | Confiabilidade | O sistema deve impedir reservas sem vagas e liberar corretamente a vaga. | Testes com cenários de lotação e cancelamento. |
| **RQ07** | Compatibilidade/Portabilidade | O sistema deve funcionar corretamente nos navegadores em uso. | Testes no navegador principal e em versões recentes. |

### Mapeamento dos antigos RQ para RNF

| Antigo | Novo | Descrição |
| --- | --- | --- |
| RQ02 Segurança | **RNF01** | Dados sensíveis devem ter acesso restrito e controle por perfil. |
| RQ01 Desempenho | **RNF02** | Consultas simples em até 3 segundos. |
| RQ03 Usabilidade | **RNF03** | Mensagens em linguagem simples, sem termos técnicos. |
| RNF04 Disponibilidade | **RNF04** | Manter acessibilidade durante o horário de funcionamento. |
| **RNF05 Acessibilidade** | **RNF05** | Fonte 16pt+, contraste 4,5:1, botões 48px e poucos cliques. |
| RQ04 Confiabilidade | **RNF06** | Impedir reserva sem vagas. |
| RQ05 Compatibilidade/Portabilidade | **RNF07** | Compatibilidade com navegadores. |

---

# 10. Restrições

| ID | Restrição | Categoria | Justificativa/Fonte |
| --- | --- | --- | --- |
| RES01 | O projeto será desenvolvido dentro do prazo da disciplina. | Prazo | Limitação acadêmica. |
| RES02 | O sistema será desenvolvido com recursos disponíveis ao grupo. | Tecnologia | Limitação de infraestrutura e conhecimento. |
| RES03 | O projeto não contempla integrações complexas com sistemas externos nesta etapa. | Escopo | Definição do escopo acadêmico. |

---

# 11. Regras de Negócio

| ID | Regra de Negócio |
| --- | --- |
| RN01 | Um aluno só pode reservar uma aula com vaga disponível. |
| RN02 | Cada usuário só acessa as funcionalidades do seu perfil. |
| RN03 | O cancelamento de uma reserva libera a vaga. |
| RN04 | O aluno só reserva aulas se tiver plano ativo e pagamento em dia. |
| RN05 | A reserva exige liberação médica válida. |
| RN06 | A liberação médica vale por 12 meses a partir da emissão. |
| RN07 | O aluno só reserva aulas compatíveis com seu nível de mobilidade. |
| RN08 | O cadastro exige ao menos um contato de emergência. |
| RN09 | A ficha de saúde só pode ser vista pelo aluno, pelo profissional de saúde e por funcionários autorizados. |

---

# 12. Rastreabilidade

| Necessidade | Stakeholder | Requisito(s) relacionado(s) |
| --- | --- | --- |
| N01 | Aluno / Funcionário | RF01, RF11 |
| N02 | Aluno | RF03, RF12 |
| N03 | Aluno | RF02, RF04, RF07, RF08 |
| N04 | Funcionário | RF10 |
| N05 | Funcionário / Administrador | RF05, RF06 |
| N06 | Professor | RF11 |
| N07 | Administrador | RNF01 |
| N08 | Academia | RF01, RF05, RF06, RF07, RF08 |
| N09 | Profissional de saúde | RF09 |
| N10 | Academia | RF10 |
| N11 | Professor | RF11 |
| N12 | Aluno | RF12 |
| N13 | Familiar / Cuidador | RF13 |
| N14 | Aluno idoso | RNF05 |

### Rastreabilidade específica da discussão de requisitos

- N09 → RF09
- N10 → RF10
- N11 → RF11
- N12 → RF12
- N13 → RF13
- N14 → RNF05
- N07 → RNF01

---

# 13. Priorização dos Requisitos — Técnica MoSCoW

| ID | Requisito | MoSCoW | Justificativa |
| --- | --- | --- | --- |
| RF09 | Registrar ficha de saúde | **Must** | Sem ficha de saúde não há como garantir segurança e acompanhamento clínico. |
| RF10 | Registrar e validar liberação médica | **Must** | Liberação médica é pré-condição de reserva e essencial para segurança. |
| RF11 | Gerenciar contato de emergência | **Should** | Ajuda em situações de urgência, mas não bloqueia o uso principal do sistema. |
| RF12 | Classificar aulas por nível de mobilidade | **Should** | É importante para reduzir riscos e adequar treinamentos ao aluno. |
| RF13 | Vincular familiar ou cuidador | **Could** | Funcionalidade útil, mas não essencial para a operação principal. |
| RNF05 | Acessibilidade | **Must** | O público depende diretamente de uma interface clara, legível e simples. |
| RNF01 | Segurança | **Must** | Protege dados sensíveis e controla acesso. |
| RF01 | Cadastrar aluno | **Must** | Necessário para registrar o aluno no sistema. |
| RF03 | Reservar aula | **Must** | Core da experiência do usuário e da academia. |

---

# 14. Requisitos da Primeira Versão

Após aplicar a técnica MoSCoW, os **8 requisitos** considerados indispensáveis para a primeira versão são:

| Ordem | ID | Requisito | Por que deve estar na primeira versão? |
| --- | --- | --- | --- |
| 1 | RF01 | Cadastrar aluno | Base para identificação e uso do sistema. |
| 2 | RF03 | Reservar aula | Funcionalidade central para alunos. |
| 3 | RF04 | Cancelar reserva | Permite corrigir reservas e liberar vagas. |
| 4 | RF05 | Cadastrar e editar aulas | Necessário para manter a oferta de aulas. |
| 5 | RF09 | Registrar ficha de saúde | Garante segurança do aluno e do ambiente. |
| 6 | RF10 | Registrar e validar liberação médica | Pré-condição para segurança e reserva. |
| 7 | RNF01 | Segurança | Protege dados pessoais sensíveis. |
| 8 | RNF05 | Acessibilidade | Fundamenta a experiência de uso do público 60+. |

---

# 15. Requisitos para Versões Futuras

| ID | Requisito | Motivo para adiar | Impacto |
| --- | --- | --- | --- |
| RF02 | Consultar planos | Pode ser entregue em momento posterior, após a base do sistema. | Baixo |
| RF06 | Cadastrar e editar planos | Relevante, mas não essencial para o funcionamento inicial. | Médio |
| RF07 | Consultar pagamentos | Importante, mas não bloqueia a operação principal. | Médio |
| RF13 | Vincular familiar ou cuidador | Pode ser implementado em versões posteriores. | Baixo |

---

# 16. Revisão por Pares

| ID do Requisito | Problema Encontrado | Sugestão de Melhoria |
| --- | --- | --- |
| RF03 | Necessidade de validar liberação médica e compatibilidade de mobilidade. | Especificar checagens obrigatórias antes da reserva. |
| RF10 | Liberação médica pode expirar. | Definir alerta em 30 dias e bloqueio automático. |
| RNF05 | Acessibilidade precisa ser mensurável. | Definir fontes, contraste e número de cliques. |
| RF09 | Dados de saúde são sensíveis. | Restringir visualização a usuários autorizados. |
| RF01 | Cadastro de idosos exige confirmação de emergência. | Definir ao menos um contato como critério obrigatório. |

---

# 17. Checklist de Qualidade dos Requisitos

- [x] Os requisitos estão completos?
- [x] Os requisitos estão corretos em relação às necessidades?
- [x] Cada requisito representa uma única capacidade ou característica?
- [x] Os requisitos são necessários?
- [x] Os requisitos são viáveis?
- [x] Todos possuem prioridade?
- [x] Termos ambíguos foram eliminados?
- [x] Os requisitos podem ser verificados ou testados?
- [x] A fonte ou stakeholder está identificado?
- [x] As necessidades estão relacionadas aos requisitos?
- [x] As prioridades MoSCoW possuem justificativa?

---

# 18. Reflexão do Grupo

## 18.1 Qual requisito gerou mais discussão durante o levantamento? Por quê?

**Resposta do grupo:**  
O requisito de reserva de aulas gerou maior discussão, pois envolve liberação médica, mobilidade, vagas, pagamento e segurança. Isso exigiu atenção para evitar riscos ao aluno.

## 18.2 Qual necessidade inicialmente parecia simples, mas gerou vários requisitos?

**Resposta do grupo:**  
A necessidade de organizar as aulas e o cadastro de alunos acabou gerando requisitos como ficha de saúde, liberação médica, contato de emergência, compatibilidade por mobilidade e acesso restrito.

## 18.3 Houve algum requisito implícito durante a discussão?

**Resposta do grupo:**  
Sim. Identificamos que o sistema deveria impedir reservas sem liberação e garantir que o usuário visualizasse apenas aulas adequadas ao seu nível.

## 18.4 Qual requisito foi mais difícil de priorizar?

**Resposta do grupo:**  
Os requisitos de saúde e acessibilidade foram mais difíceis, porque estão diretamente ligados à segurança e ao bem-estar do público 60+, mas também exigem esforço de implementação e documentação.

## 18.5 Houve algum requisito inicialmente considerado Must que mudou de prioridade?

**Resposta do grupo:**  
Sim. Alguns aspectos de acompanhamento e vínculo familiar foram analisados como úteis em versões futuras, e não essenciais à primeira operação do sistema.

---

# 19. Conclusão

O projeto investigou o problema relacionado ao gerenciamento de uma academia voltada a pessoas com 60 anos ou mais, identificando necessidades de saúde, acesso, mobilidade, segurança e autonomia. A partir dessas necessidades, foram definidos 13 requisitos funcionais, 7 requisitos não funcionais e 9 regras de negócio.

A análise mostrou que a primeira versão do sistema deve priorizar cadastro, reserva, liberação médica, ficha de saúde e acessibilidade. A técnica MoSCoW foi essencial para diferenciar o que é indispensável do que pode ser entregue em versões posteriores.

## 📄 Documento MoSCoW

[PDF a ser regenerado]

---

# 📦 Entregável

O projeto contempla:

- Identificação do projeto e dos integrantes
- Descrição do problema e do objetivo
- Identificação dos stakeholders
- Levantamento das necessidades
- 13 requisitos funcionais
- 7 requisitos não funcionais
- 9 regras de negócio
- Rastreabilidade entre necessidades e requisitos
- Priorização utilizando MoSCoW
- Definição dos requisitos da primeira versão
- Revisão por pares
- Reflexão do grupo
- Conclusão

---

# 📚 Referência

REINEHR, Sheila. **Requisitos de Software.** Material de apoio utilizado na disciplina Engenharia de Requisitos.

**Disciplina:** Engenharia de Requisitos  
**Projeto:** Levantamento e Priorização de Requisitos  
**Profª:** Kadidja Valéria
