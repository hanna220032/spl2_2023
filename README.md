#Git commands

##Inhaltsverzeichnis

- [Global config] (#Schreibe ein paar "Global config" Variablen)
- [Master Ordner] (#Master Ordner)
- [Files] (#Files)
- [Änderungen] (#Änderungen)
- [Hochladen] (#Hochladen)
- [Tutorial] (#Tutorial)



<a name="Schreibe ein paar "Global config" Variablen"></a>
## Schreibe ein paar "Global config" Variablen
```
- git config --global user.name "Name"
	- username eingeben
- git config --global user.email "Email"
	- Email eingeben
- git config --list 
	- Überpfüfung
```
	[Global config Variablen](https://github.com/hanna220032/spl2_2023/blob/master/README/git%20config.png?raw=true)

<a name="Master Ordner"></a>
## Master Ordner
```
- git init
	- um Ordner zu Git-Ordner zu machen
```	
	[Master Ordner erstellen](https://github.com/hanna220032/spl2_2023/blob/master/README/master%20ordner.png?raw=true)

<a name="Files"></a>
## Files
```
- git status
	- zeigt den Status des aktuellen files
- git add "file"
	- fügt vorhandene files zu Git zu
- git commit -m "Kommentar"
	- um files bereit zum hochladen machen
```
	[Files erstellen](https://github.com/hanna220032/spl2_2023/blob/master/README/Files.png?raw=true)

<a name="Änderungen"></a>
## Änderungen
```
- git diff
	- man sieht ob was im file geändert wird
```
	[kann man sehen ob etwas geändeet wurde.](https://github.com/hanna220032/spl2_2023/blob/master/README/aenderungen.png?raw=true)

<a name"Hochladen"></a>
## Hochladen
```
- git remote add origin "link des ersteltlen repositorys"
	-um lokalenordner mit onlineordner zu verbinden
- git push origin master
	- um committed files auf Onlineordner zu laden
```
	[Hochladen](https://github.com/hanna220032/spl2_2023/blob/master/README/hochladen.png?raw=true)
<a name "Tutorial"></a>
## Tutorial

	[Tutorial](https://www.simplilearn.com/tutorials/git-tutorial/what-is-git)