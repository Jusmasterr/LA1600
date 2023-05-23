https://jusmasterr.github.io/LA1600/
# Projekt-Dokumentation

`Coconut:` Meister, Bühler, Lutziger, Goedertier

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|   09.05.2023    | 0.0.1   |       Dkumentation angefangen und Themen besprochen                                           |
|  16.05.2023       | 0.0.2     |   Angefangen an den ersten Arbeitspaketen zu Arbeiten                                              |
|  23.05.2023       | 0.0.3     | Weiter an dem Projekt gearbeitet                                                             |
|  30.05.2023       | 0.0.4     |                                                              |
|  06.06.2023       | 0.0.5     |                                                                                                                                                                     
|    13.05.2023      | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Wir erstellen eine Webseite über die letzten fünf Fußball-Weltmeisterschaften, auf der man die Resultate, sowie spezielle Aktionen oder Ereignisse dieser Weltmeisterschaften ansehen kann.

Unser aktuelles Projekt besteht darin, in einer neuen Arbeitsgruppe die Erstellung einer Webseite zu erlernen, einschließlich des dazugehörigen Code-Schreibens. Unser Ziel ist es, fundiertes Wissen über Webdesign und -entwicklung zu erwerben. Wir konzentrieren uns darauf, die Grundlagen der Webseitengestaltung und Programmierung zu beherrschen, um eine ästhetisch ansprechende und benutzerfreundliche Benutzeroberfläche zu erstellen. Durch den Einsatz moderner Technologien und bewährter Praktiken streben wir an, innovative Lösungen zu entwickeln und ein optimales Nutzererlebnis zu gewährleisten. Wir sind begeistert von dieser Herausforderung und freuen uns darauf, unsere Fähigkeiten in diesem spannenden Projekt weiterzuentwickeln.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1  |    Muss               | funktional     | Als Benutzer möchte ich die Ergebnisse vergangener Weltmeisterschaften einsehen, um die Resultate der einzelnen Spiele nachschlagen zu können.       |
| 2  |    Muss               |   funktional   |  Als Benutzer möchte ich den Gewinner vergangener Weltmeisterschaften einsehen, um zu erfahren, welche Nation die meisten Siege verbucht hat.    |                               
| 3  | Kann   | funktional     |   Als Benutzer möchte ich zwischen einem hellen und dunklen Modus wählen können, um die Webseite nach meinen persönlichen Vorlieben zu gestalten.    |                            
| 4  |         Kann          |  funktional    |    Als Benutzer möchte ich eine Auswahl zwischen zwei Sprachen haben, damit auch Personen, die kein Deutsch verstehen, die Webseite nutzen können.                                |
| 5  |      Muss             |  funktional    |    Als Benutzer möchte ich Informationen über besondere Ereignisse und Aktionen vergangener Weltmeisterschaften erhalten, um über diese Ereignisse informiert zu sein.                             |


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |   Webseite ist geöffnet           | Klicken auf den Button "Resultate"        |     Die Resultate der vergangenen Weltmeisterschaften werden angezeigt.            |
| 2.1  |     Webseite ist geöffnet          |Klicken auf den Button "Resultate" und anschließend nach den Siegern suchen | Die Gewinner der vergangenen Weltmeisterschaften werden angezeigt.  |
| 3.1  |       Das Menü ist geöffnet      | Auswahl des Farbmoduswechsels       |   Die Webseite wechselt in den Dark- oder White-Mode.            |
| 4.1  |   Sprachmenu ist offen           | Man wechselt die Sprache        |   Die Webseite wird in der ausgewählten Sprache angezeigt.                 |
| 5.1  |   Webseite ist geöffnet           |   Klicken auf den Button "Ereignisse"     |  Die ausgewählten Ereignisse werden angezeigt.   



### 1.4 Diagramme

