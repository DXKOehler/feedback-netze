# Spinnennetz — Interaktives Feedbacknetz (dxko)

Elegante, interaktive Visualisierung zur Erfassung von Feedback als Radardiagramm — ideal für schnelle Peer-Reviews, Lernfeedback oder Retrospektiven.

[![Vorschau](assets/preview_feedback_netze.png)](tools/dxko_feedback-netze.html)

Kurzbeschreibung
----------------
Dieses kleine, fokussierte Tool erzeugt interaktive Spinnennetze (Radar-Charts). Nutzer*innen können entlang von Achsen Werte setzen (diskret oder kontinuierlich), Kategorien bearbeiten, mehrere Zustände vergleichen und das Ergebnis als PNG herunterladen.

Funktionen
---------
- Interaktives Radardiagramm mit beliebig vielen Kategorien (3–12)
- Diskreter Modus (bewertbare Ringe) und kontinuierlicher (freie Position entlang eines Strahls)
- Invertierbare Skala (höhere Werte innen/außen)
- Entwicklungsmodus: Vergleich „vorher“ vs. „nachher“
- Skalierung (Anzahl der Ringe) anpassbar (3–15)
- Kategorien editierbar: hinzufügen, löschen, umbenennen
- PNG-Export der aktuellen Ansicht
- Leichtgewichtige, rein clientseitige HTML/CSS/JS-Implementierung — keine Backend-Abhängigkeiten

Vorschau
-------
Die Datei `assets/preview_feedback_netze.png` im Repository enthält eine Vorschaubild-Ansicht. Öffne alternativ direkt die Detailseite:

- Datei: `tools/dxko_feedback-netze.html`

Wie du es lokal öffnest
-----------------------
Einfachste Methode: Datei im Browser öffnen (relative Pfade funktionieren):

PowerShell:
```powershell
# Öffnet die HTML-Datei mit der Standardanwendung (Browser)
Start-Process .\tools\dxko_feedback-netze.html
