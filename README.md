# Painel de Estudos

Aplicação web para organizar atividades de estudo, acompanhar o progresso e visualizar os próximos prazos.

## Como usar

Abra `index.html` em um navegador atualizado. Não há instalação nem dependências externas.

1. Cadastre o título da atividade, a matéria e uma data de entrega opcional.
2. Use os filtros para pesquisar atividades ou consultar pendências e conclusões.
3. Edite, conclua ou exclua atividades pelos botões de cada cartão.
4. Use **Exportar dados** para baixar uma cópia em JSON.

## Funcionalidades

- Cadastro, edição, conclusão e exclusão de atividades.
- Pesquisa por título ou matéria e filtro por situação.
- Ordenação por prazo, com atividades sem prazo ao final.
- Indicadores de total, pendências, conclusões e progresso.
- Armazenamento local e exportação em JSON.
- Interface responsiva, campos identificados e mensagens de estado.

## Tecnologias

HTML, CSS e JavaScript sem bibliotecas externas.

## Organização

O arquivo `index.html` contém a interface, os estilos e a lógica. Os registros possuem identificador, título, matéria, prazo e situação. A interface é reconstruída a partir do estado salvo, e o conteúdo digitado é inserido com `textContent`.

## Limitações

Os dados ficam apenas neste navegador; não há conta, servidor ou sincronização. Em navegação privada ou com armazenamento bloqueado, os registros podem durar apenas a sessão. O JSON exportado é uma cópia para consulta; esta versão não oferece importação. Evite inserir informações sensíveis.

## Verificação manual

Teste cadastro, edição, conclusão, filtros e exclusão. Recarregue a página para conferir a persistência. Confira a exportação e o uso por teclado e em uma tela estreita.

## Contexto

Projeto de estudo preparado com assistência de IA. Não representa experiência profissional.

## Validação realizada

Verificado em navegador local: cadastro, edição, conclusão e reabertura, exclusão, prazo vencido, filtros, recarga com persistência, exportação JSON e ausência de rolagem horizontal em tela de 390 pixels. Não foram observados erros de execução nesses cenários.
