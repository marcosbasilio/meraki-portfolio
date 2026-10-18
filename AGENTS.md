# Orientações para pessoas e assistentes de IA

Este arquivo se aplica a todo o repositório. Antes de modificar qualquer coisa, leia `README.md`, `PROJECT_STATUS.md` e `CHANGELOG.md`, examine `git status` e confira o código atual. Não trate notas antigas como prova de que um serviço externo continua no mesmo estado.

## A cada alteração

1. Preserve mudanças preexistentes e limite a edição ao pedido recebido.
2. Acrescente uma entrada datada a `CHANGELOG.md` com autor, arquivos ou comportamento alterado, verificações realmente feitas e pendências. Não declare um teste ou uma publicação que não ocorreu.
3. Atualize `PROJECT_STATUS.md` quando mudarem arquitetura, conteúdo, recursos externos, estado de produção, colaboradores, riscos ou próximos passos.
4. Revise `git diff --check`, referências de imagens e links locais, além das interações afetadas. Faça inspeção visual em desktop e celular quando houver mudança de interface.
5. Só depois registre e envie o código. O histórico do Git complementa, mas não substitui, o registro acima.

## Limites de segurança e publicação

- Nunca publique `.env`, credenciais, tokens, chaves, banco de dados, informações de alunos, contatos de clientes ou arquivos de produção privados.
- Mantenha clara a distinção entre projeto publicado e prévia local. Não invente funcionalidades, depoimentos, números ou resultados.
- Não use rótulos que apresentem os projetos como peças descartáveis nos nomes ou textos públicos; descreva com precisão o escopo real.
- Enviar alterações ao GitHub não equivale a publicar em `sitesmeraki.com`. Confirme destino, autorização e resultado antes de declarar uma implantação concluída.
- Se trabalhar com outra IA, forneça a ela estes três documentos e peça que os atualize ao terminar. Quando houver dúvida factual, registre a dúvida como pendência em vez de preencher por suposição.
