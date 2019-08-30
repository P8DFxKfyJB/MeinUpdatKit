# Apple Siri Shortcuts

Hier findest Du Tipps und Anleitungen rund um die App Shortcuts, im Deutschen Kurzbefehle, von Apple.

Apple hat im Frühjahr 2017 die sehr erfolgreiche App Workflow übernommen und zu Siri Shortcuts umgeformt. Die grundlegenden Funktionen wurden beibehalten und um einige schöne Möglichkeiten erweitert.
Seit iOS 12 ist Siri Shortcuts immer populärer geworden und viele helle Köpfe haben die App sehr beliebt gemacht und zu deren Verbreitung in der iOS-Welt beigetragen.
---
### Übersicht meiner bisher hier veröffentlichten Kurzbefehlen

Hier findest du alle meine veröffentlichten Kurzbefehle. Ab August 2019 unterstützt jeder Kurzbefehl UpdateKit. 

[Link zu Meine UpdateKit-Kurzbefehle](Meine-UpdateKit-Kurzbefehle#meine-updatekit-kurzbefehle)

---
### "Wie geht was, wie geht das hier?"

Willkommen zur Rubrik "Wie geht was, wie geht das hier?"

Hier findest du in Zukunft Beispiele, wie das mit den Kurzbefehlen überhaupt funktioniert.

Angefangen mit dem Klassiker "Hello World" über Variablen, Magische Links, Wenn-dann-sonst und viele andere Inhalte aus der Vielzahl der Möglichkeiten. Dabei möchte ich alles so einfach wie möglich halten. Kompliziert machst DU es dann von ganz allein.

[Link zu Meine UpdateKit-Kurzbefehle](Wie_geht_was_wie_geht_das_hier)

---
### Telegram Kanal für Updates zu meinen Kurzbefehlen:

[Link zum Telegram-Kanal](https://t.me/SC_Updates_Gwadro)

Einen Chat für Fragen und Anregungen zu meinen Kurzbefehlen findest du dort auch.

## Grundlegende Infos zu UpdateKit
---
### Was ist UpdateKit?

UpdateKit überprüft alle unterstützten Kurzbefehle auf eventuell vorliegende Aktualisierungen ohne Zutun des Benutzers.

Installiere UpdateKit (Link steht weiter unten) und starte den Kurzbefehl. Dabei wird das Sprach-Setup durchgeführt, UpdateKit ist mehrsprachig, und der Kurzbefehl ist einsatzbereit.

Setze in meinen Kurzbefehlen in den Einstellungen jedes Kurzbefehles "UpdateKit" auf  "1" und das "Update-Intervall" setzt du je nach Belieben auf einen Wert deiner Wahl.
- Standard ist 7 für 7 Tage. Dieser Wert ist voreingestellt.
- Setze den Wert auf 0 (Null) und UpdateKit wird  bei jedem Durchlauf auf ein vorliegendes Update prüfen.

Mit Update-Intervall = 0 kannst du auch vor Ablauf der eingestellten X Tage auf ein Update prüfen lassen ohne irgendwelche Dateien zu löschen oder in den Untiefen des Kurzbefehles Änderungen vornehmen zu müssen.

*Das bietet sich besonders in der Entwicklungsphase eines Kurzbefehls an, wenn es mehrere Änderungen an einem Tag gibt.*

![UpdateKit Setup](images/UpdateKit-Setup.png)

---
### Du möchtest Du UpdateKit nicht benutzen?

 Kein Problem, setze UpdateKit auf 0 (Null). Dadurch wird der entsprechende Abschnitt im Kurzbefehl ignoriert.

Um trotzdem über vorhandene Updates informiert zu bleiben kannst du den Telegram-Kanal zu meinen Kurzbefehlen abonnieren. Den Link dazu findest du weiter unten auf dieser Seite.

Den Link zum Kurzbefehl "UpdateKit" findest du hier:

[UpdateKit For Apple Shortcuts, by Mike Beasley](https://www.mikebeas.com/updatekit/)

Es gibt auch eine Dokumentation dazu:

[Vollständige Dokumentation](https://www.mikebeas.com/updatekit/docs/)

---
### Ablauf des Ganzen

Die Funktion **UpdateKit** wird am Ende eines Kurzbefehles aufgerufen. Das vermeidet eine Unterbrechung der Benutzererfahrung während der Verwendung eines Kurzbefehles.

Dies geschieht erstmals, wenn du den Kurzbefehl zum ersten Mal startest. Dabei wird das aktuelle Datum festgehalten. Beim nächsten Start dieses Kurzbefehles wird das aktuelle Datum mit dem Datum der letzten Überprüfung abgeglichen. Wenn die Anzahl der Tage den einstellbaren Schwellenwert (Update-Intervall) überschreitet, wird der Kurzbefehl **UpdateKit** gestartet und dieser such nach einem Update für den **eigentlichen** Kurzbefehl, der vom Benutzer gestartet wurde.

Liegt ein Update vor, erhältst du ein Hinweis darauf und hast folgende Auswahl:

+ Installieren
+ Änderungen anzeigen
+ Ignoriere dieses Update dauerhaft
+ Später erinnern / Du wirst bei der nächsten Überprüfung erneut erinnert.

---
## Kontakt und Support

### Telegram Kanal für Updates zu meinen Kurzbefehlen

[Link zum Telegram-Kanal](https://t.me/SC_Updates_Gwadro)

Einen Chat für Fragen und Anregungen zu meinen Kurzbefehlen findest du dort auch.

### Forum auf apfektalk.de

[Unterforum auf apfeltalk.de](https://www.apfeltalk.de/community/threads/apple-kurzbefehle-hilfe-anleitungen-kfka.533890/) Dort haben wir einen eigenen Bereich für Shortcuts/Kurzbefehle, schau einfach mal vorbei.

Es gibt auch eine kleine [Sammlung von Kurzbefehlen](https://www.apfeltalk.de/community/threads/sammlung-nuetzlicher-kurzbefehle.534621/) dort. Nichts aufregendes, sondern mehr aus den Anfängen, als Workflow / Shortcuts populär wurde.
