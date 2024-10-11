# Max-CPU

## Info
- 8 Bit Input
- 8 Bit Adresse
- Laden von Ram zu CPU Register A / B
- Speichern CPU Register A / B zu Ram
- Alle vier Grundrechenarten
- Kann zu bestimte Aufgabe springen
- kann "Wenn" Aufgaben machen mit A / B

## Was ist Max-CPU
Das ist ein Eigen erstelte 8 Bit CPU in [Logisim](http://www.cburch.com/logisim/)
> [!TIP]
> Nimmt lieber [Logisim-evolution](https://github.com/logisim-evolution/logisim-evolution)

## Aufgaben

Aufbau: `Funktion` `Attribut`\
Beispiel: `01` `08`\
Erklärung: Es nimmt von Ram Adresse 8 und gibt es zu Register A

| Code | Name          | Beschreibung |
| ---: | :--:          | ------------ |
|   00 | Nichts        | Es macht Nichts und geht weiter |
|   01 | Lade Ram zu A | Das Läde von der Ram Adresse `Attribut` und gibt es zu Register A |
|   02 | Lade Ram zu B | Das Läde von der Ram Adresse `Attribut` und gibt es zu Register B |
|   03 | Lade zu A     | Das nimmt `Attribut` und gibt es zu Register A |
|   04 | Lade zu B     | Das nimmt `Attribut` und gibt es zu Register B |