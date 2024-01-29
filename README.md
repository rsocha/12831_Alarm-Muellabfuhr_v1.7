# 12831_Alarm-Muellabfuhr_v1.7

Logikbaustein für den Gira Homeserver

Zyklus 1 ab Reset in Sekunden bis Warnung. z.B. Reset 0:00 Uhr. Warnung soll um 9:00 Uhr sein. Dann sind es  32400 Sekungen
Zyklus 2 nach ablauf Zyklus 1. z.B. nächste Warnung soll um 19:00 Uhr sein. Dann die Sekunden von 9:00 bis 19:00 Uhr. 36000 Sekunden

Wenn auf den Eingängen 4-8 eine 1 anliegt, wird nach Ablauf den Zyklen der jeweilige Ausgang auf 1 gesetzt.



<img width="728" alt="Alarm-Muellabfuhr" src="https://github.com/rsocha/12831_Alarm-Muellabfuhr_v1.7/assets/9153553/2008ad1a-0864-4790-8600-a2aa93dbb5cd">
