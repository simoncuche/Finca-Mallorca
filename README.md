# Finca Mallorca – 3D-Rundgang

Ein kleines First-Person-Spiel im Browser: ein begehbares 3D-Modell der Finca,
nachgebaut nach Fotos (Tor mit Bögen, Zypressenallee, Steinhof, Haupthaus mit
Außentreppe, Carport, Pool mit Rasen, Grillhaus, Spielpavillon).

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

Alle acht Orte der Finca entdecken. Die Minikarte oben rechts zeigt die
Anlage, entdeckte Orte leuchten gelb.

## Aufbau

Alles ist prozedural aus Grundkörpern gebaut (keine externen Modelle oder
Texturen). Die Anlage liegt in einem Koordinatensystem in Metern:
Tor bei z = 58, Allee entlang x = 0 nach Norden, Hof um den Ursprung,
Haus im Nordosten, Pool und Rasen im Osten, Spielpavillon im Nordosten
hinter dem Haus.
