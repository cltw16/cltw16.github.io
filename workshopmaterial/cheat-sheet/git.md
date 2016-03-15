Kommandozeile
=============

Alle Befehle können `--help`  
`man <befehl>` gibt eine Beschreibung/Dokumentation(Manual) des Befehls aus  
`ls` - Auflisten der Ordnerinhalte "list"  
`pwd` - "Print Working Directory" = "Drucke Arbeitsverzeichnis"  
`cd` - "Change Directory" = "Wechsele Verzeichnis"  
`cd ..` - gehe ein Verzeichnis zurück (`.` ist das Aktuelle Verzeichnis, `..` das darüber)  
`find` - alle existierenden Dateien auflisten  
`grep -r "====="` - nach `=====` in allen Dateien Suchen (nützlich bei Merge)  
`firefox index.html &` - mit Firefox die Datei `index.html` im Hintergrund starten (`&`)  
`gedit index.html &` - index.html mit gedit editieren.  
`nano index.html` - `index.html` in der Kommandozeile editieren mit nano  
`vi index.html` - `index.html` in der Kommandozeile editieren mit vi  

Git
===
TODO: Nutzername & email
`git --help` - alle git-Befehle anzeigen. Mach dich damit vertraut   
`git commit --help` - Hilfe zu `commit` anzeigen  
`git add index.html` - index.html dem INDEX hinzufügen  
`git add .` - den momentanen Ordner mit allen Änderungen zum INDEX hinzufügen  
`git add --all .` - alle Dateien, auch gelöscht, in den INDEX tun  
`git remove index.html~` - die Löschung einer Datei auch in den INDEX tun  
`git commit -m"Nachricht"` - Den INDEX zu einer neuen Version machen  
`git commit -am"Nachricht"` - alle von git erfassten Dateien in den Index tun und mit   Nachricht zu neuer Version machen  
`git push` - ins Quellrepository hochladen  
`git push origin master` - in das Repository `origin` in den Branch `master` hochladen    
`git pull` - vom Quellrepository Änderungen runterladen  
`git checkout -b patch-1` - den Branch `patch-1` erstellen und zu diesem branch wechseln. `master` heißt der Standardbranch
`git checkout patch-1` - in den Branch `patch-1` wechseln  
`git branch -a` - alle Branches anzeigen und auf welchem man ist  
`git merge master` - den Branch `master` in den momentanen Branch einpflegen  
**Mergekonflike beheben**  
1. `git status` - Zustand, wie ihn git sieht, anzeigen  
2. die Dateien mit Mergekonflikten editieren, suchen nach `<<<<`, `====`, `>>>>`  
3. `git add` - Dateien hinzufügen  
4. `git commit -m"Nachricht"` - Zusammenführung bestätigen und neue Version machen    
