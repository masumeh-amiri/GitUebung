# Branches in Git

Ein **Branch** (Zweig) in Git ist eine unabhängige Entwicklungsumgebung, die es ermöglicht, parallel an verschiedenen Features oder Bugfixes zu arbeiten, ohne den Hauptzweig zu beeinflussen. Branches bieten Flexibilität und erleichtern die Versionsverwaltung.

## Warum Branches nutzen?

1. **Unabhängige Entwicklung**: Entwickler können an neuen Features oder Änderungen arbeiten, ohne den `main`-Branch zu beeinflussen.
2. **Code-Qualität sichern**: Änderungen können getestet und überprüft werden, bevor sie in den Hauptzweig integriert werden.
3. **Teamarbeit erleichtern**: Mehrere Teammitglieder können gleichzeitig an unterschiedlichen Features arbeiten.

## Arbeiten mit Branches

### **Branching und Zusammenführen**
| **Befehl**                     | **Beschreibung**                                                                 |
|---------------------------------|---------------------------------------------------------------------------------|
| `git branch`                   | Listet alle lokalen Branches auf.                                               |
| `git branch <branch-name>`     | Erstellt einen neuen Branch.                                                    |
| `git checkout <branch-name>`   | Wechselt zu einem anderen Branch.                                               |
| `git switch <branch-name>`     | Alternativer Befehl zum Wechseln zwischen Branches (moderner).                  |
| `git merge <branch-name>`      | Führt den angegebenen Branch mit dem aktuellen Branch zusammen.                  |
| `git branch -d <branch-name>`  | Löscht einen lokalen Branch (wenn er zusammengeführt wurde).                    |

---


### 1. Erstellen eines Branches

```bash
git branch feature-name

git checkout feature-name
git checkout -b feature-name
```
### 3. Änderungen im Branch speichern
```
git add .
git commit -m "Beschreibung der Änderungen"
```
### 4. Branch in den Hauptzweig mergen
```
git checkout main
git merge feature-name
```
### 5. Branch löschen (optional)

```
git branch -d feature-name
```
### Visualisierung von Branches
Wenn Sie mehr über Branches erfahren möchten, schauen Sie sich dieses YouTube-Video[YouTube-Video](https://www.youtube.com/watch?v=JTE2Fn_sCZs)
 an.


