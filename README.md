<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-escuro.svg" />
  <img src="assets/logo-claro.svg" width="360" alt="MaduTasks" />
</picture>

**Site de apresentação do MaduTasks, a agenda de estudos que nasceu de uma promessa.**

### 🌐 [otaviofelix-in.github.io/Madu-Tasks-Site](https://otaviofelix-in.github.io/Madu-Tasks-Site/)

</div>

---

## Links

| | |
|---|---|
| Site no ar | https://otaviofelix-in.github.io/Madu-Tasks-Site/ |
| App (código) | https://github.com/OtavioFelix-in/Madu-Tasks |
| Baixar o APK | https://github.com/OtavioFelix-in/Madu-Tasks-Site/releases/latest/download/MaduTasks.apk |

## Como funciona

Site estático, sem build: só `index.html`, `style.css` e a pasta `assets/`.

- **Publicação:** GitHub Pages, a partir da branch `main` (pasta raiz). Todo push na `main` atualiza o site em cerca de 1 minuto.
- **Testar localmente:** abrir o `index.html` no navegador.
- **Tema claro/escuro:** segue o sistema, e o botão no topo alterna (a escolha fica salva no navegador).
- **Cores:** as mesmas do app (`madu-tasks/src/theme.js`), definidas no topo do `style.css`.

## Estrutura

```
├── index.html              # página única
├── style.css               # cores, layout e animações
├── MaduTasks-promo.mp4     # vídeo de apresentação (seção "Vídeo")
└── assets/
    ├── logo-claro.svg      # logo horizontal, tema claro
    ├── logo-escuro.svg     # logo horizontal, tema escuro
    ├── logo-animada.mp4    # ícone animado da seção "Baixar"
    ├── video-capa.jpg      # capa do vídeo antes do play
    ├── icon.png, favicon.png
    ├── telas/              # prints do app
    └── *.ttf               # fontes Inter e ícones Feather
```

## Vídeo do YouTube

O site toca o `MaduTasks-promo.mp4` local. Para usar o vídeo do YouTube, cole o ID no topo do `<script>` do `index.html`:

```js
var YOUTUBE_ID = 'D5vo4k-0MrI'; // o que vem depois de "watch?v=" ou "shorts/"
var VIDEO_VERTICAL = true;      // false se o vídeo for horizontal (16:9)
```

---

<div align="center">Feito por Otávio Felix para a Madu.</div>
