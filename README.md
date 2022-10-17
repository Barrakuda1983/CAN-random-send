Das Bash-Script diente zum testen des CAN-Monitor "canmoni" und erzeugt alle 2 Sekunden einen Datensatz mit einer Random Adresse zwischen 100 - 799 + Daten 2; 4; 6; oder 8 Byte. und sendet diese auf der zuvor angegeben  CAN-Schnittstelle.
[Die Funktion wurde mit "RS485 CAN HAT" von Waveshare und mit dem "RS485&CAN Module" von inno-Maker getestet]

Installation:
nach dem download kann die Datei "cansendrandom"
in "/usr/bin/" kopiert und mit "sudo chmod 755 /usr/bin/cansendrandom" ausführbar gemacht werden.
So kann durch Eingabe von "cansendrandom" das Script gestartet werden.