# Geolcodes repository

This repository contains an initial dictionary of defining geolcodes and labels.

## CSV columns:

Multilanguage lookup tables with geolcodes of all the classes in CSV format. 

1. geolcode
2. class
3. abbreviation
4. German
5. German description
6. French
7. French description
8. Italian
9. Italian description
10. English
11. English description
12. Extra
13. Tree / Path

## Classes:

| CLASS | ATTRIBUTE | DESCRIPTION | GEOLCODE |
| ----- | --------- | ----------- | -------- |
| ebor102 | Cuttings | Angabe, ob Bohrgut als Kern, Cuttings, oder gar nicht vorliegt. Aussage über Qualität der Schichtbeschreibungen. Mehrere Angaben möglich.  | PRESENT |
| ebor103 | Purpose | Grund / Zweck / Anlass der Bohrung. Mehrere Werte möglich | PRESENT
| ebor104 | Status of borehole | Status der Bohrung (ausgebaut, verfüllt, in Betrieb…) --> letzter Wissensstand. kann auch wieder entfernt werden, wenn es keinen Sinn macht. | PRESENT
| ebor106 | Groundwater | Angabe, ob Grundwasser vorhanden ist oder nicht. | PRESENT
| ebor107 | Drilling method | Angabe der Bohrmethode, z.B. Kernbohrung, Rammsondierung, etc. Angabe von mehrern Methoden möglich. Das Wörterbuch ist noch nicht abgeschlossen und kann laufend ergänzt werden. | PRESENT
| ebor108 | QC top bedrock | Angabe der Genauigkeit der Tiefenangabe Top Fels. Z.B. werden in vielen Kantonen EWS-Proben nur alle 2m genommen - d.h. Tiefenangabe erfolgt nur auf 2m genau; oder bei Unsicherheit wegen Verwitterung | PRESENT
| ebor109 | Land use | Wald, Wiese, Gebäude,…. Kann Hinweis auf Zugänglichkeit geben | PRESENT
| ebor115 | QC depth | Angabe der Genauigkeit der Tiefenangabe. Z.B. werden in vielen Kantonen EWS-Proben nur alle 2m genommen - d.h. Tiefenangabe erfolgt nur auf 2m genau. | PRESENT
| ebor116 | QC inc / direction | Angabe ob Ink/Einfall. gemessen oder geschätzt wurde | PRESENT
| ibor101 | Borehole kind | Gemäss DM Bohrdaten und Bohrdaten AG --> 3 Grundtypen: Bohrung, Rammsondierung, Sondierschlitz. "anderes" und "keine Angaben" möglichst NIE verwenden. | PRESENT
| ibor104 | SRS | Koordinatenreferenzsystem, Eingabe des EPSG-Codes | PRESENT
| ibor106 | HRS | CH_LN02 (alt); LN95 kann noch ergänzt werden, wenn notwendig | PRESENT
| ibor111 | Restriction | frei / gesperrt / beschränkt bis; "beschränkt bis" schaltet das Datumsfeld in GeODin auf Pflicht, d.h.: es MUSS ein Datum eingegeben werden | PRESENT
| ibor113 | QC coordinates | Rundungs-Einschätzung der Koordinaten auf Original-Bohrprofil; in der Verantwortung des Erfassers! Z.B. 2'600'300/1'198'500 => auf 100m gerundet; r= rekonstruiert, d.h. später mittels Karten rekonstruiert. Hier konnte keine Übereinstimmung mit GeoQuat erzielt werden! | PRESENT
| ibor114 | QC elevation Z | Rundungs-Einschätzung der Höhenangabe auf Original-Bohrprofil; z.B. 520 m => auf 10m gerundet; r= rekonstruiert, d.h. später mittels Karten rekonstruiert. Hier konnte keine Übereinstimmung mit GeoQuat erzielt werden! | PRESENT
| ibor117 | Reference elevation Z | Referenzpunkt der Höhenkote: OK Terrain, Rohroberkante,… Liste wird kontinuierlich weiter ergänzt. | PRESENT
| icon407 | Canton | Schlüsseleingabe (auch Kleinbuchstaben). Eine Eingabeprüfung Kanton ⊆ Land ist für die Weiterentwicklung geplant. | PRESENT
| icon408 | Country | Schlüsseleingabe (auch Kleinbuchstaben) | PRESENT
| mcla101 | USCS | USCS-Klassifikation der ersten Komponente. Eine Angabe möglich. | PRESENT
| mlpr102 | Compactness | Lagerungsdichte der Schicht. Eine Angabe möglich. | PRESENT
| mlpr103 | Consistance | Konsistenz der Schicht. Eine Angabe möglich. | PRESENT
| vchr401 | Chronostrati top bedrock | Chronostratigraphi; Datenmodell Geologie | PRESENT
| vlit40  | Lit/Pet top bedrock | Lithologie/Petrologie Top Fels | PRESENT
| vlit500 | Lithostratigraphy | Lithostratigraphie der Schicht | PRESENT
