# Spielwiese
Repository zum erklären und üben des GitHub Workflow

# Wichtige Begriffe
## Repository
Das **Repository (Repo)** ist die Sammlung aller verwalteten Dateien. Sozusagen das Projekt.
## Branch
Ein **Branch** ist ein Abzweig innerhalb des Repositories. Branches bestehen paralell zum *main* branch dem Hauptpfad des Repositories. Innerhalb eines branch können Änderungen vorgenommen werden, ohne dass der Hauptpfad von diesen betroffen ist. Ist die arbeit an einem Branch beendet kann dieser in den Hauptpfad integriert werden. Somit bleibt die integrität des Hauptpfades bestehen.
## Commit
Ein **Commit** ist die Aufnahme/Bekanntmachung der Änderungen in das Repo/den Branch. Änderungen die nicht commited wurden sind anderen nutzern nicht bekannt werden bei einem Update der lokalen Kopie verworfen. Wichtiger Bestandteil eines **Commits** ist eine kurze aber Ausagekräftige Beschreibung.
## Pull Request
Der **Pull Request** ist die Anfrage zur Übernahme der Änderungen in den Hauptpfad. Dieser dient auch als Grundlage zur diskussion über die vrogeschlagenen Änderungen. Der **Pull Request** muss nicht zwangsläufig "fertig" sein.
## merge
**mergen** ist das zusammenführen zweier Branches, meist eines Arbeitsbranch in den Hauptpfad.
## Clone
Ein **Clone** ist eine lokale Kopie eines Repositories.
## Fork
Ein **Fork** ist eine Abspaltung einens Repositories in ein eigenständiges Repository. Meist werden **Forks** genutzt um entweder einem Repository beizutragen für welches man keine schreibrechte hat, oder um ein Repositorie in eine andere Richtung weiter zu entwickeln als es für das Quell-Repo vorgesehen ist.
## push
**pushen** ist das hochladen der Änderungen in der lokalen Kopie auf das Repository.
## fetch
**fetchen** ist das updaten der lokalen Kopie auf den Stand des Repositories.

# Der Workflow
0. Ein Repository erstellen
1. **clone** - eine lokale Kopie des Repositories erstellen
2. **branch** - einen (ab)Zweig erstellen
3. Änderungen werden innerhalb des erstellten Zweigs vorgenommen
4. **commit** - Änderungen aufnehmen
5. **push** - den Branch und damit die Änderungen von der lokalen Kopie auf GitHub hochladen
6. **Pull Request** - die übernahme des Branches in den *main* branch anfragen
7. **merge** - den Branch in den *main* branch übernehmen/integrieren
8. Branch löschen
9. **update** - lokale Kopie auf den neusten Stand bringen

# Links
* [GitHub Desktop](https://desktop.github.com/) - Software mit grafischer Oberfläche zur Verwaltung von Repositories
* [GitHub CheatSheet](https://training.github.com/downloads/de/github-git-cheat-sheet/) - Kurzübersicht zu Git und GitHub
* [Markdown CheatSheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) - Kurzübersicht zur Markdown Language von GitHub
* [GitIgnore HowTo](https://www.pluralsight.com/guides/how-to-use-gitignore-file) - Kurzübersicht zu .gitignore