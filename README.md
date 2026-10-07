\# Mein erstes Git Projekt

In der Schule Lernen wir grade Git un den Umgang in der Bash. Unsere Erste Aufgabe ist das Insterllieren und das Erstellen unseres ersten Ordners mit hilfe der Bash Befehle.



* Eins
* Zwei
* Drei





Kontrollfragen:



Was bedeutet „Staging“ in Git?
Staging bedeutet, dass Änderungen für den nächsten Commit vorgemerkt werden.



Wie heißt der aktive Branch direkt nach dem Initialisieren des Repositories?
Der Standard-Branch heißt bei aktuellen Git-Versionen normalerweise main.



Womit kann man sich alle bisherigen Commits anzeigen lassen?
Mit dem Git-Log kann man sich die bisherigen Commits und deren Informationen anzeigen lassen.



Welcher Befehl zeigt den aktuellen Status des Repositories an?
Mit git status sieht man den aktuellen Zustand des Repositories, zum Beispiel welche Dateien geändert, gestaged oder noch nicht
Dateien geändert, gestaged oder noch nicht gespeichert wurden.



Wozu dient die Datei .gitignore?
Die .gitignore legt fest, welche Dateien oder Ordner von Git ignoriert werden sollen. Dadurch werden sie nicht versehentlich zum         Repository hinzugefügt, zum Beispiel temporäre Dateien oder persönliche Einstellungen.





1\. Was ist der Unterschied zwischen Working Directory, Staging Area und Repository?
Working Directory: Hier bearbeite ich meine Dateien.
Staging Area: Hier werden Änderungen für den nächsten Commit vorgemerkt.
Repository: Hier werden die Änderungen dauerhaft gespeichert.



2\. Woran erkennst du, ob ein Merge Fast-Forward war?

Ein Fast-Forward-Merge erstellt keinen neuen Merge-Commit. Der main-Branch wird einfach auf den neuesten Commit von dev weitergesetzt.



3\. Warum kann git merge --ff-only manchmal fehlschlagen?

Der Befehl kann fehlschlagen, wenn main seit der Erstellung von dev eigene neue Commits bekommen hat. Dann ist kein Fast-Forward mehr möglich.



4\. Was ist der Vorteil, Änderungen zuerst auf einem Branch wie dev zu machen?

Die Änderungen bleiben getrennt vom main-Branch. Dadurch kann man Änderungen testen und bearbeiten, ohne den Hauptbranch zu verändern.



5\. Mit welchem Befehl siehst du den aktuellen Branch?

Mit dem Befehl:



git branch



Der aktuelle Branch wird mit einem \* angezeigt.



6\. Mit welchen Befehlen machst du Änderungen sichtbar und dauerhaft?

Mit git status sehe ich die Änderungen.



Mit git add werden die Änderungen für den Commit vorgemerkt.



Mit git commit -m "Nachricht" werden die Änderungen dauerhaft im Repository gespeichert.



Änderung Protokoll:



* Neuen Ordner Hinzugefügt
* in dem Ordner die html mit meinen Daten Bestückt
* und jetzt das erstellen des Änderungs Protokoll

