# Webserver
Script for new users on VPS to have access to web server services

Počiatočné požiadavky:
	Užívateľské konto, ktoré chce využívať webové služby musí byť vytvorené.
	Ak užívateľské konto nie je ešte vytvorené, vytvorte ho cez príkaz:

	$ sudo adduser USER_NAME

	Kde USER_NAME nahradte za uzivatelské meno

	Následne pridelte užívateľovi sudo cez príkaz:

	$ sudo sudo usermod -aG sudo USER_NAME


Obsah skriptu:
	Skript obsahuje príkazy, ktoré vytvoria práva pre užívatela, pridajp mu skupiny a
	vytvoria mu hlavnú podstránku preňho na doméne www.wedevs.sk.
	
Kroky pred spustením skriptu:
	V skripte treba zmenit premennú USER_NAME (meno už existujúceho užívateľa, ktoré musí byť správne)
	 a USER_WEB (meno podtránky, ktorá sa bude nachádzať za doménou ktorá v prehliadači bude vyzerať následovne: www.wedevs.sk/USER_WEB)

Spustenie skriptu:
	Skript spustite príkazom ./webserver

!!!!   V PRIPADE OTAZOK ALEBO ERROR KONTAKTUJE DALIBORA KRALIKA  !!!! 
