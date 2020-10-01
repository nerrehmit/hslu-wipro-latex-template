# Dokumentationsvorlage WIPRO HSLU

Die Vorlage entstand aus persönlichem Bedarf im HS20.

Ich übernehme keine Verantwortung für Vollständigkeit und/ oder Richtigkeit der Vorlage.

## Setup

Zitiert wird nach dem APA Standard.

Formatvorgaben etc. entsprechen dem HSLU Standardwerk "Wissenschaftliches Arbeiten" von Balzert.

## Mithelfen

Pull Requests, Issues, Vorschläge etc. sind immer gerne gesehen.

## Nutzung

Du kannst die Vorlage so nutzen oder auch nach deinen Bedürfnissen abändern.
Benutz für deine Änderungen doch einen Fork damit deine Mitstudierenden ebenfalls davon profitieren können.

Die MIT Lizenz erlaubt es dir den Sourcecode (das Template) zu benutzen und die daraus resultierende Arbeit nicht zu veröffentlichen. Das ist explizit so gewählt das auch Arbeiten umgesetzt werden können die ggf. vom Wirtschaftspartner nicht zur Publikation inkl. Sourcecode freigegeben sind.

## PDF bauen lassen

### Gitlab
Du findest im Ordner `automation` ein `.gitlab-ci.yml`. Wenn du das ins Hauptverzeichnis von deinem Projekt verschiebst wird im HSLU Gitlab automatisch bei jedem Push von einem Gitlab Runner das PDF gebaut und als Artefakt zum Download bereitgestellt.

### Github
Hast du dein Projekt auf Github wird automatisch bei einem Push oder einem Mergerequest ein PDF durch eine Github Action gebaut und ebenfalls als Artefakt zum Download bereitgestellt.
Danke an @florianbaer für dieses Feature!

## Offene Punkte/ ToDo's

- Die Kopf- und Fusszeilen entsprechen noch nicht den Anforderungen der HSLU.
- Bilder/ Abbildungsverzeichnis hat noch kein Example
- Tabellen-(Verzeichnis) hat noch kein Example
- Literaturverzeichnis hat noch kein Example
