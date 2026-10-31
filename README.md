# Site do Tibia 3D War

Página única e estática: `index.html` + `assets/`. Roda de graça no GitHub Pages.

## Publicar no GitHub Pages
2. Settings > Pages > Source: **Deploy from a branch**, branch `main`, pasta `/ (root)` > Save.
3. Em ~1 minuto o site fica em `https://guijusto90.github.io/tibia3dwar/`.

## Link de download
O cliente fica em `download/Tibia3DWar_Cliente.zip` e o botão aponta para ele.
Para uma versão nova, troque esse arquivo (mesmo nome) e envie.

## Números ao vivo
`STATUS_URL` em `index.html` aponta para um JSON do servidor do jogo
(`online`, `max`, `blue`, `red`, `kills_hoje`, `recorde`, `placar`, `kills_vocacao`).
Enquanto estiver vazio, a página mostra "—".
