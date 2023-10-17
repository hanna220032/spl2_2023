# Git commands

## Inhaltsverzeichnis

- [Global config](#schreibeeinpaarglobalconfigvariablen)
- [Master Ordner](#masterordner)
- [Files](#files)
- [Änderungen](#änderungen)
- [Hochladen](#hochladen)
- [Tutorial](#tutorial)



<a name="schreibeeinpaarglobalconfigvariablen"></a>
## Schreibe ein paar Global config Variablen
```
- git config --global user.name "Name"
	- username eingeben
- git config --global user.email "Email"
	- Email eingeben
- git config --list 
	- Überpfüfung
```
![Global config Variablen](./images/git%20config.png?raw=true)

<a name="masterordner"></a>
## Master Ordner
```
- git init
	- um Ordner zu Git-Ordner zu machen
```	
![Master Ordner erstellen](./images/master%20ordner.png?raw=true)

<a name="files"></a>
## Files
```
- git status
	- zeigt den Status des aktuellen files
- git add "file"
	- fügt vorhandene files zu Git zu
- git commit -m "Kommentar"
	- um files bereit zum hochladen machen
```
![Files erstellen](./images/Files.png?raw=true)

<a name="änderungen"></a>
## Änderungen
```
- git diff
	- man sieht ob was im file geändert wird
```
![kann man sehen ob etwas geändeet wurde.](./images/aenderungen.png?raw=true)

<a name="hochladen"></a>
## Hochladen
```
- git remote add origin "link des ersteltlen repositorys"
	-um lokalenordner mit onlineordner zu verbinden
- git push origin master
	- um committed files auf Onlineordner zu laden
```
![Hochladen](./images/hochladen.png?raw=true)

<a name="tutorial"></a>
## Tutorial

[Tutorial](https://www.simplilearn.com/tutorials/git-tutorial/what-is-git)