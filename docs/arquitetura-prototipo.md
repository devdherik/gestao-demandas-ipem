# Organização do protótipo

O protótipo serve para validar o fluxo de demandas antes da implementação da aplicação.

## Separação de responsabilidades

- `prototipo/index.html`: estrutura semântica e conteúdo das telas.
- `prototipo/assets/css/kanban.css`: apresentação em baixa fidelidade e adaptação a diferentes larguras.
- JavaScript será introduzido quando houver comportamento a validar. Dados de exemplo, regras de movimentação e atualização da interface deverão ficar em módulos separados.

A abordagem é de melhoria progressiva: a estrutura visual deve ser compreensível sem JavaScript. Não há necessidade de framework, MVC ou padrões de criação de objetos nesta etapa. A separação entre apresentação, regras e dados evita concentrar toda a aplicação em um HTML.

## Regras que orientarão as próximas etapas

Todos podem mover cartões. Somente o destinatário original altera o executor da demanda e conclui demandas com providências. Demandas apenas para ciência encerram após todas as confirmações. Uma pessoa indicada realiza a checagem.

A estrutura visual não representa controle de acesso. As regras serão demonstradas posteriormente e, na aplicação real, deverão ser verificadas também no servidor.

## Evolução

1. Estrutura visual do quadro e filtros identificados como indisponíveis.
2. Cartões de exemplo e filtros funcionais.
3. Detalhes, ciência e planejamento de tarefas.
4. Movimentação, checagem e conclusão com validação das regras.

Cada etapa deve produzir uma mudança revisável. Commits usam `tipo(escopo): descrição` em português, com `docs`, `feat`, `fix` ou `refactor`, conforme o conteúdo. Não são necessários commits vazios ou intervalos artificiais.

As colunas seguem a proposta mais recente do protótipo. A documentação anterior possui nomes diferentes; a padronização deverá ser validada antes da implementação definitiva.
