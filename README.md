# 🎵 Notensammler

Ein kleines Retro-Musikspiel für Kinder im Pixel-Art-Stil — alles in einer einzigen HTML-Datei, ohne Installation, ohne Abhängigkeiten.

Fang mit deinem Kescher die Noten, die vom Himmel fallen, und bring sie zum Mischpult. Aber pass auf die Blitze auf!

## 🎮 So wird gespielt

Einfach die Datei [`notensammler.html`](notensammler.html) im Browser öffnen — fertig. Funktioniert am PC und auf dem Handy/Tablet.

| Gerät | Steuerung |
|---|---|
| PC | Pfeiltasten ← → |
| Handy / Tablet | Mit dem Finger über das Spielfeld wischen |

Gefangene Noten landen im Kescher (zu sehen als bunte Punkte im Netz). Lauf nach rechts zum Mischpult, um sie abzugeben. Wirst du von einem Blitz getroffen, verlierst du alle Noten im Kescher!

## 🕹️ Zwei Spielmodi

### Melodie-Sammler
Oben wird ein Kinderlied angezeigt. Sammle die Noten in der richtigen Reihenfolge und gib sie am Mischpult ab. Ist das Lied vollständig, spielt das Mischpult es mit echten Notenlängen und Pausen ab — und du gewinnst den goldenen Notenschlüssel! 🏆

Eingebaute Lieder:
- Alle meine Entchen
- Hänschen klein
- Bruder Jakob
- Kuckuck, Kuckuck
- Morgen kommt der Weihnachtsmann
- Fuchs, du hast die Gans gestohlen
- Backe, backe Kuchen
- Jingle Bells

### Eigene Melodie
Sammle Noten ganz frei und komponiere dein eigenes Lied! Dabei zählt auch der **Notenwert**: Es fallen Achtel-, Viertel-, halbe und ganze Noten vom Himmel — dein Lied wird genau mit diesen Längen abgespielt. Am Ende bewertet das Mischpult deine Komposition (Länge, Ton-Abwechslung, Melodiesprünge und Rhythmus) und du gewinnst einen von **24 Pixel-Art-Pokalen** — vom *Verstimmten Quietscheentchen* bis zur *Sinfonie-Krone*.

## ✨ Features

- 🎨 Komplett handgemachte Pixel-Art (Spielfigur mit Laufanimation, Kescher, Trophäen, Bühne)
- 🎼 Echte Notenwerte: Achtelnoten (mit Fähnchen), Viertelnoten, halbe und ganze Noten — jede Form fällt vom Himmel
- ⏸️ Lieder mit richtigen Pausen und unterschiedlichen Tempi
- 🔊 Sound komplett über die Web Audio API erzeugt (Retro-Chiptune-Klang, keine Audiodateien)
- ⚡ Elektrisch-blaue Blitze als Hindernis
- 🏆 24 liebevoll gestaltete Pixel-Trophäen in 4 Wertungsstufen + 1 Geheim-Trophäe
- 📱 Läuft auf Desktop und Mobilgeräten — das Spielfeld passt sich automatisch an den Bildschirm an
- 🅰️ Pixel-Schriftarten ("Press Start 2P" und gut lesbares "VT323") für echtes Retro-Gefühl

## 🛠️ Technik

- Eine einzige HTML-Datei mit Vanilla JavaScript und Canvas 2D — kein Build, keine Dependencies
- Alle Sprites sind als ASCII-Pixelraster im Quellcode definiert und werden zur Laufzeit gezeichnet
- Töne werden mit Oszillatoren (Rechteck-Welle) der Web Audio API erzeugt
- Schriftarten werden von Google Fonts geladen (mit Fallback auf Monospace, falls offline)

## 📄 Lizenz

Siehe [LICENSE](LICENSE).
