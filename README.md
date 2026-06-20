# Estrazione Lettera Fantacalcio

Tool gratuito che estrae una lettera casuale dalla A alla Z per iniziare la chiamata
dei calciatori nell'asta del fantacalcio.

Sito statico: solo HTML, CSS e JavaScript, senza framework e senza step di build.

## File

- `index.html` — la pagina e il tool (tutto inline)
- `robots.txt` — istruzioni per i crawler + link alla sitemap
- `sitemap.xml` — sitemap con la sola homepage

## Prima di pubblicare

Sostituisci ovunque il dominio segnaposto `https://www.tuodominio.it/` con il tuo
dominio reale. Compare in:

- `index.html` → tag `<link rel="canonical">` e `<meta property="og:*">`
- `robots.txt` → riga `Sitemap:`
- `sitemap.xml` → tag `<loc>`

Crea inoltre l'immagine di anteprima `og-image.png` (1200×630) e mettila nella radice
del progetto, così le condivisioni mostrano l'anteprima.

## Deploy

Sito statico: si pubblica così com'è. Su Vercel non serve alcuna configurazione di build.
