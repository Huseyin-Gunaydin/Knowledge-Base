# Wichtige Befehle

---

## Git-Befehle

### Git init

Mit dem Befehl git init wird ein neues Git-Repository erstellt

### Git Status

Der Befehl git status gibt den Status des Arbeitsverzeichnisses und der Staging-Umgebung zurück.

### Git Add

Mit dem Befehl git add fügst du eine Änderung aus dem Arbeitsverzeichnis zur Staging-Umgebung hinzu.

### Git commit

Mit dem Befehl git commit erfasst du einen Snapshot der aktuell bereitgestellten Änderungen des Projekts. Committete Snapshots gelten als "sichere" Versionen eines Projekts – Git nimmt an ihnen nur auf explizite Anweisung hin Änderungen vor.

### Git branch

In Git sind Branches Bestandteil deines alltäglichen Entwicklungsprozesses. Git-Branches sind quasi Verweise auf einen Snapshot deiner Änderungen. Wenn du ein neues Feature hinzufügen oder einen Fehler beheben möchtest, legst du einen neuen Branch an, der deine (großen oder kleinen) Änderungen enthält.

### Git Pull

Der git pull -Befehl wird verwendet, um Inhalte aus einem Remote-Repository herunterzuladen und unverzüglich das lokale Repository zu aktualisieren, damit die Inhalte übereinstimmen.

### Git Push

Der Befehl git push wird verwendet, um Inhalte aus einem lokalen Repository in ein Remote-Repository hochzuladen. Per Push überträgst du Commits aus deinem lokalen Repository in ein Remote-Repository.

### Git Clone

Der Befehl git clone dient dazu, ein vorhandenes Repository als Ziel festzulegen und einen Klon oder eine Kopie des Ziel-Repositorys zu erstellen.

### git fetch, git merge, git pull

Es gibt drei git-Befehle, um Änderungen aus dem entfernten Repository abzuholen und mit Ihren lokalen Dateien zu synchronisieren.

- **fetch** holt Änderungen aus dem entfernten Repository, aber wendet diese nicht auf Ihren Code an.
- **merge** synchronisiert per fetch abgeholte Änderungen mit dem Workspace.
- **pull** führt fetch und merge aus. Dadurch werden Änderungen aus dem entfernten Repository abgeholt und mit dem Workspace synchronisiert.

---

## Die 15 wichtigsten Linux-Befehle im Terminal (für Einsteiger)

### pwd

Zeigt das aktuelle Verzeichnis an, in dem wir uns befinden.

### s

Zeigt den Inhalt des aktuellen Verzeichnisses an.

### ls irgendein/pfad

Zeigt den Inhalt des angegebenen Verzeichnisses an.

### ls -l

Listet den Inhalt eines Verzeichnisses mit weiteren Details auf.

### ls -a

Zeigt auch die versteckten Dateien und Verzeichnisse an (versteckte Elemente beginnen mit einem Punkt, z.B.: .ssh).

### ls -lh

Listet den Inhalt eines Verzeichnisses mit weiteren Details auf und formatiert die Dateigrößen in ein besser lesbares Format.

### cd

Wechselt in das Home-Verzeich---

less dateiname
Zeigt den Inhalt einer Datei an. Mit den Pfeiltasten und Bild-rauf/Bild-runter kann durch längere Dateien geblättert werden.
Beenden mit Q.
nano dateiname
Öffnet den Editor "nano", um die Datei zu bearbeiten.
Beenden mit STRG + X. Wenn die Datei verändert wurde, folgt eine Frage, ob gespeichert werden soll. Mit bestätigen J oder N ablehnen, anschließend Dateiname mit ENTER bestätigen. (edited)
nis, wenn kein Pfad angegeben wird.

### cd /irgendein/pfad

Wechselt in das angegebene Verzeichnis. Das / am Anfang bedeutet, dass wir im Hauptverzeichnis beginnen.
Geben wir das / nicht am Anfang an, wechseln wir vom aktuellen Verzeichnis (siehe pwd) in ein Unterverzeichnis.
Wichtige Befehle für das Arbeiten mit Dateien und Verzeichnissen

---

### mkdir verzeichnisname

Erstellt ein neues Verzeichnis mit dem angegebenen Namen.

### touch dateiname

Erstellt eine neue Datei mit dem angegebenen Namen.

### mv quelle ziel

Verschiebt eine Datei von der Quelle zum Ziel. Wird ein anderer Dateiname als Ziel angegeben, kann mv auch umbenennen.

### cp quelle ziel

Kopiert eine Datei von der Quelle zum Ziel. Wird ein anderer Dateiname als Ziel angegeben, wird die Kopie umbenannt.

### cp -r quelle ziel

Kopiert ein Verzeichnis von der Quelle zum Ziel. Mit -r werden alle Inhalte kopiert.

### rm dateiname

Löscht eine Datei. (Achtung, es gibt keinen Papierkorb! Was weg ist, ist weg)

### rm -r verzeichnisname

Löscht ein Verzeichnis. Mit -r wird der gesamte Inhalt des Verzeichnisses gelöscht. Das ist notwendig, da wir das Verzeichnis nur löschen können, wenn es leer ist.
Dateien anzeigen und bearbeiten
