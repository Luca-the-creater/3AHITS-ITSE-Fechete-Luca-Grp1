# Arbeitsbericht vom 13.10.2026

- Thema: Installation
- Name: Fechete Luca
- Klasse: 3AHITS Gruppe 1
- Fach: ITSE Übungen

# 

# Einleitung für Kali & Metasploitable 

## Kali Virtuelle Maschine

1. Instaliere den Ordner von Lehrer.
2. Extrahiere die Datei Kali-linux-2025 in einen neuen Ordner ihn Dokumenten liste und bennene den 3AHITS_[ihn welcher gruppe du bist].
3. Öffne VMare und wenn dir eine Meldung kommt mit licens dan drücke auf free wenn noch eine Meldung kommt drücke auf skip.
4. Drücke auf open Virtuele Masin und öffne die Datei die man Extrahirt hat Kali-linux-2025, drücke auf die Virtuelle Maschine.
5. Starte die Maschine.
6. Benützer: kali || Passwort: kali
7. Öffne den Terminal und ändere die Tastatur mit den befehl ```sh setxkbmap de```
8. Instaliere Visuall Studio mit den Befehl der Lehrer ```wget -O vscode.deb "https://code.visualstudio.com/sha/download?build=stable&os=linux-deb-x64"``` und dann den Befehl ```sudo apt update```
9. Mache ein Update mit den Befehl ```sh sudo apt install ./vscode.deb```
10. Lösche die Datei vscode.deb mit den befehl ```rm vscode.deb```
11. ffne GitHub und Melde dich an, ändere den Repository von ```2HITS-ITSI-GRP1``` ihn ```3AHITS-ITSE-GRP1```
12. orpier den link und wechsle wieder zu den Terminal, clone den Repository ihn den Terminal mit denn Befehl ```git clone [Link]```
13. Öffne den Verzeichnis mit den Befehl ```cd 3AHITS-ITSE-Fechete-Luca-Grp1```.
14. Öffne Visual Studio mit den Befehl ``` code .```
15. Gib ihn den Terminal die Befehle aus um dir ein Benützer und die Email zu machen ```git config --global user.name "[dein Benützer]" ``` ```git config --glabal user.email "deine email adresse"``` (all die sahen müssen von der schule sein).

Hinweis: Mit den befehl ```ifconfig eth0``` zeigt er dir die ip addresse.

## 

## Metasploitable

1. Öffne die datei genau so wie bei kali Benützer: msfadmin || Passwort: msfadmin
2. Ändere die tastatur durch den befehl ```sudo loadkey de```
3. Mit den befehl ```ifconfig eth0``` zeigt er dir die ip addresse von eth0.


##

## Zusammen

Schau ob die beiden Maschinen sich gegenseitig pingen
