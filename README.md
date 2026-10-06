# creazionidinamiche — landing "in costruzione"

Pagina statica temporanea per **creazionidinamiche.it**.

- `index.html` — pagina unica (HTML, CSS e JS inline, nessuna dipendenza da build)
- `favicon.svg` — il simbolo su fondo blu notte

## Animazioni
1. **La pennellata**: il simbolo (C e D fuse in un unico gesto) viene dipinto con una maschera
   che segue la linea centrale del tratto (`stroke-dashoffset`).
2. **Il nome in divenire**: le vocali entrano ed escono a cascata, alternando
   `crzndnmch` → `creazionidinamiche` → `crzndnmch`, all'infinito.

Chi ha attivato "riduci movimento" nel sistema vede la versione statica con il nome per esteso.

## Palette
| Ruolo | Colore |
|---|---|
| Sfondo | `#0d1d36` |
| Simbolo, "dinamiche" | `#a9bdcb` |
| "creazioni", testi secondari | `#7c95a7` |

Font: Space Grotesk (Google Fonts).

## Deploy
È un sito statico: si pubblica così com'è su Vercel, Netlify o GitHub Pages, senza build.
