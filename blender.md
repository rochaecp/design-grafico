# Blender

## Atalhos

~~~markdown
- numpad 2, 4, 6, 8              === rotaciona a cena
- ctrl + numpad 2, 4, 6, 8       === pam
- alt + click + movMouse         === rotaciona a cena
- shift + alt + click + movMouse === pam

- numpad 7          === vista topo z
- ctrl + numpad 7   === vista topo -z
- numpad + 3        === vista topo x
- ctrl + numpad + 3 === vista topo -x
- numpad 1          === vista topo -y
- ctrl + numpad 1   === vista topo y

- home     === frame all (view -> Frame all)
- numpad . === frame selected (view -> Frame selected)
- numpad + === zoom in
- numpad - === zoom out

- selecObjt + tab === edit mode
- 1               === edit mode - opção ponto
- 2               === edit mode - opção linha
- 3               === edit mode - opção face

- selecObjt + shift + selecObjt === selecionar diversos objetos
~~~

## Menus e Janelas

- Splash screen: Tela de abertura
- Objetos iniciais: câmera (visualização da cena), cubo e ponto de luz (para quando renderizar)
- Render: opções para renderizar
  - Render Image: ver imagem da renderização
- Workspace: maneira como os painéis estão organizados
- Layout, Modeling, Scupting, ... são diferentes configurações de workspace
  - Shading: materiais e texturas

- Orientação básica:
  - câmera na esquerda e luz na direita.
  - eixo z azul aponta para o céu.

## Algumas configurações

- Blender Preferences -> Navigation -> marque a opção "Zoom to Mouse Position"
- Blender Preferences -> Input -> marque "emulate 3 button modifie"
- Blender Preferences -> keymap -> preferences -> marque select mouse left button


## Algumas etapas interessantes

- Modelagem
- Iluminação
- Animação
- Materiais e Texturas
- Renderização

## Algumas técnicas

- Ray Tracing

## How to

### Criar uma caneca

- apague o cubo, a camera e a fonte de luz
- crie um cilindro: add -> mesh -> cylinder
- opções add cylinder (canto esq inferior): vértices: 10, radius: 1m, deph: 3m
- menu overlay (canto dir sup): ativar wireframe (linhas de construção)
- entrar nas opções de edição: seleciona objeto + TAB ou menu object mode (canto sup esq) -> edit mode
- ao lado de "edit mode" há 3 opções: pontos, linhas, faces -> clique em faces usando a ferramenta de seleção ou pressione 3
- selecione o topo do cilindro, bt dir mouse -> opcao: inset faces
- selecione o topo do cilindro (parte interna), bt dir mouse -> opcao: extrude faces
- criar linhas de corte: ferramenta de Loop cut -> criar 4 linhas de corte, ferramenta de selecao e clica fora
- seleciona 2 quadrados da lateral -> btdir -> inset faces, btdir -> extrude
- seleciona 2 pontos da alça, diminui distancia - gera "planos inclinados"
- seleciona 2 planos inclinados, btdir -> bridge faces (number of cuts = 1)
- seleciona linha do meio da alça, select -> select loops -> edge loops, mover para diminuir abertura alça.



- parei em 12m


## Links - youtube - basicos

- [Heber Simeoni - tutorial basico](https://www.youtube.com/playlist?list=PLUSWmql_M1POs-yWCdLV5_iNCti1QyE-S)
- [Heber Simeoni - algumas aulas free do curso](https://hebersimeoni.com.br/curso/curso-de-blender/)
- [game life - tutorial basico](https://www.youtube.com/playlist?list=PLZ71A6T_ZR1yzhwhlm6UO5o0uzwLOVWe7)
- [Daniel franco - v2.8](https://www.youtube.com/playlist?list=PLrYLf1JihKtb5pbeR6fX1bMoREsjJn0Q_)
- [Daniel franco - v2.9](https://www.youtube.com/playlist?list=PLrYLf1JihKtZH4RWWncxrygt7UUOTwqgV)
- [Augusto cezar - blender basico](https://www.youtube.com/playlist?list=PL-YgB1cUwWX3JWUeHtvQ2GPrm81XOYnox)
- [Cria jogo - intro a blender 2.8](https://www.youtube.com/playlist?list=PLqYboeh3Jru4axGriJFruUI6ulY5s0sUn)
- [Welington Coloni](https://www.youtube.com/playlist?list=PLuGCQAHfIDDuT9G1nPhYgD1sj0_skDB6_)
- [Revolution - tutorial basico](https://www.youtube.com/playlist?list=PLJASh3gCRKY81hdBzBos9xlsHaTb9FnTG)
- [InsightZ - basico](https://www.youtube.com/playlist?list=PL6sK7EftTdDLxIa_6ILKtNY97o4a4pKb7)
- [prx 3d - tutorial basico](https://www.youtube.com/playlist?list=PLaMfHWsVa-bMdaGVQkIAwwa8I95Y01auI)

## Links - youtube - intermediario

- [Uniday studio - UPBGE - jogo](https://www.youtube.com/playlist?list=PLkei3LlusC-Er6A8uW4H5h5iswDMvZutf)
- [Uniday studio - jogo no blender - antigo](https://www.youtube.com/playlist?list=PLkei3LlusC-Gdszmg9TPmd0gSYxMSI4vT)
- [game life - raposa low poly](https://www.youtube.com/watch?v=rAa95ph_zm4&list=PLZ71A6T_ZR1zeXX9CU_2uRuqY1YFLTWsv)
- [Tiago Lourenço - modelando uma cabeça](https://www.youtube.com/playlist?list=PLKsf4kEilureYInxYoIfIWnPfwOTlR8Ud)

## Links oficiais

- [Manual - site oficial - v2.93](https://docs.blender.org/manual/en/2.93/)
- [Tutoriais - site oficial - en](https://www.blender.org/support/tutorials/)
- [Youtube - oficial blender - en](https://www.youtube.com/playlist?list=PLa1F2ddGya_-UvuAqHAksYnB0qL9yWDO6)

## Continua

parei em 2
https://www.youtube.com/playlist?list=PLUSWmql_M1POs-yWCdLV5_iNCti1QyE-S
