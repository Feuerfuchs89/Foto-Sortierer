<p align="center"><img src="icon-192.png" width="120" alt="Fotosortierer-Icon"></p>

# Fotosortierer

Fotos und Videos im **3D-Raum** (oder im Raster) in Ordner ordnen, automatisch nach Datum sortieren und als ZIP exportieren. Alles läuft lokal im Browser: nichts wird hochgeladen, deine Originale bleiben unverändert.

## Funktionen

- 3D-Raum mit Ordnern und Foto-Karten, Rasteransicht als Alternative
- Auswahl mit Häkchen, Auswahlleiste unten, Ordnerleiste unter dem Raum
- Automatisch sortieren nach Jahr/Monat, Monat, Bildformat oder Dateityp
- Duplikat-Erkennung und Sammelordner „Datum unklar“
- Ausmisten: Ordner „🗑 Aussortieren“ (kommt nicht ins ZIP) und Sterne „★ Beste markieren“ (Taste `F`), mit „★ Beste wählen“ landen alle Besten gesammelt in einem Ordner
- Export als ZIP (bei Bedarf auf mehrere Dateien verteilt) und als CSV-Zuordnung
- Rückgängig, Hell/Dunkel, Tastatur: `1`–`9` Ordner, `Esc` Auswahl aufheben

## Benutzen

**Online mit GitHub Pages:** Dateien in ein Repository hochladen, dann *Settings → Pages*, Branch `main`, Ordner `/ (root)`. Die App liegt danach unter `https://<name>.github.io/<repo>/`.

**Lokal:** `index.html` im Browser öffnen, oder mit `python3 -m http.server` starten.

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | die komplette App (HTML, CSS, JS, 3D-Modell, three.js eingebettet) |
| `icon.svg`, `icon-*.png`, `favicon-32.png` | App-Icon |
| `manifest.webmanifest` | Installation auf dem Startbildschirm |
| `.nojekyll` | GitHub Pages liefert die Dateien unverändert aus |

## Hinweise

- Schriften (Manrope, Source Sans 3) kommen von Google Fonts, offline greifen Systemschriften.
- Der 3D-Raum braucht WebGL, sonst schaltet die App auf das Raster um.

## Lizenz

MIT, siehe `LICENSE`. Enthält [three.js](https://threejs.org) (MIT).
