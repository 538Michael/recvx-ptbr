# Resident Evil Code: Veronica X em português do Brasil

Pacote de idioma feito por fãs para o [recvx-enhanced-port](https://github.com/aikatore/recvx-enhanced-port),
o port para PC do Resident Evil Code: Veronica X (PS2). Traduz o texto do jogo (mensagens, nomes e
descrições de itens, arquivos e documentos, telas de salvar e carregar, computadores) e as imagens com
texto: menu título, opções, inventário, status, mapa, telas de história, "VOCÊ MORREU", placas, a
seleção de personagem do Modo Combate (Battle Game).

> Resident Evil e todo o seu texto © Capcom. Projeto de fãs, sem fins lucrativos e sem ligação com a
> Capcom; você precisa do seu próprio disco americano do jogo (SLUS-20184). Será removido a pedido.

## Requisitos

- O port com suporte a idiomas do jogo (opção **Game language**): o build
  [recvx-enhanced-port 0.8.0](https://github.com/538Michael/recvx-enhanced-port/releases/tag/v0.8.0)
  (0.6.10 com legendas e idiomas do jogo).
- Seu próprio disco americano (SLUS-20184).
- Para legendas em português nos filmes e cenas: o pacote
  [recvx-subtitles](https://github.com/538Michael/recvx-subtitles) (`pt-BR`).

## Instalação

1. Baixe `recvx-ptbr-1.0.0.zip` em [releases](https://github.com/538Michael/recvx-ptbr/releases) e
   descompacte na pasta do jogo (onde fica o `recvx.exe`): ele cria `mods/lang/pt-BR/`.
2. Abra OPTION -> ENHANCED SETTINGS -> DISPLAY -> **Game language** e escolha
   **Portugues (Brasil)**. Com as legendas instaladas, o idioma das legendas muda junto.
3. Reinicie o jogo.

As letras acentuadas são desenhadas pelo próprio jogo a partir da fonte do seu disco; deixe
**Native textures** ligado (padrão).

## Conteúdo

| Pasta | O quê |
|---|---|
| `mods/lang/pt-BR/game.json` | o texto do jogo em português |
| `mods/lang/pt-BR/textures/` | as imagens com texto, em português (resolução original do PS2; têm prioridade sobre pacotes HD) |
| `mods/lang/pt-BR/map.json` | os nomes das áreas vizinhas nos mapas (Ponte de Ferro, Passagem, Ponte) |

Os menus do próprio port (ENHANCED SETTINGS, multiplayer, janelas F1/F2/F3) continuam em inglês.

---

**English:** a fan-made Brazilian Portuguese language pack for recvx-enhanced-port. Needs the port
build [0.8.0](https://github.com/538Michael/recvx-enhanced-port/releases/tag/v0.8.0) (game language
support) and your own US disc (SLUS-20184). Unzip `recvx-ptbr-1.0.0.zip` into the game folder (it
creates `mods/lang/pt-BR/`), pick DISPLAY -> Game language -> Portugues (Brasil), and restart. Resident Evil and its text © Capcom; unofficial; will be removed on
request.
