# Schlüsseldienst Hugo Starter

Einfacher Hugo‑Starter für eine Schlüsseldienst‑Website (deutsch), inkl. SEO‑Grundlagen (LocalBusiness/Locksmith JSON‑LD), Netlify‑Deploy und optionalem Decap CMS.

## Lokal starten
1. [Hugo installieren](https://gohugo.io/getting-started/installing/)
2. Im Ordner dieses Projekts:
   ```bash
   hugo server -D
   ```
3. Browser: http://localhost:1313

## Auf Netlify deployen
- Repo zu GitHub pushen.
- Auf Netlify: **Add new site → Import from Git**.
- Build command: `hugo --minify` · Publish dir: `public`
- Optional: unter **Identity** Git Gateway aktivieren → `/admin` öffnen für visuelles Editieren mit Decap.

## Wichtige Stellen anpassen
- `hugo.toml` → Name, Telefon, Adresse, Öffnungszeiten.
- Inhalte unter `content/`
- Preise & Texte in `layouts/index.html`

## Rechtliches (DE)
- Impressum & Datenschutz ausfüllen.
- Kein Tracking aktiv? Dann i.d.R. kein Cookie‑Banner nötig.
