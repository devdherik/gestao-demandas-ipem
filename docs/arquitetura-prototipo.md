# Organização do protótipo

As telas ficam em `prototipo/`. O HTML contém a estrutura e os textos; os estilos ficam em `assets/css/kanban.css`.

Quando os filtros e a movimentação forem adicionados, o JavaScript será dividido entre dados de exemplo, regras e atualização da tela. Por enquanto, o quadro é estático e não precisa de dependências.

## Regras do quadro

Todos podem mover cartões. Apenas quem recebeu originalmente a demanda pode trocar o executor e concluir o atendimento. A delegação não transfere essa responsabilidade.

Demandas apenas para ciência são encerradas depois da confirmação de todos os destinatários. Quando houver checagem, ela será feita pela pessoa indicada.

No protótipo, essas regras servirão para validar o fluxo. Na aplicação, as permissões também precisarão ser conferidas no servidor.

## Próximas partes

- Cartões de exemplo e pesquisa por origem, responsável e situação.
- Detalhes da demanda, ciência e planejamento das tarefas.
- Movimentação, checagem e conclusão.

Os nomes das colunas ainda precisam ser alinhados com `requisitos.md`, que registra uma versão anterior do fluxo.

## Commits

Usar `tipo(escopo): descrição`, com mensagens em português. Exemplos: `feat(prototipo): adicionar filtro por origem` e `fix(prototipo): preservar filtros ao trocar de visualização`.
