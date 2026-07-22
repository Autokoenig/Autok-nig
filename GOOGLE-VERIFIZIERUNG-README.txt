So verifizierst du autoknigge.de in der Google Search Console
================================================================

Schritt 1: Google Search Console öffnen
- Gehe zu https://search.google.com/search-console
- "Property hinzufügen" -> "URL-Präfix" -> https://autoknigge.de eingeben

Schritt 2: Verifizierungsmethode wählen (eine der beiden reicht)

Methode A - HTML-Datei (empfohlen, am einfachsten für GitHub Pages):
- Google zeigt dir eine Datei zum Download an, z. B. "google1a2b3c4d5e6f7g8h.html"
- Diese Datei unverändert in den Haupt-Ordner (Root) des Repositorys hochladen,
  direkt neben index.html, styles.css usw.
- Bei Google auf "Bestätigen" klicken

Methode B - HTML-Meta-Tag:
- Google zeigt dir einen Code wie:
  <meta name="google-site-verification" content="ABC123..." />
- Sag mir einfach den "content"-Wert (den Code nach content="..."),
  dann füge ich ihn dir in den <head>-Bereich von index.html ein

Schritt 3: Sitemap einreichen
- In der Search Console links auf "Sitemaps" klicken
- "https://autoknigge.de/sitemap.xml" eintragen und senden

Das war's - keine weiteren Änderungen an der Website nötig für diesen Schritt.
Diese Datei kannst du nach der Verifizierung wieder löschen.
