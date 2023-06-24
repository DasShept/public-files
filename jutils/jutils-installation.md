# Installieren von JUtils

## Server aufsetzen
Um den Server aufzusetzen, werden wir hier `mcserv` verwenden.
 

**Dafür werden wir es als erstes installieren:**

1. Gehe in dein Terminal indem du `Win + R` drückst, `cmd` eintippst und Enter drückst.
2. Installiere `mcserv` indem du nun `winget install mcserv` eintippst und Enter drückst.

![Installation von McServ](https://i.ibb.co/hm5HvND/image.png)


**Nun erstellen wir deinen Server:**

1. Tippe `mcserv` ein und drücke Enter.
2. Wähle bei der ersten Frage mit den Pfeiltasten `Neuen Server erstellen` aus und drücke Enter.
3. Gebe bei `Zielverzeichnis` einen Pfad ein, in dem dein Server erstellt werden soll, also bspw. `C:\Users\DEINNAME\Desktop\jutils-server`
4. Wenn dort nun steht, dass der Pfad nicht existiert, dann tippe `y` ein, damit der Pfad erstellt wird.
5. Wähle bei `Server Distribution auswählen` mit den Pfeiltasten `Paper MC (Recommended)` aus und drücke Enter
6. Akzeptiere die Minecraft EULA, indem du bei der nächsten Frage `y` eintippst
7. Wähle bei der `Server Version` die aktuelle Version `1.20`
8. Wähle bei `Unterversion` die Version `1.20.1`
9. Wähle bei der `Java Version` eine bestehende Version aus oder installiere eine neue, indem du `Install a new JRE` auswählst (wähle ggf. Java 17)
10. Warte, bis die Installation beendet wurde

![Erstellen eines Servers mit McServ](https://i.ibb.co/tC4tfhs/image.png)


**Server das erste Mal starten:**

1. Öffne den Dateiexplorer und wechsle in das Verzeichnis, dass du in Schritt 2 eingegeben hattest
2. Mache dann einen Doppelklick auf die `start.bat`
3. Warte nun, bis der Server vollständig gestartet ist. Tipp: Du kannst das daran erkennen, dass `Done (xx.xxxs)!` in der Konsole steht
4. Stoppe den Server jetzt wieder, indem du `stop` in die Konsole eingibst und Enter drückst


## JUtils auf dem Server installieren
Wenn sich die Konsole wieder geschlossen hat, wird es Zeit, JUtils zu installieren:

1. Lade dir die aktuelle Version aus dem Discord-Server herunter, indem du in #download auf den Button drückst
2. Wenn auf dem Button gedrückt hast, lädt sich in deinem Browser eine Datei mit dem Namen `jutils-1-x-x-RELEASE.jar` herunter. Speichere diese in ein Verzeichnis deiner Wahl
3. Kopiere nun die neu heruntergeladene Datei in den `plugins`-Ordner im Pfad, in dem sich auch die `start.bat` befindet
4. Starte nun den Server wieder, indem du einen Doppelklick auf die `start.bat` machst
5. Wenn dein Server wieder gestartet ist, ist JUtils installiert und du kannst deine Lizenz verifizieren

---
Nun solltest du JUtils ohne Probleme verwenden können. Falls du Fragen oder Probleme hast, melde dich gerne auf unserem [Discord-Server](https://dasshept.de/dc).
Vielen Dank, dass du JUtils verwendest!
