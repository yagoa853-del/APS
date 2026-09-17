# Sistema de Gestão para Academias de Musculação — Documentação APS

Documento produzido para a disciplina de Análise e Projeto de Sistemas (APS) — UDF,
2026.2. Arquivo final: `Projeto_APS_Sistema_Academia_UDF.docx`.

## Conteúdo do documento

1. Introdução
2. Justificativa
3. Objetivos (geral e específicos)
4. Descrição do sistema proposto
5. Requisitos e regras de negócio
   - 5.1 Requisitos Funcionais (RF01–RF08)
   - 5.2 Requisitos Não Funcionais (RNF01–RNF04)
   - 5.3 Regras de Negócio (RN01–RN04)
6. Diagramas UML (resumo teórico + imagem de cada um)
   - 6.1 Casos de Uso — 8 casos de uso (UC01–UC08), com atores Aluno,
     Professor, Funcionário e Administrador, e tabela de descrição de cada UC
   - 6.2 Classes — Usuario (base) com herança para Aluno e Funcionario,
     associada a Plano, Reserva, Aula e Pagamento
   - 6.3 Atividades — fluxo do processo "Reservar Aula", incluindo as
     verificações da RN04 (pagamento) e RN02 (vagas)
   - 6.4 Sequência — fluxo "Cancelar Reserva" entre Aluno, Frontend, Backend
     e Banco de Dados, com bloco `alt` para os dois cenários da RN03
   - 6.5 Objetos — instância de exemplo (aluna vinculada a um plano Anual,
     com reserva confirmada em uma aula de Spinning)
7. Conclusão
8. Referências

## Formatação

- Fonte: Arial em todo o documento.
- Capa com o brasão da UDF, curso, disciplina, equipe (6 integrantes com RGM),
  orientadora e data.
- Sumário com numeração de página sincronizada com o conteúdo final.
- Tabelas padronizadas para RF, RNF e para cada caso de uso.

## Premissas assumidas na modelagem dos diagramas

Como o documento original não trazia os diagramas prontos, alguns pontos
foram definidos para tornar a modelagem completa e coerente com o texto:

- O ator **Professor** (citado na Seção 4 como um dos 4 perfis do sistema)
  foi associado, no Diagrama de Casos de Uso, a UC02 (Consultar Planos) e
  UC08 (Consultar Dados e Reservas), já que os Requisitos Funcionais listados
  não detalham uma função exclusiva desse perfil.
- Os dados do Diagrama de Objetos (nome da aluna, instrutor, modalidade,
  valores) são fictícios, apenas para ilustrar uma instância válida do
  modelo de classes.
- Atributos e métodos das classes (ex.: `Usuario`, `Aluno`, `Plano`) foram
  inferidos a partir dos RFs/RNs, podendo ser refinados pela equipe conforme
  o modelo de dados definitivo.

## Possíveis ajustes futuros

- Substituir os dados fictícios do Diagrama de Objetos por um cenário real
  de testes, se desejado.
- Revisar a associação do ator Professor caso a equipe defina um RF
  específico para esse perfil (ex.: consultar/gerenciar a própria agenda de
  aulas).
- Ajustar cores/estilo visual dos diagramas, se a equipe preferir uma
  paleta diferente da usada (tons de azul, alinhados à identidade da UDF).
