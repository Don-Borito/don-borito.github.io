---
Layout: post
Title: Gruppenarbeit Vokabelabfrage per .csv Datei
---

# Gruppenarbeit Vokabelabfragesystem

## Aufgabenstellung

An der BBBaden hatten wir den Auftrag ein Vokabelabfragesystem zu programmieren. Dieses Programm soll Vokabeln aus einer Datei abfragen um zu üben. Bei falschen Antworten soll das Wort erneut gefragt werden.

### Ziele:
1. Der Benutzer kann die Vokabeln übersetzen.
2. Die Eingaben werden geprüft und falsche werden später erneut gefragt.


## Inhalt Nr.1
Für den Anfang möchte ich hier den Teil meines Codes Zeigen, der die Eingaben mit den Daten aus der Datei vergleicht. Denn diese Funktion gehört zu den Herzstücken des Programms und ich das neu gelernt habe.
```
    Console.WriteLine("" + italien[random] + "");
    string answer = Console.ReadLine();
    if (answer == german[random])
    {
        Console.ForegroundColor = ConsoleColor.Green;
        score = score + 1;
        all = all + 1;
        Console.WriteLine("Richtig!");
        corrects[random] = "richtig";
        Console.ForegroundColor = ConsoleColor.White;
    }
    else if (answer == "stop")
    {
        all = 50;
    }
    else if (answer != italien[random])
    {
        Console.ForegroundColor = ConsoleColor.Red;
        Console.WriteLine("richtige Lösung:" + italien[random] + "");
        score = score - 1;
        Console.ForegroundColor = ConsoleColor.White;
    }
```

## Inhalt Nr.2
Als eigene Anforderung haben wir uns auch vorgenommen die Rückgaben in farbiger Schrift zu programmieren.

[![code](https://snipboard.io/7nqWZF.jpg)](https://snipboard.io/7nqWZF.jpg)
## Inhalt Nr.3

Zusätzlich möchte ich noch ein [Video](https://youtu.be/s2Fcle4nVS8) vom Gameplay zeigen.

## Reflexion und Verifikation

### Reflexion:
Unser Programm ist abgeschlossen mit allen Anforderungen und Funktioniert einwandfrei. 
Ich habe neu gelernt wie man Daten aus .csv Dateien verwendet. Und habe meine Fähigkeiten mit if Funktionen verbessert.
Am Anfang hatten wir ein paar Probleme mit dem Zusammenfügen des Codes, da wir alle verschiedene Vorstellungen hatten und jeder seine eigene Art hat. Doch dieses Problem wurde mit der Zeit beseitigt.

Verbesserungen: Wir hätten am Anfang besser planen sollen da es nicht eine Einzelarbeit ist, in der man schnell den Plan ändern kann, falls es nicht passt. Denn es gab verschieden Sachen die vor anderen gemacht werden mussten, was wir nicht bedacht haben.

### Verifikation:
Meine Ziele habe ich erreicht:

Ziel 1: ✔ Der Benutzer kann die Vokabeln übersetzen.

Ziel 2: ✔ Die Eingaben werden geprüft und falsche werden später erneut gefragt.
