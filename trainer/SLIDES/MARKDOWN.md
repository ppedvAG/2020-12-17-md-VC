# MARKDOWN #

## GETTING STARTED ##

### IDEA OF MD ###

`#md` `#markdown`

WAS IST MARKDOWN

- Präprozessor für html
- MD text can be converted to xhtml / html

WOZU IST MARKDOWN

- a way to write simple to read text

---

### STARTING LINKS ###

HOMEPAGE <https://daringfireball.net/projects/markdown/>

WIKIPEDIA <https://en.wikipedia.org/wiki/Markdown>

ONLINE EDITOR <https://daringfireball.net/projects/markdown/dingus>

MD-Anleitung auf GitHub <https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf>

MD-Anleitung von VSCode <https://code.visualstudio.com/docs/languages/markdown>

Achtung: nicht alles, was der offizielle Editor (Compiler) unterstützt, wird auch in GitHub unterstützt

### STARTING TOOLS ###

VSCode (am besten)

VSCode hat eingebautes Preview für MD-Dateien
VSCode hat Outlining für MD-Dateien zum besseren Navigieren in der Datei

- Erweiterung Markdown All in One
- Erweiterung markdownlint
- Erweiterung Markdown PDF
  
Visual Studio

- Erweiterung Markdown Editor bringt MD-Preview mit sich

<!-- todo #2 -->

<!-- todo #3 -->

## HEADINGS ##

Format der ersten Überschrift entscheidet, welche Syntax in der aktuellen Datei als Standart gilt. Die anderen Schreibweisen werden als Warnungen markiert.

## LINKS ##

Die Links in VSC sind nicht case-sensitive und funktionieren auch mit Backslash statt Slash.

Auf GitHub sind sie aber case-sensitive und nur mit Slash!

Absolute und relative Links funktionieren sowohl in VSC als auch auf GitHub

Bei relativen Links ist in VSC der Unterschied, dass Slash vor dem Ordner keine Rolle spielt. Für GitHub sind '/spicker/shortcuts.md' und 'spicker/shortcuts.md' zwei verschiedene Links.

VSCode hat gute Intellisense beim Hinzufügen von relativen Links in MD.

<!-- todo #1 -->

Alleinstehende Links: <https://www.typescriptlang.org/>

## FORMATTING TEXT ##

Fett

An der leeren Stelle oder mit dem vorherigen Selektieren vom Text

`**fett**` => **fett**

Shortcut: `ctrl` + `B`

wird kompiliert zu: ``

---

Kursiv

_kursiv1_
*kursiv2*

wird kompiliert zu: ``

---

Code

`eject`

wird kompiliert zu: ``

Code-Beispiele

```js
function showCodeBlock() {
    // Text wird eingefärbt wie in einer JS-Datei
}
```

Anstatt js kann man auch andere Programmiersprachen angeben.

---

Notiz

``` md
> notiz
> notiz2
```

> notiz
> notiz2

wird kompiliert zu: ``

## TABLES ##

## CHECKBOXES ##

`- [ ]`

## BILDER ##

`![alt Text](src)`

## MD & CSS ##

Man kann auch eigene Stile hinzufügen, wie zu einer HTML-Datei
GitHub wird sie aber ignorieren, VSCode und PDF nicht

---
---
## PROJEKTE / PRODUKTE AUFGEBAUT AUF MD ##

revealjs - interaktive HTML slides. Ein open source Projekt. Man braucht Kenntnisse in HTML, CSS und JS

- Homepage und Beispiel: <https://revealjs.com>
- GitHub Repo: <https://github.com/hakimel/reveal.js>


slides - dieses Projekt basiert auf revealjs, hat zusätzlich einen graphischen Editor für Benutzer ohne HTML-CSS-JS-Kenntnisse. Dieses Projekt ist proprietär.

- Homepage und Beispiel: <https://slides.com/>


remark - slides (wie PowerPoint), basiert auf md

- Beispiel: <https://remarkjs.com>
- GitHub Repo : <https://github.com/gnab/remark>


rmarkdown - wissenschaftliche Beiträge (mit Diagrammen, Bildern etc). Kostenlos

- Homepage: <https://rmarkdown.rstudio.com/>
- GitHub Repo: <https://github.com/rstudio/rmarkdown>
