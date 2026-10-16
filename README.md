# TUNG TUNG RUNNER

Ein kleines, mobilfreundliches Endless-Runner-Spiel im Subway-Surfer-Stil. Läuft direkt im Browser und kann kostenlos über GitHub Pages veröffentlicht werden.

## Dateien
- `index.html` – komplettes Spiel (HTML, CSS und JavaScript)
- `assets/obstacle-photo.jpg` – dein Foto als Hindernis-Asset

## Lokal testen
Öffne `index.html` im Browser. Für zuverlässiges Laden des Assets kannst du einen lokalen Server verwenden, z. B. mit VS Code Live Server.

## Auf GitHub veröffentlichen
1. Erstelle auf GitHub ein neues Repository, z. B. `tung-tung-runner`.
2. Lade `index.html` und den Ordner `assets` hoch (Ordnerstruktur beibehalten).
3. Öffne **Settings → Pages**.
4. Bei **Build and deployment** wähle **Deploy from a branch**, Branch `main`, Ordner `/(root)`, dann **Save**.
5. Warte kurz und öffne die angezeigte GitHub-Pages-Adresse auf deinem Handy.

## Steuerung
- Wischen links/rechts: Spur wechseln
- Nach oben wischen: springen
- Alternativ die Bildschirmbuttons nutzen
- Tastatur: Pfeiltasten / Leertaste

Hinweis: Das Hindernisfoto wird aktuell als vollständiges Foto angezeigt. Für einen wirklich transparenten Freisteller ersetze `assets/obstacle-photo.jpg` durch ein transparentes PNG und ändere in `index.html` die Bildquelle auf `assets/obstacle-cutout.png`.
