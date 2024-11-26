# GitUebung
# Git

## Was ist Git?  
Git ist ein verteiltes Versionskontrollsystem, das von Linus Torvalds im Jahr 2005 entwickelt wurde. Es wird verwendet, um Änderungen an Dateien, vor allem im Bereich Softwareentwicklung, zu verfolgen und zu verwalten.  

## Wofür kann man Git verwenden?  
- Verwaltung von Quellcode-Projekten  
- Zusammenarbeit im Team  
- Rückverfolgung von Änderungen  
- Erstellen von verschiedenen Entwicklungszweigen (Branches)  
- Versionshistorie speichern und vergleichen  

[Mehr zu Branches](branches.md)  
[Linksammlung zu Git und Markdown](links.md)

## Wichtige Git-Befehle  

| **Befehl**                     | **Beschreibung**                                                                 |
|---------------------------------|---------------------------------------------------------------------------------|
| `git init`                     | Erstellt ein neues lokales Git-Repository.                                      |
| `git clone <URL>`              | Klont ein bestehendes Repository (remote/local) in ein Verzeichnis.             |
| `git status`                   | Zeigt den Status der Arbeitskopie an (z. B. geänderte Dateien).                 |
| `git add <Datei>`              | Fügt Änderungen zur Staging-Area hinzu (für den nächsten Commit).               |
| `git add .`                    | Fügt alle Änderungen im aktuellen Verzeichnis zur Staging-Area hinzu.           |
| `git commit -m "Nachricht"`    | Speichert die Änderungen in der Historie mit einer Beschreibung.                |
| `git push`                     | Überträgt Commits aus der lokalen auf die Remote-Branch.                        |
| `git pull`                     | Holt die neuesten Änderungen aus der Remote-Branch und führt sie zusammen.      |
| `git log`                      | Zeigt die Commit-Historie an.                                                   |

---


### Repository initialisieren
```
git init
```

### Änderungen hinzufügen
```
git add <datei> oder git add .
```

### Commit erstellen
```
git commit -m "Beschreibung der Änderungen"
```
### Änderungen zu einem Remote-Repository hochladen
```
git push
```

### Änderungen vom Remote-Repository herunterladen
```
git pull
```

### Status des Arbeitsverzeichnisses anzeigen
```
git status
````

### Log der letzten Commits anzeigen
```
git log
```

## Inhalte

- [Branches in Git](branches.md): Eine Beschreibung von Branches und deren Verwendung.

-Hier findest du die Dokumentation und hilfreiche Ressourcen.

- [Nützliche Links](links.md) - Eine Sammlung hilfreicher Links zu Git, Markdown und mehr.
# Review

Dieses Projekt wurde von Jevgenia Schlovic am 26.11.2024 überprüft.

Ich lade dich ein, mein Projekt zu klonen und es zu überprüfen. Du findest es hier:
[GitHub](https://github.com/masumeh-amiri/GitUebung.git)

## Schritte zum Klonen:
1. Öffne dein Terminal oder Git Bash.
2. Wechsle zu einem Verzeichnis, in dem du das Projekt speichern möchtest (aber **nicht** in deinem aktuellen Projektordner).
```
git clone https://github.com/masumeh-amiri/GitUebung.git
cd repository
```




