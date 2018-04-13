# TipToi_SUIT_Lara

## Inhalt

* [Projektinfo](#projekt)
* [Was wird benötigt?](#benoetigt)
* [Ziele](#ziele)
* [Codebelegung](#belegung)

## Projektinfo <a name="projekt"></a>

Dieses Projekt ensteht in zusammenarbeit mit der Hochschule für Technik und Wirtschft im Modul Spiele‐ und Interaktionstechniken unter der leitung von Prof. Dr. Markus Wacker

## Was wird benötigt? <a name="benoetigt"></a>

TipToiTool Version 1.8 [https://github.com/entropia/tip-toi-reveng/releases]  

## Ziele <a name="ziele"></a>

**Erweitere das Pixi‐Buch: Wie Lara mit den Fingern sieht**

1. Mehrmaliges Antippen eines Codes ergibt verschiedene Soundfiles (z.B. Hochzählen des Tippen oder Vorlesen des Textes – Info auf welcher Seite des Buches man ist - Beschreibung des Bildes im Buch) Über Variablen lösen: ct.15.08.156‐158_tiptoi.pdf , c_t_Beispiel_für_Tiptoi1508‐156.zip http://tttool.entropia.de Thema KOMPLEXERE ABLÄUFE MIT REGISTERN

2. Oberkategorien (Vorlesen, Beschreibung des Bildes) http://tttool.entropia.de Thema KOMPLEXERE ABLÄUFE MIT REGISTERN https://github.com/entropia/tip‐toi‐reveng/blob/master/templates/WWW_Bauernhof.yaml 

3. Spiel (Suchspiel) Suche folgendes Objekt ct.15.08.156‐158_tiptoi.pdf, c_t_Beispiel_für_Tiptoi1508‐156.zip https://github.com/entropia/tip‐toi‐reveng/blob/master/templates/WWW_Bauernhof.yaml 

4. Würfelspiel (Würfeln) und dann eine Aktion ausgeben (z.B. dazugehöriger Seite aufblättern und antippen) ct.15.08.156‐158_tiptoi.pdf, c_t_Beispiel_für_Tiptoi1508‐156.zip https://github.com/entropia/tip‐toi‐reveng/blob/master/templates/WWW_Bauernhof.yaml https://lists.nomeata.de/archive/tiptoi/2016/001398.html 

5. Start/Stop / Wiederholen des Textes / Nächste Seite Stoppen des Vorlesetextes, Wiederholen des Vorlesetextes

6. Eigene Ideen

## Codebelegung <a name="belegung"></a>
```
Aufgabe 1 = 501
Aufgabe 2 = 502
Aufgabe 3 = 503
Aufgabe 4 = 504

Beschreibung:
    12001 = Seite 1
    12002 = Seite 2
    12003 = Seite 3
    12004 = Seite 4
    12005 = Seite 5
    12006 = Seite 6
    12007 = Seite 7
    12008 = Seite 8
    12009 = Seite 9 
    12010 = Seite 10 
    12011 = Seite 11
    12012 = Seite 12
    12013 = Seite 13

Suchaufgaben:
    12022 = Bobbycar finden
    12023 = Bühnebild finden
    12024 = Rechenschieber finden
    12025 = Schwein finden
    12026 = Skadeboard finden
    12027 = Bobbycar
    12015 = Bühnebild 1
    12016 = Bühnebild 2
    12017 = Bühnebild 3
    12018 = Bühnebild 4
    12019 = Rechenschieber
    12020 = Schwein
    12021 = Skadeboard
    
Sonstige:
    10208 = Moduswechsel[502], Zufallsaufgabe[504], Alle Text durch nacheinander Berühren abspielen[501]
    10202 = Alle Texte abspielen[501]
