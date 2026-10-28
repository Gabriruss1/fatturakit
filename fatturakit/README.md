# FatturaKit

Fatture per freelance italiani, gratis, nel browser, senza registrazione.
Calcolo automatico di INPS 4% e tassa sostitutiva (15% / 5%) per regime forfettario.

## Struttura
- `index.html` — landing page (dark, Tailwind CDN, Inter)
- `fattura.html` — generatore di fatture client-side, stampa PDF via `window.print()` + `@media print`

## Modello di business
- **Gratis**: generatore ( traffico)
- **Kit Pro €9 una tantum** (Gumroad): template Word/Excel, solleciti pagamento, foglio liquidità, mini-guida forfettario

## Costi attuali: 0€
Hosting GitHub Pages gratuito. Nessun backend, nessun database, nessun cookie.

## Roadmap
- [x] v0.1 landing + generatore + calcolo forfettario
- [ ] Deploy GitHub Pages
- [ ] Wire checkout Gumroad (link effettivo)
- [ ] SEO: sitemap + 2 pagine long-tail ("fattura in regime forfettario", "a cosa serve fornitore fiscale")
- [ ] Copy per 3 canali acquisizione (Reddit, LinkedIn, dev.to)
- [ ] v0.2: salvataggio dati cliente in localStorage
- [ ] v0.3: num progressiva memorizzata, più coefficienti ATECO

## Disclaimer
Non è consulenza fiscale. Le stime forfettarie sono indicative.
