# Following Penguin - Dein treuer Pinguin
Dieser kleine Mod soll zeigen, wie man einen eigenen Mod erstellt und dabei auch Mods anderer Entwickler verwendet.

## Die Datei init.lua
Diese Datei wird bein Start der Spiels geladen und der Code ausgeführt. In dieser Datei registrieren wir einen Befehl zum Erstellen eines Pinguins, dem wir ein paar Eigenschaften geben. Außerdem lassen wir ihn dem Spieler folgen, wenn dieser einen Apfel un der Hand hält.

## Abhängigkeiten
Wir verwenden die Mobs Redo API (mod), mit dem es leicht ist Mobs im eigenen Mod zu implementieren. Da wäre nur ein Hühnchen dabei. Deswegen wird noch der mod mobs_animal verwendet, der auch unseren Pinguin enthält.
In der Datei mods/mobs/api.txt werden viele Befehle und Möglichkeiten des Mods erläutert. Auch in den Dateien mods/mobs_animal/penguin.lua usw. finden sich die voreingestellten Attribute der Tiere.

## Die Datei Konfigurationsdatei mod.conf
Ein mod muss die Datei mod.conf enthalten, in der der Name, eine Beschreibung und Abhänigkeiten des mods von anderen mods angegeben ist.

## Weitere Dateien
* LICENSE.txt - Hier wird die Lizenz unseres Codes angegeben und erläutert.
* README.md - Das ist diese Datei mit Erklärungen für den Nutzer unseres Codes.