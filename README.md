# Pac-Man

Jogo de labirinto para navegador, com visual arcade responsivo, controles por teclado e toque, pontuação, vidas, fases, fantasmas, power pellets e ranking local.

## Jogar localmente
Abra `index.html` em um navegador moderno. Não há dependências nem etapa de build.

## Controles
- Setas ou WASD: movimentar
- Espaço: pausar/retomar
- Enter: iniciar

## Publicar no GitHub Pages
O workflow em `.github/workflows/pages.yml` publica automaticamente o conteúdo do repositório quando há push na branch `main`.
No GitHub, abra **Settings → Pages** e selecione **GitHub Actions** como fonte de publicação. Depois acompanhe a execução em **Actions**.

## Ranking
Os cinco melhores resultados são armazenados em `localStorage` no navegador de cada jogador. O ranking não é compartilhado entre dispositivos.

## Versão desktop
Esta edição web é independente da versão desktop Java/SQLite. O GitHub Pages hospeda arquivos estáticos e não executa aplicações Java Swing ou servidores.
