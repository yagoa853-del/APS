# 📋 Projeto de APS — Sistema de Gerenciamento de Academia

 ## Levantamento e Priorização de Requisitos

 **Etapa:** Levantamento de Requisitos\
 **Técnica de Priorização:** MoSCoW\
 **Data:** 10/09/2026\
 **Turma:** D2

---

 # 👥 1. Identificação do Grupo

 | Integrante | Nome |
| --- | --- |
| 1 | Pedro Henrique Silva Monteiro — [@phsmontheiro-glitch](https://github.com/phsmontheiro-glitch) |
| 2 | Yago Alves de Carvalho  — [@yagoa853-del](https://github.com/yagoa853-del) |
| 3 | Igor Jesus da Silva Tolentino  — [@igorjesusdasilvatoletntino](https://github.com/igorjesusdasilvatoletntino)|
| 4 | Luiz Daniel da Costa Bastos —  [@luizdanieldacostabastosbastos-creator](https://github.com/luizdanieldacostabastosbastos-creator)
| 5 | Pedro Borges Prudente Machado —  [@PedroBPMachado](https://github.com/PedroBPMachado)|
| 6 | Robson Otávio Queiroz Castro  — [@robsonotavioqueirozcastroo343-pixel](https://github.com/robsonotavioqueirozcastroo343-pixel)|


---

 # 2\. Identificação do Projeto

 ## Nome do projeto

 **Sistema de Gerenciamento de Academia**

 ## Descrição resumida do projeto

 O projeto consiste na especificação de um sistema de software para auxiliar no gerenciamento das principais operações de uma academia. O sistema terá como finalidade facilitar o cadastro e gerenciamento de alunos, planos e aulas, além de permitir reservas e cancelamentos de aulas, consultas de pagamentos, dados cadastrais e reservas, com controle de acesso de acordo com o perfil de cada usuário.

---

 # 3\. Problema Identificado

 ## 3.1 Qual problema será resolvido?

 **Resposta:**

 O problema identificado é a dificuldade de organizar e controlar as informações relacionadas aos alunos, planos, aulas, reservas e pagamentos de uma academia. Processos realizados de maneira manual ou descentralizada podem gerar erros, perda de informações, dificuldade para consultar dados e problemas no controle das reservas e vagas das aulas.

 ## 3.2 Quem é afetado pelo problema?

 **Resposta:**

 Os principais afetados são os alunos, professores, funcionários e administradores da academia. Os alunos precisam consultar planos, realizar e cancelar reservas; os professores precisam acompanhar suas aulas e reservas; os funcionários precisam gerenciar cadastros e informações; e os administradores precisam controlar planos, aulas, pagamentos e acessos ao sistema.

 ## 3.3 Como o problema é resolvido atualmente?

 **Resposta:**

 Atualmente, processos semelhantes podem ser realizados por meio de atendimento presencial, planilhas, registros manuais, mensagens ou sistemas separados. Essas formas de controle podem dificultar a centralização das informações e aumentar a possibilidade de erros ou informações desatualizadas.

 ## 3.4 Principais dificuldades encontradas

 - Dificuldade para organizar os dados dos alunos.
- Dificuldade para controlar reservas e cancelamentos de aulas.
- Dificuldade para acompanhar a quantidade de vagas disponíveis.
- Possibilidade de erros em registros manuais.
- Dificuldade para consultar pagamentos e informações cadastrais.
- Falta de centralização das informações.
- Dificuldade para controlar o acesso às informações de acordo com o perfil do usuário.

---

 # 🎯 4. Objetivo do Projeto

 ## Objetivo

 Nosso projeto pretende desenvolver a especificação de um sistema de gerenciamento de academia para alunos, professores, funcionários e administradores, contribuindo para a organização das informações, o controle das aulas e reservas, a segurança dos dados e a melhoria dos processos administrativos da academia.

---

 # 👤 5. Stakeholders

 | ID | Stakeholder | Papel | Necessidade/Interesse | Influência |
| --- | --- | --- | --- | --- |
| ST01 | Alunos | Usuários do sistema | Realizar reservas, consultar planos, pagamentos e dados cadastrais | Alta |
| ST02 | Professores | Responsáveis pelas aulas | Consultar e acompanhar aulas e reservas | Média |
| ST03 | Funcionários | Operação da academia | Cadastrar alunos, aulas e planos e consultar informações | Alta |
| ST04 | Administradores | Gestão do sistema | Gerenciar usuários, planos, aulas, pagamentos e acessos | Alta |
| ST05 | Academia | Organização responsável pelo serviço | Melhorar a organização e o gerenciamento das atividades | Alta |

 ## Stakeholder principal

 **Stakeholder:** Alunos

 ### Por que ele foi considerado o principal stakeholder?

 Os alunos foram considerados o principal stakeholder porque são os usuários que utilizarão diretamente diversas funcionalidades do sistema, como consulta de planos, realização e cancelamento de reservas e consulta de informações pessoais e pagamentos.

---

 # 🗣️ 6. Levantamento de Informações

 | Pergunta | Resposta |
| --- | --- |
| O que o usuário precisa fazer? | Cadastrar-se, consultar planos, reservar e cancelar aulas e consultar suas informações. |
| Qual problema enfrenta atualmente? | Dificuldade para centralizar informações e realizar o controle de aulas, reservas e dados. |
| Quais informações precisa consultar? | Planos, horários, vagas, reservas, pagamentos e dados cadastrais. |
| Quais informações precisa cadastrar ou alterar? | Dados dos alunos, aulas e planos. |
| Quais tarefas são repetitivas? | Cadastro e atualização de dados, consultas e gerenciamento de reservas. |
| Quais tarefas consomem mais tempo? | Controle de reservas, consultas e atualização de informações. |
| Quais erros acontecem atualmente? | Possíveis erros de cadastro, reservas duplicadas e informações desatualizadas. |
| Precisa receber notificações? | Poderia receber notificações sobre aulas e reservas em versões futuras. |
| Precisa gerar documentos ou relatórios? | Relatórios administrativos podem ser incluídos em versões futuras. |
| Existem informações que precisam ser protegidas? | Sim. Dados pessoais, pagamentos e informações de acesso precisam ser protegidos. |
| O sistema precisará se comunicar com outros sistemas? | Não na primeira versão. |
| Existem regras obrigatórias que precisam ser respeitadas? | Sim. É necessário respeitar permissões de acesso, disponibilidade de vagas e regras de reservas. |

---

 # 💡 7. Necessidades Identificadas

 | ID | Stakeholder | Necessidade Identificada | Problema Relacionado |
| --- | --- | --- | --- |
| N01 | Alunos | Realizar cadastro no sistema | Dificuldade de manter dados organizados |
| N02 | Alunos | Reservar aulas | Dificuldade no controle de reservas |
| N03 | Alunos | Cancelar reservas | Dificuldade para liberar vagas novamente |
| N04 | Funcionários | Gerenciar aulas | Dificuldade para cadastrar e atualizar aulas |
| N05 | Funcionários | Gerenciar planos | Dificuldade para manter informações de planos atualizadas |
| N06 | Alunos | Consultar pagamentos e dados | Dificuldade de acesso às próprias informações |
| N07 | Administradores | Controlar acesso dos usuários | Risco de acesso indevido às informações |
| N08 | Academia | Centralizar informações | Informações distribuídas em diferentes meios |

---

 # ⚙️ 8. Requisitos Funcionais

 | ID | Requisito Funcional | Stakeholder/Fonte | Necessidade | Prioridade |
| --- | --- | --- | --- | --- |
| RF01 | O sistema deve permitir o cadastro de alunos com seus dados pessoais. | Alunos / Funcionários | N01 | Alta |
| RF02 | O sistema deve permitir a consulta dos planos disponíveis. | Alunos | N06 | Média |
| RF03 | O sistema deve permitir que o aluno reserve uma aula que possua vaga disponível. | Alunos | N02 | Alta |
| RF04 | O sistema deve permitir que o aluno cancele uma reserva realizada. | Alunos | N03 | Alta |
| RF05 | O sistema deve permitir o cadastro e a edição de aulas. | Funcionários | N04 | Alta |
| RF06 | O sistema deve permitir o cadastro e a edição de planos. | Funcionários / Administradores | N05 | Média |
| RF07 | O sistema deve permitir a consulta dos pagamentos realizados pelo aluno. | Alunos / Funcionários | N06 | Alta |
| RF08 | O sistema deve permitir a consulta dos dados cadastrais e das reservas do aluno. | Alunos | N06 | Média |

---

 # ⭐ 9. Requisitos de Qualidade

 | ID | Característica de Qualidade | Requisito | Como será verificado? |
| --- | --- | --- | --- |
| RQ01 | Desempenho | O sistema deve apresentar o resultado das consultas em até 3 segundos em condições normais de uso. | Realizar testes de tempo de resposta. |
| RQ02 | Segurança | O sistema deve restringir o acesso às funcionalidades de acordo com o perfil do usuário autenticado. | Realizar testes utilizando diferentes perfis de acesso. |
| RQ03 | Usabilidade/Interação | O sistema deve apresentar uma interface clara, organizada e com navegação simples para as principais funcionalidades. | Realizar testes de uso com usuários e verificar a execução das tarefas principais. |
| RQ04 | Confiabilidade | O sistema deve impedir a realização de reservas em aulas que não possuam vagas disponíveis. | Realizar testes com aulas lotadas e verificar o comportamento do sistema. |
| RQ05 | Compatibilidade/Portabilidade | O sistema deve funcionar corretamente nos principais navegadores utilizados pelos usuários. | Realizar testes nos navegadores definidos para o projeto. |

---

 # 🚧 10. Restrições

 | ID | Restrição | Categoria | Justificativa/Fonte |
| --- | --- | --- | --- |
| RES01 | O projeto será desenvolvido dentro do prazo definido para a disciplina. | Prazo | Limitação acadêmica da disciplina. |
| RES02 | O sistema será desenvolvido utilizando os recursos tecnológicos disponíveis para o grupo. | Tecnologia/Recursos | Limitação de conhecimento, ferramentas e infraestrutura disponíveis. |
| RES03 | O projeto possui finalidade acadêmica e não contempla, nesta etapa, integrações complexas com sistemas externos. | Escopo | Definição do escopo da atividade de APS. |

---

 # 📜 11. Regras de Negócio

 | ID | Regra de Negócio | Fonte |
| --- | --- | --- |
| RN01 | Um aluno somente poderá realizar uma reserva quando houver vaga disponível na aula. | Regras do domínio da academia |
| RN02 | Cada usuário somente poderá acessar as funcionalidades permitidas para seu respectivo perfil. | Regras de segurança do sistema |
| RN03 | Uma reserva cancelada deve liberar a vaga correspondente para que outro aluno possa realizar uma nova reserva. | Regras do domínio da academia |

---

 # 🔗 12. Rastreabilidade Inicial

 | Necessidade | Stakeholder | Requisito(s) relacionado(s) |
| --- | --- | --- |
| N01 | Alunos / Funcionários | RF01 |
| N02 | Alunos | RF03 |
| N03 | Alunos | RF04 |
| N04 | Funcionários | RF05 |
| N05 | Funcionários / Administradores | RF06 |
| N06 | Alunos | RF02, RF07, RF08 |
| N07 | Administradores | RQ02 |
| N08 | Academia | RF01, RF05, RF06, RF07, RF08 |

---

 # 🏷️ 13. Priorização dos Requisitos — Técnica MoSCoW

 | ID | Requisito | MoSCoW | Justificativa |
| --- | --- | --- | --- |
| RF01 | Cadastrar aluno | **M — Must Have** | É necessário para registrar e gerenciar os usuários do sistema. |
| RF02 | Consultar planos | **S — Should Have** | É importante para que o aluno conheça os planos disponíveis, mas não impede o funcionamento básico das reservas. |
| RF03 | Reservar aula | **M — Must Have** | É uma das principais funcionalidades do sistema para os alunos. |
| RF04 | Cancelar reserva | **M — Must Have** | É necessário para permitir o gerenciamento correto das reservas e liberação de vagas. |
| RF05 | Cadastrar e editar aulas | **M — Must Have** | É necessário para manter as aulas disponíveis e atualizadas. |
| RF06 | Cadastrar e editar planos | **S — Should Have** | É importante para o gerenciamento da academia, mas pode ser priorizado após as funções básicas de alunos e aulas. |
| RF07 | Consultar pagamentos | **S — Should Have** | É uma funcionalidade importante para acompanhamento financeiro dos alunos. |
| RF08 | Consultar dados e reservas | **S — Should Have** | Facilita o acompanhamento das informações do aluno e de suas reservas. |
| RQ01 | Desempenho | **S — Should Have** | É importante para garantir uma boa experiência de uso. |
| RQ02 | Segurança | **M — Must Have** | Informações pessoais e acessos precisam ser protegidos. |
| RQ03 | Usabilidade/Interação | **M — Must Have** | A interface precisa permitir que os usuários utilizem as funções principais de maneira clara. |
| RQ04 | Confiabilidade | **M — Must Have** | O sistema precisa evitar reservas em aulas sem vagas e manter o funcionamento correto das operações. |
| RQ05 | Compatibilidade/Portabilidade | **C — Could Have** | A compatibilidade com diferentes navegadores é desejável, mas pode ser ampliada posteriormente. |

---

 # 🚀 14. Requisitos da Primeira Versão

 Após aplicar a técnica MoSCoW, os 5 requisitos considerados indispensáveis para a primeira versão são:

 | Ordem | ID | Requisito | Por que deve estar na primeira versão? |
| --- | --- | --- | --- |
| 1 | RF01 | Cadastrar aluno | É a base para identificar e gerenciar os usuários do sistema. |
| 2 | RF03 | Reservar aula | Representa uma das principais funcionalidades para os alunos. |
| 3 | RF04 | Cancelar reserva | Permite corrigir reservas e liberar vagas para outros alunos. |
| 4 | RF05 | Cadastrar e editar aulas | É necessário para disponibilizar e administrar as aulas. |
| 5 | RQ02 | Segurança | Protege os dados e garante que cada usuário tenha acesso somente às funções permitidas. |

---

 # ⏭️ 15. Requisitos para Versões Futuras

 | ID | Requisito | Motivo para adiar | Impacto |
| --- | --- | --- | --- |
| RF02 | Consultar planos | Pode ser implementado após as funcionalidades básicas de cadastro e reservas. | Baixo |
| RF06 | Cadastrar e editar planos | O gerenciamento de planos pode ser ampliado em uma versão posterior. | Médio |
| RQ05 | Compatibilidade/Portabilidade | A primeira versão pode ser validada inicialmente nos navegadores definidos pelo grupo. | Baixo |

---

 # 🔍 16. Revisão por Pares


 | ID do Requisito | Problema Encontrado | Sugestão de Melhoria |
| --- | --- | --- |
| RF03 | Necessidade de verificar a disponibilidade de vagas. | Especificar que somente aulas com vagas disponíveis podem ser reservadas. |
| RF04 | Necessidade de definir o efeito do cancelamento. | Determinar que o cancelamento libera a vaga da aula. |
| RQ01 | O tempo de resposta precisa ser mensurável. | Definir o limite máximo de 3 segundos. |
| RQ02 | Necessidade de diferenciar os perfis de acesso. | Definir permissões conforme o perfil do usuário. |
| RF01 | Dados necessários para cadastro precisam estar definidos. | Especificar os principais dados pessoais necessários. |

---

 # ✅ 17. Checklist de Qualidade dos Requisitos

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
- [x] Os requisitos de qualidade são mensuráveis sempre que possível?
- [x] As prioridades MoSCoW possuem justificativa?

---

 # 💭 18. Reflexão do Grupo

 ## 18.1 Qual requisito gerou mais discussão durante o levantamento? Por quê?

 **Resposta do grupo:**

 O requisito de reserva de aulas gerou mais discussão porque envolve diferentes situações, como disponibilidade de vagas, cancelamento de reservas e controle da quantidade de alunos por aula. Foi necessário analisar essas situações para definir um comportamento claro para o sistema.

 ## 18.2 Qual necessidade inicialmente parecia simples, mas gerou vários requisitos?

 **Resposta do grupo:**

 A necessidade de organizar as aulas inicialmente parecia simples, mas acabou envolvendo o cadastro e edição das aulas, consulta de horários, controle de vagas, reservas e cancelamentos.

 ## 18.3 O grupo identificou algum requisito implícito durante a discussão?

 **Resposta do grupo:**

 Sim. Durante a discussão, identificamos a necessidade de controle de acesso por perfil de usuário. Também percebemos que o sistema deveria impedir reservas quando não houvesse vagas disponíveis.

 ## 18.4 Qual requisito foi mais difícil de priorizar utilizando MoSCoW? Por quê?

 **Resposta do grupo:**

 O requisito de consulta de pagamentos foi um dos mais difíceis de priorizar, pois é importante para o aluno e para a academia, mas não é essencial para que as funções básicas de cadastro, aulas e reservas funcionem.

 ## 18.5 Houve algum requisito inicialmente considerado Must que mudou de prioridade?

 **Resposta do grupo:**

 Sim. A consulta de planos e a consulta de pagamentos foram inicialmente consideradas indispensáveis, mas após analisar o funcionamento básico do sistema, o grupo decidiu classificá-las como Should Have, pois podem ser implementadas após as funcionalidades essenciais.

---

 # 📝 19. Conclusão

 **Conclusão:**

 O projeto investigou o problema relacionado ao gerenciamento de alunos, aulas, planos, reservas e pagamentos em uma academia. Os principais stakeholders identificados foram alunos, professores, funcionários, administradores e a própria academia.

 Durante o levantamento, foram identificadas necessidades relacionadas principalmente ao cadastro de alunos, gerenciamento de aulas, realização e cancelamento de reservas, consulta de informações e segurança dos dados.

 A partir dessas necessidades, foram definidos oito requisitos funcionais e cinco requisitos de qualidade. Entre eles, foram considerados essenciais para a primeira versão o cadastro de alunos, a reserva e o cancelamento de aulas, o gerenciamento das aulas e a segurança do sistema.

 A técnica MoSCoW auxiliou o grupo a organizar os requisitos de acordo com seu grau de importância, permitindo diferenciar aquilo que é indispensável daquilo que pode ser desenvolvido posteriormente. Dessa forma, foi possível estabelecer um escopo mais realista para a primeira versão do sistema e definir funcionalidades que poderão ser implementadas em versões futuras.


## 📄 Documento MoSCoW

[Acessar o PDF — Sistema de Gestão para Academias de Musculação (MoSCoW)](https://github.com/yagoa853-del/APS/blob/main/ProjetoAPS/Sistema_de_Gest%C3%A3o_para_Academias_de_Muscula%C3%A7%C3%A3o_MoSCoW.pdf)

---
 # 📦 Entregável

 O projeto contempla:

 - Identificação do projeto e dos integrantes;
- Descrição do problema;
- Objetivo do projeto;
- Identificação dos stakeholders;
- Levantamento das necessidades;
- 8 requisitos funcionais;
- 5 requisitos de qualidade;
- 3 restrições;
- 3 regras de negócio;
- Rastreabilidade entre necessidades e requisitos;
- Priorização utilizando MoSCoW;
- Definição dos requisitos da primeira versão;
- Requisitos para versões futuras;
- Revisão dos requisitos;
- Reflexão do grupo;
- Conclusão.

---

 # 📚 Referência

 REINEHR, Sheila. **Requisitos de Software.** Material de apoio utilizado na disciplina Engenharia de Requisitos.

 **Disciplina:** Engenharia de Requisitos\
 **Projeto:** Levantamento e Priorização de Requisitos\
 **Profª:** Kadidja Valéria
