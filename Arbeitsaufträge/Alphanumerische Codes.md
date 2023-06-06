# Daten codieren

## Alphanumerische Codes ASCII und Unicode

### UTF-8/UTF-16 analyse

#### Sample 1 | ASCII

4 Charaktere: BERN
4 HexZiffern: 42 45 52 4E

#### Sample 2 | UTF-8

4 Charaktere: BERN
4 HexZiffern: 42 45 52 4E

#### Sample 3 | ASCII

4 Charaktere: Z�ri
4 HexZiffern: 5A 81 72 69

#### Sample 4 | UTF-8

4 Charaktere: Züri
5 HexZiffern: 5A C3 BC 72 69

#### Sample 5 | UTF-8

4 Charaktere:  工业学校
12 HexZiffern: E5 B7 A5 E4 B8 9A E5 AD A6 E6 A0 A1

### Kollektion Keyboard-Fremden Zeichen

Zeichen - Unicode - Englischer Name des Zeichens

۩ - U+06E9 - Arabischer Ort der Sajdah
༃ - U+0F03 - Tibetan Mark Gter Yig Mgo undefined-Um Gter Tsheg Ma
௸ - (U+0BF8) - Tamil as Above Sign
֍ - (U+058D) - Nach rechts deutendes armenisches Zeichen für Ewigkeit
֎ - (U+058E) - Nach links deutendes armenisches Zeichen für Ewigkeit
۾ - (U+06FE) - Arabisches Zeichen sindhi-sprachliches nachgestelltes Men
࿇ - (U+0FC7) - Tibetan Symbol Rdo Rje Rgya Gram
᥀ - (U+1940) - Limbu Sign Loo
᎐ - (U+1390) - Ethiopic Tonal Mark Yizet
᧫ - (U+19EB) - Khmer Symbol Dap-Muoy Koet
℃ - (U+2103) - Grad Celsius
℆ - (U+2106) - Cada-Una-Zeichen
℞ - (U+211E) - Zeichen für Ärztliches Rezept
℟ - (U+211F) - Antwort-Zeichen
⅌ - (U+214C) - Pro-Zeichen
⇝ - (U+21DD) - Schnörkelpfeil nach rechts
⇛ - (U+21DB) - Pfeil mit Dreifachstrich nach rechts
⇗ - (U+21D7) - Pfeil mit Doppelstrich nach Nordosten

### Welche der Dateien ist nun ASCII-codiert, welche UTF-8 und welche UTF-16 BE-BOM?

1. ASCII
2. UTF-8
3. UTF-16

### Alle drei Dateien enthalten denselben Text. Aus wie vielen Zeichen besteht dieser?

68

### Was sind die jeweiligen Dateigrössen? (Beachten sie, dass unter Grösse auf Datenträger jeweils 0 Bytes angegeben wird. Dies darum, weil beim Windows-Dateisystem NTFS kleine Dateien direkt in die MFT (Master File Table) geschrieben werden.) Wie erklären sie sich die Unterschiede?

1. 68   ASCII  1:1
2. 71   UTF-8  1:1-4
3. 138  UTF-16 1: 2/4

### Bei den weiteren Fragen interessieren uns nur noch die ASCII- und die UTF-8-Datei: Bekanntlich ist UTF-8 in den ersten 128 Zeichen deckungsgleich mit ASCII. Untersuchen sie nun die beiden HEX-Dumps und geben sie an, welche Zeichen unterschiedlich codiert sind. Ein kleiner Tipp: Es sind deren zwei

ä & €

### Was bedeuten die beiden Ausdrücke, denen wir z.B. bei UTF-16 begegnen: Big-Endian (BE), Little-Endian (LE)?

BE & LE bedeuten nur andere Byte Reihenfolge
