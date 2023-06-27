# Lern-Bericht
### Coconut
#### Gruppenleiter: Justus Meister

Gruppenmitglieder: Cyril Lutziger, Lennard Buehler, Timo Goedertier

## Einleitung

In unserem Projekt geht es um eine Webseite, auf der man Resultate der Fussball WM anschauen kann.

## Was habe ich gelernt?

In diesem Projekt haben wir gelernt, wie man ein Dropdown Menü macht. Dies hat uns auch sehr geholfen, beim Erstellen dieser Webseite und ist allgemein ziemlich hilfreich.

## Beschreibung

Ein Dropdown-Menü ist ein häufiges Element in der Webentwicklung, das Benutzern eine Liste mit Optionen zur Auswahl bietet. In HTML werden Dropdown-Menüs mit dem `<select>`-Element erstellt, während Optionen mit dem `<option>`-Tag definiert werden. CSS wird verwendet, um das Erscheinungsbild des Dropdown-Menüs anzupassen.

```html
<div class="dropdown">
  <li class="dropItem"><a href="results.html">Results</a></li>
  <div class="dropdownContent">
    <a href="2022.html">2022</a>
    <a href="2018.html">2018</a>
    <a href="2014.html">2014</a>
    <a href="2010.html">2010</a>
    <a href="2006.html">2006</a>
  </div>
</div>
```

Mithilfe von CSS können verschiedene Stile angewendet werden, um das Dropdown-Menü anzupassen. Hintergrundfarbe, Schriftart und Positionierung können zur Anpassung von Schaltflächen und Dropdown-Listen verwendet werden. Pseudoklassen wie :hover können für interaktive Effekte verwendet werden.

```css
.dropdownContent {
  font-size: 25px;
  display: none;
  position: absolute;
  background-color: #3d3d3d;
  width: 121px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
}

.dropdown:hover .dropdownContent {
  display: block;
  border-radius: 5px;
}
```

HTML und CSS bilden die Grundlage für die Erstellung und Anpassung von Dropdown-Menüs. HTML wird verwendet, um die Struktur des Menüs zu definieren und die Optionen festzulegen. Mit CSS wird das Erscheinungsbild mit Farben, Schriftarten und Abständen gestaltet. Die Kombination dieser beiden Technologien ermöglicht es Entwicklern, benutzerfreundliche Dropdown-Menüs zu erstellen, die sowohl funktional als auch visuell ansprechend sind.

![grafik](https://im4.ezgif.com/tmp/ezgif-4-e3e822ddf1.gif)

## Verifikation

* `Textbeschreibung:` Die Textbeschreibung dient zur Verständlichkeit des Codes und des Gifs.

* `Code:` Dieser Code ist die Bewegung unseres Charakteres in unserem Programm.

* `Gif:` Das Video dient zur Demonstration des Programmes.


# Reflektion zum Arbeitsprozess

👍 Bei unserer Arbeit lief gut, das wir durch vorwissen schnell mit dem Programmieren starten konnte.

👎 Bei unserer Arbeit lief nicht gut, aufgrund unzureichender Absprachen bezüglich der Aufgabenverteilung und einer allgemein erschwerten Kommunikationssituation.

**VBV**: Wir sollten besser kommunizieren und unter uns abmachen wer was genau machen soll.

