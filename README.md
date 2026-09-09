# NOVA – iPhone Testversion v2

Diese Version ist eine statische PWA für GitHub Pages und kann auf dem iPhone zum Home-Bildschirm hinzugefügt werden.

## Enthalten
- Heute-Ansicht mit einfachem Assistenten
- Monatskalender mit Mitarbeiterfilter
- Öffnungszeiten, Betriebsferien und Mitarbeiterferien
- Termin erstellen, ansehen, absagen und kassieren
- Kein manueller „Erledigt“-Button: Zahlung via TWINT/Karte/Bar setzt Termin automatisch auf „Bezahlt“
- Kasse mit freien Verkäufen
- Kundenübersicht und Kundenprofil
- Team mit Mitarbeiterrechten und Ferien
- Einzelbetrieb/Team-Modus: unnötige Teamfelder verschwinden automatisch
- Analyse mit Umsatz, Zahlungsarten, Top-Leistungen und – nur im Teammodus – Umsatz pro Mitarbeiter
- Dienstleistungen & Preisänderungen mit Verlauf
- Excel-, CSV- und PDF-Export
- Designfarbe
- Mitarbeiter-Testansicht: sieht nur eigene Termine
- Sprachsteuerung, falls der Browser Web Speech Recognition unterstützt

## Wichtiger Hinweis zur KI
Der Assistent ist in dieser statischen Testversion aktiv und kann typische Befehle auf den lokalen Testdaten ausführen bzw. vorbereiten. Eine echte generative Cloud-KI wird absichtlich nicht direkt aus einer öffentlichen GitHub-Seite mit API-Schlüssel verbunden, weil der Schlüssel sonst öffentlich wäre. Für die Produktversion kommt dafür ein geschütztes Backend dazwischen.

## GitHub Pages
1. Neues GitHub Repository erstellen.
2. Alle Dateien aus diesem Ordner ins Root des Repositories laden.
3. GitHub: Settings → Pages.
4. Deploy from a branch → `main` → `/root`.
5. Die GitHub-Pages-Adresse in Safari auf dem iPhone öffnen.
6. Teilen → „Zum Home-Bildschirm“.

Falls eine ältere Version wegen PWA-Cache erscheint, die Seite einmal neu laden oder die alte Home-Bildschirm-App entfernen und erneut hinzufügen.
