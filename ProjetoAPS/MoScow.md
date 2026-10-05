# 🏢 Longevo Fit: Academia 60+ - APS

## 📋 Descrição do Projeto

Repositório de atividades práticas referentes à disciplina de **Análise e Projeto de Sistemas (APS)**, em que desenvolvemos a especificação de um **Longevo Fit: Academia 60+** para apoiar a gestão de alunos idosos, saúde, reservas e acessibilidade.

O projeto tem como objetivo definir requisitos, regras de negócio e casos de uso para uma academia voltada a pessoas com 60 anos ou mais, centralizando cadastro de alunos, ficha de saúde, liberação médica, planos, aulas adaptadas, reservas e pagamentos, com interface acessível e participação opcional de familiares ou cuidadores.

---

## 5W - Visão Geral do Projeto

### **WHAT (O QUÊ?)**
**O que é o projeto?**

Um sistema de software para gestão de uma academia direcionada a pessoas com 60 anos ou mais, contemplando:

- ✅ Cadastro de alunos idosos (60+)
- ✅ Registro da ficha de saúde
- ✅ Validação da liberação médica
- ✅ Cadastro de contatos de emergência
- ✅ Classificação de aulas por nível de mobilidade
- ✅ Reserva e cancelamento de aulas adaptadas
- ✅ Cadastro e edição de planos
- ✅ Consulta de pagamentos e reservas
- ✅ Vinculação de familiar ou cuidador
- ✅ Controle de acesso por perfil de usuário
- ✅ Interface acessível e de fácil uso

### **WHY (POR QUÊ?)**
**Por que fazer este projeto?**

- 👴 **Envelhecimento da população:** a demanda por serviços e atividades adequadas para pessoas com 60 anos ou mais cresce de forma importante.
- 🩺 **Prevenção de lesões:** o acompanhamento da saúde, liberação médica e mobilidade reduz riscos durante as aulas.
- 📚 **Aprendizado acadêmico:** aplicar conceitos de Engenharia de Requisitos e modelagem de sistemas em um cenário realista.
- 🎯 **Prática profissional:** desenvolver documentação clara, verificável e focada em acessibilidade e segurança.
- 🤝 **Trabalho em equipe:** discutir requisitos, prioridades e regras de negócio para um sistema com público específico.

### **WHO (QUEM?)**
**Quem está envolvido?**

**Integrantes do Grupo:**

