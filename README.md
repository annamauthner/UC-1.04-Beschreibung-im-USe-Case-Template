# Use Case - Alarm bei Leistungsabweichung
## Name und Identifikationsnummer
UC 1.04 - Alarm bei Leistungsabweichung
## Beschreibung
Überwachung der Leistungsparameter des Probanden während des Leistungstests. Wenn die Leistung des Probanden signifikant von erwarteten Werten abweicht, wird ein Alarm ausgelöst.
## Beteiligte Aktuere
System, Proband/in
## Status
In Arbeit
## Verwendete Anwendungsfälle
- UC 1.01 - Proband/in anlegen
- UC 1.02. - Leistungstest anlegen
- UC 1.03. - Alarm bei zu hoher Herzfrequenz
- UC 1.07. - Abbruch des Leistungstests
## Auslöser
Leistungsabweichung des Probanden während des Leistungstests.
## Vorbedingungen
Der Leistungstest wurde gestartet, das System ist ordnungsgemäß konfiguriert und die Leistungsparamter des Probanden werden überwacht.
## Invarianten
Aufzeichnung der bis zum Abbruch erhobenen Daten.
## Nachbedingung / Ergebnis
Ein Alarm wird ausgelöst und das Überwachungssystem informiert den/die Diagnostiker/in über die Leistungsabweichung.
## Standartablauf
1. Das System überwacht die Leistunhgsparameter des Probanden durchgehend während des Tests
2. Weichen die Leistungsparameter signifikant von den erwarteten Werten ab, wird ein Alarm ausgelöst
3. Der Alarm wird angezeigt und der/die Diagnostiker/in erhält die Information über die Leistungsabweichung
## Alternative Ablaufschritte
- Wenn die Leistunhgsparameter innerhalb der erwarteten Werte bleiben, wird kein Alarm ausgelöst und der Leistungstest wird fortgesetzt
- Bei Fehlern im Test wird der/die Diagnostiker/in informiert und kann entsprechende Maßnahmen ergreifen
## Hinweise
Die genauen Kriterien für Leistungsabweichungen können individuell an den Probanden angepasst werden.
## Änderungsgeschichte
Version: 0.01; Datum: 17.03.2024; Autor: Anna Mauthner
