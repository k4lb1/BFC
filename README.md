# Brainfuck Converter (PWA)

Kleine Progressive Web App: Text in Brainfuck-Code umwandeln und wieder dekodieren.

- **Zu Brainfuck** – wandelt den eingegebenen Text in Brainfuck-Anweisungen um
- **Base64** – Ausgabe optional als Base64 (z. B. für kürzere Darstellung)
- **Dekodieren** – Brainfuck-Code aus dem Ausgabefeld ausführen und Ergebnis in die Eingabe zurückschreiben

Funktioniert offline, kann als App auf dem Homescreen installiert werden.

## Starten

Einfach `index.html` im Browser öffnen oder mit einem lokalen Server (z. B. `python3 -m http.server`) ausliefern.

## Technik

- Nur HTML, CSS und Vanilla-JS, keine Abhängigkeiten
- `manifest.json` für PWA-Installation
