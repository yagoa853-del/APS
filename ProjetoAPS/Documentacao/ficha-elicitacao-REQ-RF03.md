# Longevo Fit: Academia 60+ — Documentação APS

Documento produzido para a disciplina de **Análise e Projeto de Sistemas (APS)** — UDF, 2026.2.

> Observação: o arquivo `.docx` e as imagens dos diagramas precisam ser regenerados para refletir a nova identidade do sistema.

## Conteúdo do documento

1. Introdução
2. Justificativa
3. Objetivos (geral e específicos)
4. Descrição do sistema proposto
5. Requisitos e regras de negócio
   - 5.1 Requisitos Funcionais (RF01–RF13)
   - 5.2 Requisitos Não Funcionais (RNF01–RNF07)
   - 5.3 Regras de Negócio (RN01–RN09)
6. Diagramas UML
   - 6.1 Casos de Uso — 13 casos de uso (UC01–UC13), com atores Aluno, Familiar/Cuidador, Professor, Profissional de Saúde, Funcionário e Administrador
   - 6.2 Classes — Aluno, Familiar, FichaSaude, LiberacaoMedica, ContatoEmergencia, Aula, Plano, Reserva, Pagamento e Funcionario
   - 6.3 Atividades — fluxo do processo "Reservar Aula", incluindo validação da liberação médica e compatibilidade de mobilidade
   - 6.4 Sequência — fluxo "Registrar e validar liberação médica" entre Funcionário, Sistema e Banco de Dados
   - 6.5 Objetos — instância de exemplo com aluna idosa, ficha de saúde, liberação médica e reserva em aula adequada
7. Conclusão
8. Referências

## Formatação

- Fonte: Arial em todo o documento.
- Capa com o brasão da UDF, curso, disciplina, equipe, orientadora e data.
- Sumário com numeração de página sincronizada com o conteúdo final.
- Tabelas padronizadas para RF, RNF, RN e para cada caso de uso.

## Premissas assumidas na modelagem dos diagramas

- O ator **Professor** foi considerado relevante para consulta do contato de emergência durante a aula e acompanhamento do aluno.
- O ator **Familiar/Cuidador** foi incluído para consulta de reservas e pagamentos, nunca de dados de saúde.
- O ator **Profissional de Saúde** foi incluído para registrar e atualizar a ficha de saúde e orientar o nível de mobilidade do aluno.
- O atributo **nivelMobilidade** foi associado a **Aluno** e **Aula** para validar a compatibilidade antes da reserva.
- O atributo **dataUltimaAtualizacao** foi incluído na **FichaSaude** para garantir rastreabilidade da informação.
- O diagrama de objetos usa uma aluna idosa como exemplo, sem dados reais e sem nomes de pessoas reais.

## Possíveis ajustes futuros

- Regenerar o documento `.docx` para refletir o novo nome e contexto do sistema.
- Atualizar imagens dos diagramas UML com a nova identidade visual.
- Validar os diagramas com a entrevista real do público 60+, quando disponível.
- Revisar a estrutura de classes para refletir regras de negócio e permissões definidas no MoSCoW.