✍️Fügen Sie hier ein Use Case-Diagramm mit mindestens 10 Anwendungsfällen ein; und einen PAP.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |  09.05.23     |     Justus  |          Menubar für "Resultate-button"          |      40         |
| 2.A  |  16.05.23     |    Justus  |           Dropdownmenu zur Auswahl des Jahres der Meisterschaft       |      40         |
| 3.A  |     06.06.2023   |              Justus |  Farbmenu erstellen                            |     30        |
| 4.A  | 23.05.2023       |                Justus |  Hintergrund in Whitemode ertellen           |     50        |
| 5.A  |   30.05.2023          |               Justus  | Hintergrund in Darkmode ertellen             |    30         |
| 6.A  |   06.06.2023  |                Justus  |   Menu für Sprachenauswahl                                          |   35          |
| 7.A  | 23.05.2023|           Justus   |   Webseite kann auf Deutsch eingestellt werden                              |    45         |
| 8.A  |  30.05.2023|         Justus     |   Webseite kann auf Englisch eingestellt werden                           |    60          |
| 9.A  | 23.05.2023       |              Lennard     |    Schöne Gestalltung                       |    45           |
| 10.A  | 06.06.2023       |                  Lennard |     Button für Ereignisse                                   |      30         |
| 11.A  | 30.05.2023|     Lennard  |Wenn man auf Ereigiss-Button drückt wird ein Jahr auswahl Dropdown menu aufgemacht|  35   |
| 12.A  | 23.05.2023|           Lennard   |Wenn man ein Jahr ausgewählt hat, werden zu diesem Jahr ereignisse angezeigt |    40        |
| 13.A  |   23.05.2023|            Lennard |    Es gibt Fussballfeld einen Hintergrund                                |    80         |
| 14.A  |23.05.2023  |             Lennard  |   Auf der Ereigniss Seite gibt es Texte                  |     30          |
| 15.A  |     06.06.202 |                  Lennard  |  Auf der Ereigniss Seite gibt es Bilder             |  30           |                                             
| 16.A  |23.05.2023        |     Lennard  | Auf dem Fussballfeld befindet sich Schiedsrichtier in Gelb             |    45           |
| 17.A  | 23.05.2023 |                  Timo     |   Auf dem Fussballfeld befindet sich ein Ball                     |     30         |
| 18.A  |    06.06.2023 |                  Timo     |  Auf dem Spielfeld befinden sich Linien                   |    40           |
| 19.A  |    06.06.2023 |          Timo    |    Grunddesign der Webseite erstellen                                     |  40          |
| 20.A  |     23.05.2023   |     Timo    |      Es gibt verschiedene Schriftarten auf der Website                    |    40        |
| 21.A  |  23.05.2023 |     Timo     | Es gibt einen Button für den Filter                           | 45              |
| 22.A  |  06.06.2023      |                  Timo     |   Farbenpallete passt sich an Systhempreferenz an            |   30          |
| 23.A  | 06.06.2023   |                  Timo     |    Es sind Farben auf unserer Webseite eingebaut                   |  30         |
| 24.A  | 30.05.2023      |                  Timo     |   Das Fussballfeld hat eine Grundanimation                     |     90        |
| 25.A  |   06.06.2023     |                  Cyril    |   Auf dem Fussballfeld befinden sich Spieler in Blau     | 50              |
| 26.A  | 30.05.2023      |                   Cyril   | Auf dem Fussballfeld befinden sich Spieler in Grün          | 40              |
| 27.A  |      06.06.2023  |          Cyril   |   Der Filter kann nach Tordifferenz filtern                       |     45          |
| 28.A  | 30.05.2023|                   Cyril   |  Der Filter kann nach Land filtern                               |    40           |
| 29.A  |    06.06.2023    |       Cyril   |     Der Filter kann nach Sieger des Turniers filtern                   |   40            |
| 30.A  | 23.05.2023       |                   Cyril   |Der Filter kann nach Gruppen filtern                    |  30             |
| 31.A  |   06.06.2023     |           Cyril  |  Der Filter kann runde suchen wo Rausgeflogen                |    40           |
| 32.A  |  30.05.2023     |                   Cyril   |  Webseiten Titel mit Farbe etc. ertellen                         |    30           |
Total: 



## 3 Entscheiden

Nach sorgfältiger Abwägung haben wir uns dafür entschieden, einen Dark Mode in unsere Webseite zu integrieren. Dieses Designkonzept wird von uns allen als passend empfunden und trägt oft zu einer verbesserten Ästhetik bei. Zudem haben wir beschlossen, unseren Benutzern eine Sprachauswahl anzubieten, wobei wir uns jedoch auf die englische Sprache beschränken. Wir sind zu dem Schluss gekommen, dass zusätzliche Sprachen unnötig wären und auch mit einem erheblichen Aufwand verbunden wären. Durch diese Entscheidungen möchten wir eine konsistente Benutzererfahrung gewährleisten und den Entwicklungsaufwand optimieren.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |  09.05.2023      |     Justus      |   40            |        40           |
| 2.A  |       |      Justus     |     40          |                   |
| 3.A  |       |      Justus     |    30           |                   |
| 4.A  |       |     Justus      |   50            |                   |
| 5.A  |       |     Justus      |   30            |                   |
| 6.A  |       |    Justus       |   35            |                   |
| 7.A  |       |    Justus       |    45           |                   |
| 8.A  |       |    Justus       |    60           |                   |
| 9.A  | 23.05.2023       |    Lennard       |   45            |     40              |
| 10.A  |       |     Lennard      |  30             |                   |
| 11.A  |       |     Lennard      |  35             |                   |
| 12.A  |       |      Lennard     |  40             |                   |
| 13.A  |      |     Lennard      |  80             |                   |
| 14.A  | 23.05.2023       |    Lennard       |   30            |     35              |
| 15.A  |23.05.2023        |    Lennard       |   30            |    30               |
| 16.A  |       |    Lennard       |   45            |                   |
| 17.A  |       |     Timo      |     30          |                   |
| 18.A  |       |      Timo     |    40           |                   |
| 19.A  |       |     Timo      |     40          |                   |
| 20.A  |       |     Timo      |      40         |                   |
| 21.A  |       |     Timo      |      45         |                   |
| 22.A  |       |      Timo     |      50         |                   |
| 23.A  |       |     Timo      |     40          |                   |
| 24.A  |       |     Timo      |     90          |                   |
| 25.A  |       |     Cyril      |    30           |                   |
| 26.A  |       |     Cyril      |    30           |                   |
| 27.A  |       |      Cyril     |  45             |                   |
| 28.A  |       |     Cyril      |   40            |                   |
| 29.A  |       |      Cyril     |     40          |                   |
| 30.A  |       |     Cyril      |     30          |                   |
| 31.A  |       |     Cyril      |     40          |                   |
| 32.A  |       |      Cyril     |     30          |                   |





## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
