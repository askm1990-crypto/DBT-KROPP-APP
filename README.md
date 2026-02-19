# DBT – Hva forteller kroppen din?

En liten statisk web-app (én HTML-fil) for kroppsscan + forslag til emosjoner og DBT-ferdigheter.

## Kjør lokalt

### Alternativ A: Åpne direkte
Åpne `index.html` i nettleseren.

### Alternativ B: Lokal server (anbefalt)
Med Node:

```bash
npm install
npm run dev
```

eller med Python:

```bash
python -m http.server 5173
```

Gå til: http://localhost:5173

## Deploy (GitHub Pages)
1. Push repoet til GitHub
2. Settings → Pages → Deploy from a branch → `main` / `/root`
3. Åpne Pages-URLen

## Personvern
Appen lagrer ikke data og sender ingen data noe sted (kun klient-side).
