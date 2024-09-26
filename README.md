# candy_power_ranking
Fallstudie: Erweiterung des Süßwarensortiments (Eigenmarke)
Szenario
Der Einkauf von Lidl möchte das Süßwarensortiment (Eigenmarke) erweitern. Hierzu soll eine neue Süßigkeit kreiert werden. Jedoch besteht innerhalb des betreffenden Projektteams noch Uneinigkeit über die Charakteristika der neuen Süßigkeit.
Während die Einen beispielsweise eine Keks-basierte Süßigkeit bevorzugen, favorisieren Andere eine Fruchtgummivariation. Daher hat der Bereichsvorstand beschlossen ein Marktforschungsunternehmen zu beauftragen, um die Beliebtheit, der am Markt erhältlichen Süßwaren, zu ermitteln.
Die Ergebnisse der Marktforschung liegen nun vor und Du wurdest beauftragt eine Analyse der Daten durchzuführen. Ziel ist es, die Auswirkungen der Charakteristika von Süßwaren auf deren Beliebtheit zu analysieren und auf Basis dieser Analyse eine Empfehlung für die Eigenschaften einer neuen Süßigkeit abzugeben.

Den Datensatz (inkl. einer kurzen Beschreibung) findest Du unter:
https://github.com/fivethirtyeight/data/tree/master/candy-power-ranking
Hierbei handelt es sich um einen Datensatz von FiveThirtyEight, der unter der Creative Commons Attribution 4.0 International license (https://creativecommons.org/licenses/by/4.0/) steht.


## Datensatzübersicht

Die Datei `candy-data.csv` enthält Attribute für verschiedene Süßigkeiten sowie deren Rangfolge basierend auf ihrer Beliebtheit. Bei binären Variablen bedeutet **1 "ja"** und **0 "nein".**

### Datenfeldbeschreibung

| **Spaltenname**        | **Beschreibung**                                                        |
|------------------------|-------------------------------------------------------------------------|
| `chocolate`            | Gibt an, ob die Süßigkeit Schokolade enthält.                           |
| `fruity`               | Gibt an, ob die Süßigkeit fruchtig ist.                                 |
| `caramel`              | Gibt an, ob die Süßigkeit Karamell enthält.                             |
| `peanutalmondy`        | Gibt an, ob die Süßigkeit Erdnüsse, Erdnussbutter oder Mandeln enthält.|
| `nougat`               | Gibt an, ob die Süßigkeit Nougat enthält.                               |
| `crispedricewafer`     | Gibt an, ob die Süßigkeit gepufften Reis, Waffeln oder Keks enthält.    |
| `hard`                 | Gibt an, ob es sich um eine harte Süßigkeit handelt.                   |
| `bar`                  | Gibt an, ob es sich um einen Schokoriegel handelt.                      |
| `pluribus`             | Gibt an, ob die Süßigkeit Teil einer Sammlung ist (z. B. mehrere Süßigkeiten in einer Tüte oder Schachtel). |
| `sugarpercent`         | Repräsentiert den Zuckergehalt in Prozent im Vergleich zu anderen Süßigkeiten im Datensatz. |
| `pricepercent`         | Repräsentiert den Preis in Prozent im Vergleich zu anderen Süßigkeiten im Datensatz. |
| `winpercent`           | Der Gesamtgewinnprozentsatz basierend auf 269.000 Vergleichen.         |
