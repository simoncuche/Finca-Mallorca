# Finca Mallorca – 3D-Rundgang

Ein kleines First-Person-Spiel im Browser: ein begehbares 3D-Modell der Finca,
nachgebaut nach Fotos (Tor mit Bögen, Zypressenallee, Steinhof, Haupthaus mit
Außentreppe, Carport, Wintergarten, Pool mit Deck, Poolhaus, Spielpavillon).

## Starten

`index.html` im Browser öffnen. Es wird nur Three.js von cdnjs geladen,
sonst ist alles in der Datei enthalten.

## Steuerung

| Eingabe | Aktion |
| --- | --- |
| W A S D / Pfeiltasten | Laufen |
| Maus | Umsehen (Klick ins Bild fängt die Maus, Esc gibt sie frei) |
| Shift | Rennen |
| E | Tor öffnen |
| Touch | linker Daumen laufen, rechter Daumen umsehen, Knopf fürs Tor |

## Spielziel

Alle elf Orte der Finca entdecken. Die Minikarte oben rechts zeigt die
Anlage, entdeckte Orte leuchten gelb.

## Aufbau

Alles ist prozedural aus Grundkörpern gebaut (keine externen Modelle oder
Texturen). Die Anordnung folgt dem Luftbild (Norden oben, etwa 10 Pixel pro
Meter). Koordinaten in Metern, x nach Osten, z nach Süden, Ursprung im Hof:

- Tor und Zypressenallee kommen von Osten und laufen nach Westsüdwesten in den
  Hof. Der Hauskomplex (Haupthaus, Anbau mit Außentreppe, Natursteinflügel,
  Carport, Wintergarten) ist um 21 Grad gedreht, die Fassade zeigt zum Hof.
- Pool, Holzdeck und Poolhaus liegen nordwestlich hinter dem Haus.
- Der Rundweg (rote Linie im Luftbild) führt vom Hof nach Westen, am Rasen
  vorbei nach Norden, über die Wiese nach Osten und durch den Wald zum Tor.
- Nördlich der Wiese liegt der Tennisplatz, südwestlich der Spielpavillon,
  der Talblick geht nach Norden.
