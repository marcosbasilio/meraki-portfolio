# Estado atual — Meraki Sites

Última verificação: 18/10/2026. Este documento descreve o que foi observado nessa data; confirme novamente os itens externos antes de agir.

## Projeto e estrutura

- Repositório público: `marcosbasilio/meraki-portfolio`; branch principal: `main`.
- Site estático de portfólio. `index.html` reúne HTML, CSS e JavaScript; `favicon.svg` e `assets/` guardam recursos visuais.
- Não há backend, banco de dados, instalação de dependências ou suíte de testes automatizados neste repositório.
- A direção visual usa violeta, verde-lima, fundo escuro e composição editorial. Preserve essa identidade ao alterar a interface.
- O menu móvel, a janela de contato e a cópia de uma mensagem-base são comportamentos locais no navegador. A janela de contato não envia formulários nem armazena dados.
- Há recursos externos: fontes do Google e uma incorporação visual do site Tiago Machado Advocacia. A disponibilidade deles depende dos respectivos serviços.

## Conteúdo e limites

- Os cartões identificam projetos publicados e prévias locais. Jardim Secreto e Área de Membros são prévias locais, sem link para uma publicação de produção.
- A Área de Membros é representada neste repositório por arte em CSS, sem captura de telas ou dados de alunos.
- Este repositório não contém o sistema privado de área de membros, credenciais, banco de dados, cadastros ou dados de clientes.
- Não transforme uma prévia local em projeto publicado nem acrescente afirmações sobre clientes, funcionalidades ou resultados sem confirmação de Marcos.

## Publicação e colaboração

- Em 18/10/2026, `https://sitesmeraki.com/` respondeu HTTP 200 com o título do Meraki, mas o HTML publicado **não continha o cartão recente da Área de Membros** presente na branch `main` do GitHub. Portanto, o estado de produção difere do repositório.
- Não há configuração de implantação para esse domínio neste repositório. Não presuma que enviar código ao GitHub atualize o site publicado.
- A conta GitHub `Mateus0096` tinha permissão de escrita confirmada em 18/10/2026. Confirme o acesso novamente caso isso seja importante para uma ação futura.

## Próximas verificações

1. Confirmar com Marcos qual é o fluxo de publicação de `sitesmeraki.com` e qual checkout deve ser a fonte principal de trabalho em equipe.
2. Antes de publicar, comparar a branch `main` com o site no ar e obter autorização para qualquer alteração de produção.
3. Depois de cada alteração, testar menu, janela de contato, links, imagens, responsividade e referências a projetos locais; registrar o resultado em `CHANGELOG.md`.

Ao concluir qualquer trabalho, atualize este arquivo se algum item acima mudar. Registre o que foi alterado, verificado e o que ainda está pendente no histórico.
