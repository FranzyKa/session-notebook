# GitHub & Markdown – Session Notes

## 🌿 Git Branches – Grundkonzept

- Branches ermöglichen paralleles Arbeiten an Features.
- Der `main`-Branch enthält den stabilen, gemeinsamen Code.
- Feature-Branches verhindern Konflikte und ungeprüften Code im main.

---

## 🛠️ Wichtige Git-Commands

### 🔧 Branch erstellen & wechseln

- `git switch -c <branchname>`  
  → erstellt neuen Branch und wechselt direkt dahin
- `git switch <branchname>`  
  → zu bestehendem Branch wechseln
- `git branch`  
  → zeigt lokale Branches
- `git branch -a`  
  → zeigt lokale und Remote-Branches
- `git branch -d <branchname>`  
  → Branch löschen

---

## 💾 Commit Workflow

1. Änderungen prüfen:  
   `git status`
2. Dateien zum Commit hinzufügen:  
   `git add <datei>`  
   oder alle Änderungen:  
   `git add .`
3. Commit erstellen:  
   `git commit -m "Beschreibung der Änderung"`

---

## 🚀 Push & Pull

- Änderungen hochladen (erstmalig für neuen Branch):  
  `git push -u origin <branchname>`
- Weitere Pushes:  
  `git push`
- Neueste Änderungen vom Remote holen:  
  `git pull`

---

## 🔀 Pull Request Workflow (GitHub)

1. Feature-Branch erstellen  
   `git switch -c <branchname>`
2. Änderungen durchführen und committen
3. Branch hochladen  
   `git push -u origin <branchname>`
4. Pull Request auf GitHub erstellen
5. Team um Review bitten
6. Änderungen aus Feedback einbauen
7. PR mergen
8. Im lokalen main aktualisieren:  
   `git switch main`  
   `git pull`
9. Feature-Branch löschen (GitHub & lokal)

---

## ✨ Markdown Basics

### Überschriften

```md
# H1

## H2

### H3
```
