# Layouts

O **layout** divide a tela da TV em **regiões**. Cada região vira uma trilha na [playlist](Playlists.md).

Acesse pelo menu **Conteúdos → Layouts** ou pelo botão ao lado do layout, no editor da playlist.

## Layouts prontos

| Layout | Regiões |
|---|---|
| **L padrão** | principal, lateral (cabeçalho, superior e inferior), rodapé e relógio |
| **Tela cheia** | só a principal |
| **Main + rodapé** | principal e rodapé |
| **Cheia + ticker** | principal com uma faixa de mensagens |
| **Retrato** | para TV na vertical (1080 × 1920) |
| **Main + lateral** | principal e lateral |

Os layouts prontos aparecem com a marca **sistema · clonado**. Ao salvar uma alteração num deles, é criada uma cópia; o original não muda.

## Criar ou editar um layout

1. No seletor ao lado do título, escolha um layout ou **Novo layout**.
2. Informe o **Nome**, a **Orientação** e a **Referência** (resolução, por exemplo 1920 × 1080).
3. Clique em **+ Região** para criar uma região, ou clique numa região do desenho para editá-la.
4. Nas propriedades da região:
   - **Nome**, **Chave** (não pode repetir) e **Papel** (principal, lateral, cabeçalho, rodapé, relógio...);
   - **Posição (%)**: esquerda, topo, largura e altura;
   - **Tipos permitidos**: os conteúdos que a região aceita;
   - **Duração padrão**, **Transição padrão** e **Obrigatória na playlist**;
   - **Aparência**: fundo, transparente, texto fixo e se recolhe quando o vídeo da principal vai para tela cheia;
   - **Moldura**: cor e espessura.
5. Clique em **Salvar**.

> Dica: a grade ajuda a encaixar as regiões. Abaixo da posição aparece o tamanho em pixels na resolução de referência.

## Regras

- O layout precisa de pelo menos uma região.
- Não é possível excluir um layout pronto nem um layout usado por alguma playlist.
- Ao trocar o layout de uma playlist, os itens das regiões com a mesma **Chave** são mantidos; os demais somem.

## Veja também

- [Playlists](Playlists.md)
