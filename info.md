# Infoanzeige
Hier ist angegeben wie man eine Datei in diesem Falle info.md mit git erzeugen und auf github hochladen kann.

## Mit **Powershell**
erzeuge Dateipfad
installiere Git
erzeuge ssh key

## Mit der **Git Bash**

öffne erzeugten Dateipfad
```
git init
touch info.md
nano info.md
git add info.md
git config --global user.email "your email"
git config --global user.name "your Name"
git branch -M main
git commit -m 'Filename'
```

## Auf der **Github.com** website
den erzeugten ssh key in dem Explorer in einem Unterordner Namens ssh öffnen und in den GitHub-Einstellungen abspeichern
Der ssh Key wird standartmäßig in dem Ordnerverlauf C/Benutzer/user/.ssh abgelegt

## Pushen mit der **Git Bsah**
´´´
git remote add origin Github Dateipfad
git push -u origin main
´´´
