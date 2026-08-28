# Schriften

Diese Dateien liegen bewusst im Repo: der Service Worker kann nur Antworten
gleicher Herkunft zwischenspeichern, deshalb wäre die App ohne sie offline auf
Systemschriften zurückgefallen.

| Datei | Familie | Zeichensatz |
|---|---|---|
| `caveat-latin.woff2` | Caveat | latin |
| `caveat-latin-ext.woff2` | Caveat | latin-ext |
| `karla-latin.woff2` | Karla | latin |
| `karla-latin-ext.woff2` | Karla | latin-ext |

Beides sind variable Schriften. Eine Datei bedient darum alle benutzten
Schnitte (Caveat 500/700, Karla 400/600/700); die `@font-face`-Regeln in
`index.html` verweisen mehrfach auf dieselbe Datei.

Bezogen von Google Fonts, lizenziert unter der SIL Open Font License 1.1 –
siehe `OFL-Caveat.txt` und `OFL-Karla.txt`.