- 👨‍💻 Pedro Henrique Silva Monteiro — [@phsmontheiro-glitch](https://github.com/phsmontheiro-glitch)
- 👨‍💻 Pedro Borges Prudente Machado — [@PedroBPMachado](https://github.com/PedroBPMachado)
- 👨‍💻 Yago Alves de Carvalho — [@yagoa853-del](https://github.com/yagoa853-del)
- 👨‍💻 Robson Otávio Queiroz Castro — [@robsonotavioqueirozcastroo343-pixel](https://github.com/robsonotavioqueirozcastroo343-pixel)
- 👨‍💻 Igor Jesus da Silva Tolentino — [@igorjesusdasilvatoletntino](https://github.com/igorjesusdasilvatoletntino)
- 👨‍💻 Luiz Daniel da Costa Bastos — [@luizdanieldacostabastosbastos-creator](https://github.com/luizdanieldacostabastosbastos-creator)

**Público-alvo do sistema:**

- 👴 Alunos idosos (60+)
- 👨‍👩‍👧 Familias/cuidadores
- 👨‍🏫 Professores
- 🩺 Profissional de saúde (fisioterapeuta)
- 👥 Funcionários da academia
- 🔐 Administradores

### **WHEN (QUANDO?)**
**Quando foi desenvolvido?**

- 📅 **Período:** Segundo semestre de 2026
- 📍 **Contexto:** Atividades da disciplina Análise e Projeto de Sistemas — UDF
- 📋 **Etapa atual:** Especificação dos requisitos funcionais, não funcionais, regras de negócio e casos de uso
- 🚀 **Próxima etapa:** Diagramas UML, refinamento de requisitos e documentação final

### **WHERE (ONDE?)**
**Onde o projeto está organizado?**

```text
📁 APS/
├── 📁 Unidade1/
│   ├── 📄 Atividade.md              (Ficha de requisitos)
│   └── 📄 README.md                 (Dinâmica de desenho)
├── 📁 Unidade2/
│   └── 📄 atividade.md              (Casos de uso)
├── 📁 ProjetoAPS/
│   ├── 📄 README.md                 (Visão geral do projeto)
│   ├── 📄 MoScow.md                 (Priorização de requisitos)
│   └── 📁 Documentacao/
│       ├── 📄 README.md             (Resumo da documentação)
│       ├── 📄 ficha-elicitacao-REQ-RF03.md
│       ├── 📄 ficha-elicitacao-REQ-RF10.md
│       └── 📄 [PDF a ser regenerado]
├── 📄 README.md                     (Este arquivo da disciplina)
└── 📄 LICENSE
```

---

## 📊 Estrutura do Projeto

### **Unidade 1 - Levantamento de Requisitos**

Transformação do levantamento do sistema em **requisitos funcionais e não funcionais**, definindo prioridades, critérios de aceitação e exemplos de utilização para o público 60+.

#### Requisitos Funcionais (13 no total)

| ID | Funcionalidade | Prioridade |
|:--:|---|:---:|
| RF01 | Cadastrar aluno | 🔴 Alta |
| RF02 | Consultar planos | 🟡 Média |
| RF03 | Reservar aula | 🔴 Alta |
| RF04 | Cancelar reserva | 🔴 Alta |
| RF05 | Cadastrar e editar aulas | 🔴 Alta |
| RF06 | Cadastrar e editar planos | 🟡 Média |
| RF07 | Consultar pagamentos | 🔴 Alta |
| RF08 | Consultar dados e reservas | 🟡 Média |
| RF09 | Registrar ficha de saúde | 🔴 Alta |
| RF10 | Registrar e validar liberação médica | 🔴 Alta |
| RF11 | Gerenciar contato de emergência | 🟡 Média |
| RF12 | Classificar aulas por nível de mobilidade | 🟡 Média |
| RF13 | Vincular familiar ou cuidador | 🟢 Baixa |

#### Requisitos Não Funcionais (7 no total)

| ID | Característica | Prioridade |
|:--:|---|:---:|
| RNF01 | Segurança (dados sensíveis e acesso restrito) | 🔴 Alta |
| RNF02 | Desempenho (respostas em até 3s) | 🟡 Média |
| RNF03 | Usabilidade (linguagem simples e orientações claras) | 🔴 Alta |
| RNF04 | Disponibilidade | 🔴 Alta |
| RNF05 | Acessibilidade | 🔴 Alta |
| RNF06 | Confiabilidade (impedir reserva sem vagas) | 🔴 Alta |
| RNF07 | Compatibilidade com navegadores | 🟡 Média |

### **Unidade 2 - Casos de Uso**

A próxima etapa utiliza os requisitos definidos como base para identificar atores, casos de uso e interações do sistema.

---

## 🎨 Dinâmica do Desenho

Na Unidade 1, realizamos uma **dinâmica de prototipagem rápida** para explorar a interface proposta do sistema.

**Sistema proposto:** Longevo Fit: Academia 60+

**Funcionalidade:** Cadastro e reserva de aulas adaptadas para idosos.

### Elementos da tela

- Nome do aluno e idade
- Foto ou avatar opcional
- Condição de saúde ou restrição de mobilidade
- Aulas compatíveis com o nível do aluno
- Botão para reservar e confirmar
- Contato de emergência

Cada aluno criou uma solução diferente para representar como a interface poderia facilitar o uso por pessoas com 60 anos ou mais.

---

## 📚 Conceitos Aplicados

### Engenharia de Requisitos

- ✅ Elicitação de requisitos
- ✅ Análise e organização de requisitos
- ✅ Documentação estruturada
- ✅ Definição de prioridades
- ✅ Critérios de aceitação
- ✅ Exemplos de utilização
- ✅ Requisitos funcionais e não funcionais

### Qualidade de Requisitos

Um bom requisito deve ser:

- **Claro** — sem ambiguidades e de fácil compreensão
- **Específico** — com informações precisas sobre o comportamento esperado
- **Verificável** — com critérios que permitam confirmar se foi atendido
- **Relevante** — alinhado aos objetivos e necessidades do sistema

---

## 🔍 Como Usar Este Repositório

### Para estudantes

1. 📖 Leia a ficha de requisitos.
2. 📝 Utilize os requisitos documentados como base para compreender a evolução do projeto.
3. 🔄 Acompanhe a Unidade 2 para consultar a especificação dos casos de uso.
4. 🧠 Releia o contexto do público 60+ para validar acessibilidade, saúde e segurança.

### Para professores e avaliadores

- Verifique a completude e organização dos requisitos
- Valide as prioridades definidas pelo grupo
- Analise os critérios de aceitação
- Verifique a clareza e verificabilidade dos requisitos
- Acompanhe a evolução dos requisitos para os casos de uso e diagramas UML

---

## 📖 Próximas Etapas

- 🔄 **Especificação de Casos de Uso** (Unidade 2)
- 🎨 **Diagramas UML** (casos de uso, classes, atividades, sequência e objetos)
- 💾 **Design do Banco de Dados**
- 🧪 **Validação de requisitos**
- 🖥️ **Implementação do Sistema**

---

## 📞 Contato e Contribuições

Este repositório foi desenvolvido pelos estudantes da **UDF — Centro Universitário**, para a disciplina de **Análise e Projeto de Sistemas**.

Para dúvidas, sugestões ou contribuições relacionadas ao projeto, entre em contato com os integrantes do grupo.

---

## 📄 Licença

Projeto desenvolvido para fins educacionais, como atividade da disciplina de **Análise e Projeto de Sistemas (APS)** da **UDF — Centro Universitário**.

---

**Última atualização:** 2026  
**Versão:** 2.0
