# Playlists

A **playlist** diz o que a TV mostra. O **layout** divide a tela em regiões (principal, lateral, rodapé, relógio...) e cada região tem uma **trilha** com os itens que passam em sequência: tabela de preços, ofertas, imagens, vídeos, mensagens, encartes do Studio, senha em fila e outros.

A playlist só chega às TVs depois de **publicada** e de entrar na [Programação](Programacao.md).

Acesse pelo menu **Conteúdos → Playlist**.

## Visão geral da tela

- **Filtros**: status (por padrão as arquivadas ficam escondidas), layout e tag.
- **Visualizações**: alterne entre **cartões** e **tabela** nos botões ao lado de **Nova playlist**.
- **Cartão**: mostra o desenho do layout, o status, a versão, quantas telas (itens) e quantas programações a playlist tem, e se há **rascunho pendente**.
- **Páginas**: a lista mostra 12 playlists por vez. Use o seletor no fim da página para ver as demais.

## Criar uma playlist

1. Clique em **Nova playlist**.
2. Troque o nome em **Nome da playlist** (obrigatório).
3. Na barra de configurações:
   - **Layout**: cada região do layout vira uma trilha. O botão ao lado abre o [editor de layouts](Layouts.md);
   - **Áudio de fundo**: origem, volume e se abaixa durante os vídeos;
   - **Padrões**: duração, transição e ajuste da imagem usados pelos itens;
   - **Tags**: servem de filtro na lista de playlists.
4. Clique numa região do desenho (ou na trilha) para escolhê-la e adicione um item em **Conteúdo disponível**. Só ficam habilitados os tipos que aquela região aceita. O item entra no fim da trilha.
5. Clique no item para ajustar as [propriedades](#propriedades-do-item).
6. Use as setas para mudar a ordem e a lixeira para remover.
7. Clique em **Salvar**. A playlist fica como **rascunho**: as TVs ainda não veem.
8. Clique em **Publicar → Publicar agora** para enviar a versão às TVs.

> Dica: **Pré-visualizar** mostra a playlist tocando numa data e hora à sua escolha e explica por que um item não tocaria naquele momento.

## Conteúdo disponível

| Grupo | Itens |
|---|---|
| Produtos | Tabela de preços, Ofertas, Ofertas em grade, Consulta de preço |
| Mídias | Imagem, Vídeo, Áudio |
| Mensagens | Mensagem |
| Widgets | Relógio, Clima, RSS, Página web, Senha em fila |
| Studio | Projeto do Studio |
| Encarte | Encarte |
| Playlists | outra playlist dentro desta |

Cada região aceita alguns tipos. Por exemplo, o rodapé aceita mensagens e RSS, e o relógio só aceita o relógio. Se um item ficar numa região que não o aceita (por exemplo, depois de trocar o layout), a linha dele mostra um aviso.

## Propriedades do item

Ao clicar num item da trilha, o painel de propriedades mostra quatro abas:

| Aba | O que ajusta |
|---|---|
| **Conteúdo** | o que o item mostra. Nos produtos: **Origem** (*Dinâmica*, filtrada pelos campos abaixo, ou *Fixa*, escolhendo os itens), **Departamento**, **Flag de tela**, **Somente em oferta**, **Somente com imagem**, **Ordenação** e **Máximo de produtos**. Em **Template**: modelo, estilo, colunas e linhas por página |
| **Exibição** | **Duração** (*Fixa*, *Duração da mídia*, *Página por página* ou *Até o evento*), segundos, **Páginas por passagem**, **Transição**, **Com áudio** e **Tela cheia** |
| **Validade** | **Início** e **Fim** (datas), **Dias da semana** e **Janelas de horário**: fora delas o item não toca |
| **Avançado** | público: **Lojas**, **Departamentos** e **Tags** em que o item aparece |

> Dica: vídeo com duração *Fixa* pode ser cortado antes do fim. Use *Duração da mídia*.

### Conteúdos do Studio

- **Projeto do Studio**: em **Layout do Studio** escolha um layout de TV ou de encarte (ou deixe *Layout padrão*).
- **Encarte**: escolha o conjunto de encarte.

Na TV o layout é preenchido com os produtos da loja, conforme os filtros da aba **Conteúdo**.

### Senha em fila

Mostra a senha atual em destaque e as 3 últimas chamadas. Veja [Senha em fila](Senha-Fila.md).

## Editar uma playlist

1. Clique em **Editar** no cartão (ou na linha da tabela).
2. Faça as alterações e clique em **Salvar**. Se a playlist já estava publicada, a alteração vira um **rascunho pendente**: as TVs continuam com a versão publicada.
3. Clique em **Publicar → Publicar agora**. Antes, use **Ver diferenças com a versão anterior** para conferir o que muda.

## Outras ações

No menu **...** do cartão (ou nos botões da tabela):

| Ação | O que faz |
|---|---|
| **Duplicar** | cria uma cópia como rascunho, com o nome "(cópia)", e abre o editor |
| **Programar** | abre a [Programação](Programacao.md) |
| **Versões** | mostra o rascunho atual, a versão publicada e a criação |
| **Arquivar** | tira a playlist da lista, da programação e das TVs. Para trazer de volta, filtre o status *Arquivada* e use **Restaurar** |
| **Excluir** | apaga a playlist. Não é possível excluir uma playlist que está na programação |

## Perguntas frequentes

**Salvei, mas a TV não mudou.** Salvar só grava o rascunho. Clique em **Publicar → Publicar agora**.

**A playlist não aparece na TV.** Confira se ela está publicada, se não está arquivada e se existe uma entrada para ela na [Programação](Programacao.md) daquela TV, loja ou departamento.

**Um item não aparece na TV.** Veja a aba **Validade** (datas, dias e horários) e a aba **Avançado** (lojas e departamentos) do item. A **Pré-visualizar** mostra o motivo.

**Não consigo excluir a playlist.** Ela está em alguma entrada da programação. Remova as entradas ou arquive a playlist.

## Veja também

- [Programação](Programacao.md)
- [Layouts](Layouts.md)
- [Reprodução](Reproducao.md)
