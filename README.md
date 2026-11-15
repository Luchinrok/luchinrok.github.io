# luchinrok.github.io (arrel compartida)

Aquí no hi viu cap app. Les apps són als seus repos:

| App | Adreça | Repo |
|---|---|---|
| Festuc | https://luchinrok.github.io/festuc/ | `Luchinrok/festuc` |
| Xala! | https://luchinrok.github.io/Xala/ | `Luchinrok/Xala` |
| 3Tocs | https://luchinrok.github.io/volei/ | `Luchinrok/volei` |

Què hi ha:

- `.well-known/assetlinks.json`: Digital Asset Links de les apps de Google Play (TWA). Només és vàlid servit des de l'arrel, per això és aquí. És una llista: **cada app hi afegeix la seva entrada** (`package_name` + empremta SHA-256) sense tocar les altres.
- `.nojekyll`: perquè GitHub Pages publiqui `.well-known/`.
- `index.html` i `privacitat.html`: redirigeixen a `/festuc/`. Festuc va viure a l'arrel del 03-11 al 15-11-2026 i hi ha gent que la té instal·lada aquí. No treure-les.
- **No posar-hi `manifest.json` ni cap app**: una PWA a l'arrel tindria `scope` sobre tot el domini i capturaria les altres apps.
