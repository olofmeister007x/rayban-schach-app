# Ray-Ban Schach-App (Prototyp)

Eine deutschsprachige Schach-Web-App als Ausgangspunkt für ein späteres Ray-Ban-Meta-Display-Projekt.

## Bestehende Open-Source-Bausteine
- [Chessboard.js](https://github.com/oakmac/chessboardjs): Schachbrett und Drag-and-drop.
- [Stockfish.js](https://github.com/nmrugg/stockfish.js): geplante Schach-Engine (noch **nicht** eingebunden).
- [chess.js](https://github.com/jhlywa/chess.js): Zugregeln und Spielzustand.

## Stand
Die `index.html` enthält ein spielbares lokales Schachbrett für zwei Personen an einem Gerät, eine Zugliste, Zurücknehmen und Brett drehen. Bibliotheken werden derzeit über CDNs geladen; Internet ist erforderlich.

**Nicht implementiert:** Stockfish-Zugberechnung, Spiel gegen den Computer, automatische Kameraerkennung, Meta-Brillenkamera, Anzeige auf dem Brillendisplay und Neural-Band-Steuerung.

## Test
`index.html` in einem Browser öffnen. Optional GitHub Pages für statisches Hosting aktivieren (Settings → Pages → Deploy from branch → main / root).

## Weiterer Plan
1. Stockfish.js-Version und zugehörige Worker-/WASM-Dateien lokal einbinden und Engine-Tests durchführen.
2. Modus „Gegen Computer“ und Analyseanzeige ergänzen.
3. Brett-Erkennung aus einer ausdrücklich freigegebenen Kameraquelle als eigenständiges Modul entwickeln.
4. Meta Wearables SDK und Display-Fähigkeiten anhand aktueller offizieller Dokumentation prüfen; ggf. iOS-Begleit-App bauen.

**Fair Play:** Analysehilfe nur für Training und Spiele, in denen sie erlaubt ist.
