# Exodus für Kodi -Deutsche Anleitung/ FAQ
- Erstellt für das Orignal xStream Forum [EXODUS]
http://xstream-addon.square7.ch/showthread.php?tid=911

![Exodus logo](https://offshoregit.com/exodus/plugin.video.exodus/icon.png)


- [1. Allgemeines zum Addon](#1-allgemeines-zum-addon)
    - [1.1 Verfügbare Webseiten](#11-verfügbare-webseiten)
    - [1.2 Rechtliche Konsequenzen bei Nutzung](#12-rechtliche-konsequenzen-bei-nutzung)
   
   
- [2. Installation und Konfiguration](#2-installation-und-konfiguration)
    - [2.1 Bezugsquellen zur Installation](#21-bezugsquellen-zur-installation)
    - [2.2 Allgemeine Einstellungen](#22-allgemeine-einstellungen)
    - [2.3 Index Seiten Aktivieren und Deaktivieren](#23-index-seiten-aktivieren-und-deaktivieren)
    - [2.4 Hosterwahl](#24-hosterwahl)
    - [2.5 Konten](#25-konten)
    - [2.6 Untertitel](#26-untertitel)
    - [2.7 Downloads](#27-downloads)
    - [2.8 URL Resolver Konfiguration](#28-url-resolver-konfiguration)
    - [2.9 Trakt](#29-trakt)
    - [2.10 Gemeinsamer gesehen Status in Exodus und xStream](#210-gemeinsamer-gesehen-status-in-exodus-und-xstream)
 
- [3. Bekannte Probleme](#3-bekannte-probleme)
    - [3.1 Fehler bei der Installation](#31-fehler-bei-der-installation)
    - [3.2 URL Resolver Fehler](#32-url-resolver-fehler)
    - [3.3 Beobachtungen und Fehler im Betrieb](#33-beobachtungen-und-fehler-im-betrieb)
  
- [4. Fehlerbericht über Log-Datei](#4-fehlerbericht-über-log-datei)
    - [4.1 Allgemeines zur Log-Datei](#41-allgemeines-zur-log-datei)
    - [4.2 Speicherort der Log Datei](#42-speicherort-der-log-datei)
    - [4.3 Erstellen und Hochladen der Log-Datei](#43-erstellen-und-hochladen-der-log-datei)

    
- [5. Phyton Dateien](#5-phyton-dateien)
    - [5.1 Allgemeines zur .py-Datei](#51-allgemeines-zur-py-datei)
    - [5.2 Bearbeiten einer .py-Datei](#52-bearbeiten-einer-py-datei)
    - [5.3 Speicherort der einzelnen Webseiten (.py Dateien)](#53-speicherort-der-einzelnen-webseiten-py-dateien)



## 1. Allgemeines zum Addon

Exodus ist, genau wie xStream,  ein Video Addon für die Media-Center-Software Kodi. 
Mit Exodus ist es möglich über eine einfache Benutzeroberfläche mehrere Streaming-Seiten zu benutzen, mit denen man Filme und Serien anschauen kann.

Dabei greift Exodus bei Film/Serienauswahl oder einer Suche zuerst auf eine Filmdatenbank zu (z.B.tvdb)zu und zeigt ein Ergebnis an. 

Erst nach der getroffenen Auswahl werden die Anbieter & Hoster durchsucht.

Der Menüaufbau von Exodus ist eigentlich selbsterklärend

Die Menüsprache von Exodus ist jene Sprache, auf die Kodi eingestellt ist

Bei Exodus liegt der Vorteil für viele User darin, dass auch Englisch sprachliche Streams genutzt werden können.

Die Fremdsprachliche Seiten werden jedoch von uns nicht Supportet

Englisches Exodus Forum findet Ihr hier: [Link](https://www.tvaddons.ag/forums/exodus-repository/41161-exodus-add.html)

Unterstützung und Anfragen zu den Deutschen Seiten, Problemen usw. werden derzeit über das xStream Forum abgewickelt.

Ob es ein eigenes deutsches Exodus Forum geben wird, steht momentan noch nicht fest.

### 1.1 Verfügbare Webseiten

| Name           | Domain            | Verfügbarkeit          | Stand      |
|:-------------- |:----------------- | :------------------| :--------- |
|1Kino| 1kino.in| 	funktioniert| 12.01.2017
|Animeloads  	 |anime-loads.org    | funktioniert 	      | 23.02.2017 |
| BurningSeries  | bs.to             | funktioniert           | 12.01.2017 |
| Cine           | cine.to           | funktioniert           | 12.01.2017 |
| DirectDownLoad | ddl.me            | funktioniert           | 12.01.2017 |
| FilmPalast     | filmpalast.to     | funktioniert           | 12.01.2017 |
|Foxx 		 |foxx.to 	     |zur Zeit oft Offline    |19.03.2017 |
| HDfilme        | hdfilme.tv        | funktioniert           | 12.01.2017 |
|iLoad 		 |iload.to 	     |funktioniert	      |	12.01.2017 |
| KinoDogs	 |  kinodogs.to	     | funktioniert	      |28.01.2017|
| KinoX          | kinox.to          | funktioniert           | 12.01.2017 |
|MeinKino 	 |meinkino.to  	     |funktioniert 	      |12.01.2017|
| Movie4k	 |movie4k.to	     |funktioniert 	      |13.02.2017|
|Moviesever	 | moviesever.com    | funktioniert	      |10.02.2017  |
|Netzkino  	 | netzkino.de 	     |funktioniert	      |16.03.2017  |
|Pureanime	 |pure-anime.tv      | Download auf Github    |24.03.2017  |
|Rapidstream	 | rapidstream.to    |Offline 		      | 16.03.2017|
|SerienStream    | serienstream.to   | funktioniert 	      |13.01.2017|
|StreamDream	 | streamdream.ws    | funktioniert 	      |12.01.2017|
| Streamit	 | streamit.ws 	     | funktioniert	      | 17.03.2017 |
|StreamKisteTV	 | streamkiste.tv    | funktioniert	      |12.01.2017  |
|SeriesEver 	 |seriesever.net     |funktioniert            | 12.01.2017|
| Tata           | tata.to           | funktioniert           | 12.01.2017 |
| Video4k        | video4k.to        | funktioniert           | 12.01.2017 |

Empfehlungen und Vorschläge für neue Seiten können über das xStream Forum unter dem Bereich [Sonstiges, Projekt EXODUS](http://xstream-addon.square7.ch/showthread.php?tid=911) angefragt bzw. eingestellt werden.

Die Intergration der eingereichten Seiten ist nicht selbsverständlich und folgt daraufhin auch nicht automatisch. Sowohl das Potenzial der vorgeschlagenen Seite als auch der erforderliche Mehrwert wird geprüft und entscheidet über die Entwicklung eines neuen Site-Plugins.
Grundsätzlich ist jedoch zu erwähnen, dass stätig an der Weiterentwicklung von Exodus und deren Site-Plugins gearbeitet wird.


### 1.2 Rechtliche Konsequenzen bei Nutzung

Nein. Das Addon ermöglicht nur die Nutzung der Streaming-Seiten. Das bloße Streamen hat in Deutschland/Österreich (momentan) keine rechtlichen Konsequenzen
Die meisten Streaming-Seiten speichern keine Zugriffsdaten

Hier ist ein Video von Rechtsanwalt Christian Solmecke, der über das Thema rechtlich aufklärt:

[![Nutzerfragen: Legalität von Streaming, Arbeitszeiten und Bild.de | Rechtsanwalt Christian Solmecke](http://img.youtube.com/vi/cDmvhJrLkmM/0.jpg)](http://www.youtube.com/watch?v=cDmvhJrLkmM)



## 2. Installation und Konfiguration


### 2.1 Bezugsquellen zur Installation

**Das hinzufügen von Exodus über "als Quelle hinzufügen" in Kodi ist NICHT möglich!!!**

Das Video Addon Exodus wird über das  EXODUS Repository installiert (empfohlen). 

Dieses ist hier verfügbar: 

[Download](https://offshoregit.com/exodus/repository.exodus/repository.exodus-1.0.1.zip)

Die Entwicklung und Änderungen in Exodus können auf Github mitverfolt werden, der Download sollte jedoch vom Downloadlink oben durchgeführt werden: [Exodus auf Github](https://dev.tvaddons.ag/tvaddons/plugin.video.exodus/tree/master)

Die Aktualisierung von Exodus erfolgt NUR über das Exodus Repository, so wie bei jedem anderen Repo auch. 
Nach einem Repo Update, werden dann auch neu hinzugefügte Index-Seiten automatisch angezeigt.

Wollt Ihr nicht bis zu einem Update warten, könnt Ihr  die .py Dateien der Index Seiten von [Github downloaden](https://dev.tvaddons.ag/tvaddons/plugin.video.exodus/tree/master/resources/lib/sources_de) und in das entsprechende Verzeichnis kopieren (siehe Kap.5.3)

**Wichtig**

Die Index-Seiten welche so hinzugefügt werden, können sofort verwendet werden, jedoch sind Sie in den Einstellungen (Index-Seiten) NICHT sichtbar. 

Die Sichtbarkeit erfolgt, mit dem nächsten Repo Update!!

**BEACHTE:**

*Beim gesamten Daten Download von Github* gilt es folgendes zu Beachten:

Um eine Korrekte Installation zu Gewährleisten, ist es immer notwendig, den Anhang Master, Beta, Nightly aus den .zip Dateien und dem Unterordner zu entfernen

*Geht wie folgt:*

Die Datei in “plugin.video.exodus-master.zip” umbenennen (quasi das “-master" entfernen)

Dann Datei öffnen (nicht entpacken) mit 7-Zip, WinRAR, WinZIP (oder einem anderen Packer), dort ist ein Ordner zu sehen der z.B. “plugin.video.exodus-master” heißt => auch hier das “-master”
entfernen

Die Zip dann installieren.

Im Exodus Repo ist auch das TVAddons Repo  enthalten. 

Wenn das installiert wird, aktualisiert sich auch der URL Resolver automatisch, wenn es ein URL Resolver Repo-Update gibt 

Es wird übrigens der tknorris URL Resolver Verwendet.

**Tipp:**

Da Exodus und xStream den gleichen URLResolver verwenden, könnt Ihr das Updaten des URLResolvers über xStream machen, sofern xStream installiert ist

Alternativ kann Exodus auch über das Addon Fusion Installer installiert werden, jedoch nicht zu empfehlen da es zu umständlich ist

***WICHTIG:*** Jedoch muss an dieser Stelle klar darauf hingewiesen werden, dass unter der alternativen Bezugsquelle nicht für den aktuellsten Stand und Funktion der Software garantiert werden kann!

Repo Installieren:

- öffne die Kategorie Addons
- aus zip installieren
- Downloadordner suchen und installieren

Nach dem das Repo Installiert wurde ist noch folgendes zu machen:

- öffnet die Kategorie Addons
- Aus Repository installieren
- Exodus Repository
- *Video-Addons*
- Exodus (installieren/aktivieren)
- *Addon Verzeichnis*
  hier TVADDONS.ag Libraries Repository installieren/aktivieren
  (dann wird der URL-Resolver automatisch aktualisiert)

### 2.2 Allgemeine Einstellungen

Wenn gesehene Filme auf einmal weg sind, liegt das an den Einstellungen im Seitenmenü. 
Hier die Markierung „gesehene Filme“ deaktivieren!

In Exodus  Kategorie *WERKZEUGE* öffnen
Hier werden alle Exodus Einstellungen angezeigt

####**Einstellungen Allgemein**

***Erscheinungsbild***

Exuary
Exodus
Genesis

Exodus verwendet ein zugehöriges Artwork Addon für Themen Unterstützung
Das Exodus Artwork Addon wird standardmäßig mit installiert



***Zeitlimit für Index Seiten:***

*Standard (default):* 30 Sekunden

Ist die Zeit, wie lange Exodus die Anbieter durchsuchen soll  bevor das Suchergebniss , als Liste zur Auswahl  angezeigt  wird

Exodus liefert ein exzellentes Ergebnisse mit einem Wert von 12 -  
15 Sekunden, vor allem wenn ihr einen Premium Service verwendet.

Wenn Ihr Schwierigkeiten habt Streams zu finden, kann dieser Wert erhöht werden

***Indikator***

*Standard (default): Lokal*

*Lokal:* der gesehen Status wird innerhalb von Kodi behandelt

*Trakt:* 
wenn Ihr bei dem Menüpunkt *Konto* Euer Trakt Konto aktiviert habt, kann hier auch Trakt ausgewählt werden
Wird Trakt verwendet, dann werden alle gesehen Status  auf der Trakt Homepage gespeichert 

***Sprache für Informationen***

*Standard (default):* Auto

Es wird automatisch die in Kodi verwendete Sprache benutzt
Wenn notwendig, kann die Sprache manuell eingestellt werden

Diese Einstellung kontrolliert die Sprache, welche Angezeigt/Wiedergegeben wird, wenn Exodus Abfragen von Titel, Beschreibungen und andere Metadaten Informationen, für Filme und Serien durchführt
Diese Einstellung bezieht sich nur auf die Informationen für Exodus und hat KEINE Auswirkung auf die Stream Sprache

***Sprache für Index Seiten***

Hier wird die Sprache für die Webseiten Eingestellt, zur Auswahl:

Englisch 

German

German + Englisch

French

French + Englisch

**Serien-Staffeln reduzieren**

EIN: Alle Staffeln werden in einer Liste angezeigt 

AUS: Staffeln werden in eigenen Staffel Ordnern angezeigt

**Fanart verwenden**

*Standard (default):* aktiviert

Wenn Ihr Probleme mit dieser Funktion habt, solltet Ihr überlegen diese zu deaktivieren um zu sehen, ob sich dadurch die Leistung verbessert
Dadurch verliert Ihr natürlich die Bilder und Kosmetische Aspekte. Aber es könnte zur Leistungsverbesserung beitragen

**MENÜ**

*Neue Filme:*

Einstellung, welcher Inhalt angezeigt wird, wenn die Kategorie Neue Filme in Exodus gewählt wird (Im Kino, am populärsten, Empfohlen, Deaktivieren

*Neue Episoden:*

Einstellung, welcher Inhalt angezeigt wird, wenn die Kategorie Neue Episoden in Exodus gewählt wird (Episoden, Deaktiviert)

*Meine Listen:*

wenn aktiviert, wird im Hauptmenü die Kategorie Meine Liste angezeigt. 
Funktion nur mit Trakt Konto (und anderen Konten)

####**Einstellungen Wiedergabe**

**Standard Aktion (default):**  Verzeichnis

*Verzeichnis*

Die Anzeige ist wie eine Liste Aufgebaut

*Dialog*

Die Anzeige erfolgt in einem kleineren Fenster, Aufbau wie eine Liste
 
*Auto-Play*

Es wird keine Liste angezeigt
Die Wiedergabe nach Filmauswahl/Serienauswahl startet automatisch
Es wird der beste verfügbare Hoster & die beste verfügbare Qualität gewählt

Die Auswahlreihenfolge der Hoster richtet sich nach deren Priorität
(und auch Qualität, HD vor SD usw.)

Die Priorität kann im URLResolver unter “Resolver Settings” angepasst werden.

***Niedrige Werte werden vor hohen Werten gewählt***

**Fortschrittsdialog**

Vordergrund: 

nach Streamauswahl wird das Info-Fenster, groß in der mitte des Bildschirmes dargestellt

Hintergrund: 

nach Streamauswahl wird das Info-Fenster, klein am Rand des Bildschirmes dargestellt

**DATEIANBIETER FILTER**

**Höchste Qualität:**

4k, 1440p, 1080p, 720p und 480p stehen zur Auswahl

Das was hier engestellt wird, ist die max. Auflösung nach der die Index-Seiten durchsucht werden. 

Ist auch die max. Auflösung, welche bei Autoplay verwendet wird

Bei Seriesever & Moviesever ist 4k verfügbar, aber nur mit einem Premium Account (Bezahlung)

**SD Anbieter in Autoplay**

*Wenn aktiviert:*

werden im Auto-Play Modus nur SD Streams wiedergegeben. 
HD Streams werden dabei ignoriert. 
Ist nur dann sinnvoll, wenn man einen langsamen Internet Anbieter oder eine schwache Hardware hat

**Dateianbieter mit Captcha Abfrage**

Wenn aktiviert, werden alle Hoster die Captcha-Abfragen durchführen ignoriert

**Nach Index-Seiten sortieren**

Wenn aktiviert, werden nur die Streams der Ausgewählten Anbieter angezeigt.
Premium Services sind immer Gruppiert und stehen  an der Spitze der Liste
Beispiel: Alle Streams, die z.B. auf PrimeWire gefunden werden, sind aufgelistet

***Wenn Wiedergabe startet......***

*Wiedergabe fortsetzen*

Wenn ein Stream gestoppt wird, wird automatisch ein Fortsetzungspunkt gespeichert/erstellt 

(aber erst ab einer Wiedergabezeit von 3 Minuten )

*Option Wiedergabe fortsetzten EIN:*

Es erscheint bei Fortsetzung des Streams eine  Anzeige  wo gewählt werden kann: Fortsetzen oder Vom Anfang abspielen an, egal welcher Hoster dabei gewählt wird

*Option Wiedergabe fortsetzten AUS:*

Stream startet immer vom Anfang (auch wenn Ihr eine advancedsettings.xml verwendet)


Wenn in Kodi unter: 
Addons-Seitenmenü, Automatische Aktualisierung auf AUS gestellt ist, wird Exodus nicht automatisch aktualisiert

**EXODUS: Cache löschen/Index Seiten löschen**

Löscht den Cache (Speicher) von Exodus
Keine Angst, hierbei passiert nichts!!

**Suche**

Die Suche in Exodus ist eine Globale Suche. Das heißt, es werden immer alle Anbieter/Hoster durchsucht

Es kann vorkommen, dass eine Serie/ein Film nicht gefunden wird, näheres dazu siehe Kapitel 3.3

**Kategorie: Meine Filme / Meine TV Serien**

Diese beiden Kategorien sind nur nutzbar, wenn z.B. Trakt aktiviert ist
Hier findet Ihr dann Eure gesehenen Serien/Filme, Filmvorschläge usw.

**EXODUS: Anzeige Typen**
Hier wird die Ansicht (view) eingestellt, wie Filme/Serien/Episoden usw. dargestellt werden (Liste, Wall, InfoWall, Poster usw...)

Diese Ansichten werden in einer eigenen Datenbank gespeichert:

.....kodi\userdata\addon_data\plugin.video.exodus\views.db

Und so stellt Ihr die Ansichten ein:

Exodus Menü -> Werkzeuge ->Angezeigte Typen-> 4 Kategorien (Filme, TV Serien, Staffeln, Episoden)->eine auswählen-> jetzt über Seitenmenü die Ansicht auswählen (Wall, InfoWall, Poster, Fanart usw..) ->Speichern (auf das angezeigte Bild klicken oder auf den Text)->fertig

Nun wird die Ansicht in Exodus so dargestellt, wie sie eben eingestellt wurde

Wollt Ihr die Datenbak zurücksetzen, dann kann sie gelöscht werden

Erklärung zur Datenbank:

*views.db*

speichert eine festgelegte Ansicht über das Exodus Menü, welche bei jedem Seitenaufruf (Pfad: Bsp. Filme -> Trakt -> Sammlung) die - vom Skin in der ViewModes.db gespeicherte -ViewID überscheibt 

Thema: [Link](http://xstream-addon.square7.ch/showthread.php?tid=969)

**Kanäle**

Hier werden Euch Sky Sparten angezeigt

Diese sind jedoch KEINE Live Streams

Die Sparten dienen nur so als Vorschlag was man schauen könnte

Deutscher SkyEPG wird nicht eingebaut, da Exodus International ist und die Vorschläge für alle gleich sind

### 2.3 Index Seiten Aktivieren und Deaktivieren

*Standard:* Alle Index Seiten aktiviert

In Exodus, unter dem Menüpunkt Werkzeuge, *Index-Seiten*, besteht die Möglichkeit bestimmte Seiten an bzw. auszuschalten. 

Ebenso kann jetzt hier eingestellt werden ob Deutsche und/oder Englische Seiten durchsucht werden
Dies kann von Nutzen sein, wenn kein Interesse an bestimmten Medien besteht. 
Diese werden dann auch nicht in der Suche angezeigt.

Einige Index-Seiten unterschützen Multi-Part

Aktuelle sind das ddl.me und Filmpalast

*Was ist MultiPart?*

MultiPart bedeutet: das der Film in zwei Teilen auf der Seite hochgeladen ist und Exodus diese nahtlos nacheinander abspielt

Der Film sollte auch grob in der Mitte mal nachladen, beim Wechsel auf den zweiten Stream. 

Auch beim Start des zweiten Stream etwas langsamer, aber besser so als gar nicht

*Anmerkung*
Wenn Ihr Probleme mit kinox habt, hilft es wenn Ihr Eure DNS (z.B. auf die von Google 8.8.8.8) Adresse ändert. 
Manche Seiten werden von den Internet Providern geblockt 

Nache einem Exodus Update werden auch neu hinzugefügte Seiten automatisch angezeigt. 
Das Update erfolgt aber nur, wenn das Exodus Repo installiert ist, wie am Anfang beschrieben

Im Verzeichnis `...kodi/addons/plugin.video.exodus/resources/lib/sources_de` sind die .py Daten  der einzelnen Webseiten abgelegt.
Hier könnt Ihr auch neue Deutsche Seiten hinzufügen, oder bestehende bearbeiten

Bei diesem Pfad handelt es sich um "versteckte Dateien". 
Diese müssen erst sichtbar gemacht werden

### 2.4 Hosterwahl

Wenn Ihr im Menü z.B. Filme- Jahr- 2017- beliebigen Film auswählen- klickt, werden alle verfügbaren Anbieter/Hoster durchsucht.

Auch nachdem eine Suche gestartet wurde, werden alle verfügbaren Anbieter/ Hoster angezeigt. 

Die Anzeige sieht wie Folgt aus:

BS | OPENLOAD | HD

(Anbieter | Hoster | Qualität)

Die Qualität des Streams kann sein: 4k, HD, SD, CAM usw.

Wie lange das durchsuchen der Hoster dauert hängt von der Einstellung *Zeitlimit für Index Seiten* ab

*Wenn Ihr einen Film/Serie angewählt habt, könnt Ihr ein zusätzliches Menü öffnen:*

am PC: rechte Maus Taste
am Handy/Tablet: langer Druck auf den Film
am FireTV: die Menü Taste drücken

Ist der von Euch gewählte Anbieter/Hoster nicht verfügbar, nimmt Exodus AUTOMATISCH den nächsten, bis ein lauffähiger gefunden wird

***Anmerkung zu den Hostern Openload (HD), TheVideo:***

Wenn Ihr einen dieser Hoster zum Streamen auswählt, erscheint ein Fenster, welches Euch auffordert Eure Gerät zu Pairen.
Das könnt ihr mit ruhigen Gewissen machen.

Ihr müsst im selben WLAN sein wie das zu Pairende Gerät (z.B. FireTV, Apple TV usw.)
Öffnet am Handy/Tablet/PC einen Browser mit der angezeigten Adresse von openload (https://openload.co/pair) bzw. thevideo (https://thevideo.me/pair)
Klickt in dem Kasten bei “Ich bin kein Roboter”
Dann ganz runter und klick auf “Pair”
Das wars.
Dieser Vorgang muss immer wieder Wiederholt werden (nach 4 Stunden oder 5 Streams)

*Warum ist das "pairen" nötig?*
Auf der Homepage muss immer eine Werbung betrachet werden
Da wir ja die Homepage des Hostbetreibers nicht besuchen müssen, entgehen dem Betreiber Werbeeinnahmen. 

Damit dies nicht der Fall ist und die Hoster Exodus so arbeiten lassen, wurde mit den Betreibern diese "pair" Funktion vereinbart.
Durch den klick auf "pair" bekommen die Hoster Ihre Werbeeinnahme.

Für Euch entstehen dadurch KEINE Kosten!!

### 2.5 Konten
In dieser Einstellung, kann der Premium Service konfiguriert werden
Es steht eine Vielzahl an Anbietern zur Verfügung z.B. Trakt, Premiumize, TMDb, IMDb usw
Voraussetzung ist natürlich, dass ein Account/Abo vom jeweiligen Anbieter vorhanden ist

Die Konfiguration der einzelnen Anbieter kann im englischen Formum nachgelesen werden: [Link](https://www.tvaddons.ag/exodus-tips/?utm_campaign=twitter&utm_medium=twitter&utm_source=twitter)

**Trakt einrichten:**
In der Kategorie *Konto* - *Trakt* auf Berechtigung klicken

*Es wird ein Infofenster angezeigt:*

Webseite besuchen: https://trakt.tv/activate
Dort werdet Ihr dann aufgefordert den Code (der in Exodus angezeigt wird)  einzugeben, Continue.

Allow Exodus to use Your Accout (Erlaube Exodus die Verwendung Deines Kontos), YES

WooHoo! Your device is now connected and will automatically refresh in a few seconds.

Zurück in Exodus, steht jetzt bei Trakt Euer Benutzername.
Der Takt Service kann ab jetzt genutzt weren

Weiteres zum Thema Trakt findet Ihr hier: [Link](http://xstream-addon.square7.ch/showthread.php?tid=948)

### 2.6 Untertitel
*Standard (default):* deaktiviert

Um Untertitel zu aktivieren, gehen in den Einstellungen zu Kategorie *Untertitel*
Untertitel aktivieren

Hauptsprache und Zweitsprache wählen
(Es ist jedoch möglich, dass diese Einstellung gelegentlich Funktionslos bleibt)
Während der Stream läuft könnt Ihr nun am unteren Rand, die Untertitel ein/ausschalten

### 2.7 Downloads
Kategorie *Werkzeuge*, Exodus Downloads

Herunterladen aktivieren

Speicherplatz Ordner für Filme bzw. Serien anlegen/auswählen

Zurück zur Film/Serien Auswahl
Einen Film/Serie suchen, Film auswählen.

Wenn dann die Anbieter/Hoste angezeigt werden, das Kontexmenü öffnen

Download wählen

Es öffnet sich ein Fenster, wo der Name des Films und die Dateigröße angezeigt wird

Nach Klick auf Confirm, starte der Download. 
Es wird kurz: *Download in Progress* angezeigt

Ihr findet den Film/Serie dann in Eurem Download Ordner

### 2.8 URL Resolver Konfiguration

Es besteht die Möglichkeit, in den Einstellungen des URL Resolvers die Priorität der Hoster festzulegen also welche Hoster als ersters angezeigt bzw. verwendet werden sollen.

*Da Exodus & xStream den gleichen URL Resolver verwenden, hat diese Einstellung auch Auswirkung auf beide Addons!!*

Exodus probiert automatisch alle verfügbaren Hoster aus, bis ein Stream abgespielt werden kann

Die Auswahlreihenfolge der Hoster richtet sich nach deren Priorität

Diese kann unter “Resolver Settings” angepasst werden

***Niedrige Werte werden vor hohen Werten gewählt***

Sind Eure Priorisierten (Lieblings) Hoster nicht nicht verfügbar, nimmt Exodus den nächsten Hoster der funktioniert

Den URL Resolver findet Ihr in Kodi:

Optionen - Einstellungen - Addons - System Addons - Abhängigkeiten - URL Resolver:  Konfigurieren

Den URL Resolver findet Ihr in Kodi 17:

Einstellungen - System - Addons - Abhängigkeiten verwalten - URLResolver: Konfigurieren

### 2.9 Trakt
Die Einrichtung des Trakt Kontos steht in Kapitel 2.5

*Wollt Ihr nun eine Staffel zur Merkliste hinzufügen, geht das wie folgt:*

Serienstaffel suchen, Kontexmenü öffnen- Trakt Manager
In dem sich nun öffnenden Fenster, könnt Ihr eine Liste wählen, wo die Staffel gespeichert werden soll

**Kategorie:  Meine TV Serien**

In dieser Kategorie, findet Ihr die zuvor angezeigte Liste und somit die von Euch gespeicherte Serie

*Wollt Ihr nun eine Serie zu Takt hinzufügen, geht das wie folgt:*

Serie wählen - Staffel wählen - Episode wählen - Kontexmenü öffnen - In Trakt angesehen klicken

Auf die gleiche Weise, könnt Ihr auch die komplette Staffel als "In Trakt gesehen" wählen

*Wollt Ihr nun einen Film zur Merkliste hinzufügen, geht das wie folgt:*

Das vorgehen ist dabei gleich wie bei den Serien

Film wählen - Kontexmenü öffnen - Trakt manager 

In dem sich nun öffnenden Fenster, könnt Ihr eine Liste wählen, wo der Film gespeichert werden soll

**Kategorie:  Meine Filme**

In dieser Kategorie, findet Ihr die zuvor angezeigte Liste und somit den von Euch gespeicherten Film

*Wollt Ihr nun einen Film zu Takt hinzufügen, geht das wie folgt:*

Film wählen - Kontext Menü öffnen - In Trakt angesehen wählen

*INFO:*
Immer wenn ein Film/Serie in Exodus als gesehen oder "In Trakt gesehen" markieret wird, springt Exodus zum Listenanfang zurück

Das ist leider ein normales verhalten von Exodus und liegt an Kodi 17

Hier müssen an Exodus noch Anpassungen für Kodi 17 vorgenommen werden

Thema: [Link](http://xstream-addon.square7.ch/showthread.php?tid=948)

Auch wenn Trakt nicht genutzt wird in/mit Exodus, benutzt Exodus trotzdem die Suche von Trakt.tv

Ihr könnt auf der Homepage von Trakt.tv, Filme&Serien selbst zur Trakt Datenbank hinzufügen/nachtragen, wenn diese nicht vorhanden sind

Dazu benötigt Ihr die Film oder Serien ID Nummer, welche Euch auf thevdb.com angezeigt wird

Am unteren Ende der Trakt Homepage, findet Ihr das Import Menü für Filme (Import Movie) und Serien (Import TV Show), hier müsst Ihr die ID Nummer eingeben

### 2.10 Gemeinsamer gesehen Status in Exodus und xStream

Exodus benutzt standardmaäßig den metahandler

Wenn dieser auch in xStream aktiviert wurde, dann wird der gesehen Status aus xStream auch in Exodus angezeigt und umgekehrt, weil dann beide Addons in die gleiche Datenbank schreiben

Die Datenbank befindet sich unter:  

.....kodi/userdata/addon_data/Skript.module.metahandler/meta_cache/Video_cache.db

Ihr könnt den "gesehen Status" (wached state) auch exportieren und auf einem anderen System importieren

Ihr müsst dann also nur die oben genannte *video_cache.db* auf ein anderes System übertragen

Thema: [Link](http://xstream-addon.square7.ch/showthread.php?tid=787)

## 3. Bekannte Probleme

### 3.1 Fehler bei der Installation

**Bei der Installation von Exodus erscheint folgende Fehlermeldung**

Installation fehlgeschlagen --> Installation der Abhängigen fehlgeschlagen

- Lösung: Deaktiviert alle Repositorys, welche Exodus anbieten Danach Exodus aus der offiziellen Exodus Repo installieren und alles funktioniert

### 3.2 URL Resolver Fehler

Sollte dies der Fall sein, bitte den aktuellste Version des "URLResolver" über dier folgende Bezugsquellen beziehen:

 https://github.com/tknorris/script.module.urlresolver/archive/master.zip


### 3.3 Beobachtungen und Fehler im Betrieb

**Suche liefert kein Ergebnis, Suche zeigt kein Ergebnis an**

Exodus findet eine Serie oder einen Film bei der Suche nicht,obwohl auf thetvdb die Infos vorhanden sind.

Ein Beispiele: Die Biene Maja 2012

*Wie kann ich die Serien in Exodus finden??*

Die Suche basiert auf Trakt.tv. Trakt nutzt thevdb & imdb Datenbank

Wenn auf Trakt.tv der Film oder die Serie gefunden wird,  findet es auch Exodus

Der Film oder die Serie kann dabei in der Datenbank auch einen Englischen Namen enthalten/haben

Das Beispiel Biene Maja:  wird gefunden wenn es "Maya" geschrieben wird

Auch wenn Trakt nicht genutzt wird in/mit Exodus, benutzt Exodus trotzdem die Suche von Trakt.tv

Des weiteren, könnt Ihr auf der Homepage von Trakt.tv, Filme&Serien selbst zur Datenbank hinzufügen/nachtragen, wenn diese nicht vorhanden sind

Dazu benötigt Ihr die Film oder Serien ID Nummer, welche Euch auf thevdb.com angezeigt wird

Am unteren Ende der Trakt Homepage, findet Ihr das Import Menü für Filme (Import Movie) und Serien (Import TV Show), hier müsst Ihr die ID Nummer eingeben

**Trakt watched Status & Exodus**

einmal in Exodus "mit trakt angesehen" markierte Filme lassen sich nicht mehr als "mit trakt ungesehen" markieren und werden auf trakt.tv aber auch nicht als watched übernommen

Staffeln in Serien lassen sich nicht einzeln als watched oder unwatched markieren. 

Die Markierung einer Staffel als "watched/unwatched" markiert immer gleich alle Staffeln

Lösung: derzeit keine

**Trakt arbeitet sehr langsam/Inhalte werden nur langsam geladen**

Das Trakt langsam lädt liegt leider am Trakt

Es gab keine Änderung an der Trakt-Integration, es liegt daher nicht an Exodus

Das Laden z.B. der Merkliste kann schon mal ein paar Minuten dauern

**Abbruch der Streams/Buffern der Streams während der Wiedergabe**

Gehört eigentlich nicht hier in diese Kategorie da es kein Fehler von Exodus ist

Aber da es oft gefagt wird, bzw. öfters vorkommt steht es eben hier

Wenn der Stream an Kodi übergeben hat, ist die die Sache für Exodus durch/erledigt

Wenn Streams abbrechen/buffern oder ähnliches, ist das ein Problem von Kodi und nicht von Exodus

Was das verursacht müsste man genauer klären, eventuell hilft eine advancedsettings.xml

**Super Favoriten funktioniert nur teilweise mit Exodus**

Bei Filmen gibt es meistens kein Problem mit dem Addon SuperFavoriten.

Bei Serien ist es jedoch so, dass diese in den SuperFavoriten Ordner integriert werden können, jedoch kann der Stream nicht abgespielt werden, es tut sich gar nichts

Mit einem kleinen Trick, behebt Ihr diese Problem. 

*Folgender Vorgang muss nach jedem Exodus Update erneut durchgeführt werden*

Navigiere zu folgendem Ordner: 
(Kap.4.2 steht der ganze Speicherpfad)

...../.kodi/addons/plugin.video.exodus/resources/lib/modules/control.py

Öffne die control.py 

Suche folgenden Eintrag
		 
		  def moderator():

Füge hier folgendes hinzu:

	'plugin.program.super.favourites'

sieht fertig dann so aus:

	def moderator():
    netloc = [urlparse.urlparse(sys.argv[0]).netloc, '', 'plugin.video.live.streamspro',
    'plugin.video.phstreams', 'plugin.video.cpstreams', 'plugin.video.tinklepad', 'plugin.video.metallic',
    'plugin.video.metalliq', 'plugin.program.super.favourites']

Speichern. Nun kann SuperFavoriten ohne Probleme mit Exodus genutzt werden

**Fehlermeldung: "Kein Stream verfügbar"**

Exodus greift bei der  Suche, Film/Serienauswahl zuerst auf eine Filmdatenbank zu (IMDB), fragt diese nach Infos zum Film, zur Serie ab und zeigt diese dann an

In dieser Datenbank sind also nur Informationen zu Filmen/Serien gespeichert und hat noch nichts mit der Verfügbarkeit des Streams/Hoster zu tun

Daher kommt es immer wieder mal vor, dass z.B. die Episode einer Serie (in Deutsch) angezeigt wird und wenn der Stream gestarte werden soll,kommt die Fehlermeldung: 

*"In Exodus kein Stream verfügbar"*

Das ist KEIN Fehler von & in Exodus!!

**Falsche HD/1080p Angaben bei Streams**

Das ist KEIN Fehler von & in Exodus

Einigen Hoster haben falsche Angaben zur Qualität (Auflösung) der Streams, sollte eigentlich nicht mehr vorkommen seit Update 3.1.0

Da steht dann neben dem Hoster HD/1080p obwohl es nur ein SD Stream ist.

Bekannte Hoster wo die Auflösung (Qualität) neben dem Stream meistens falsch ist,da diese keine HD/1080p anbieten:

Streamcloud
Vidto
Vidiz
Flashx

## 4. Fehlerbericht über Log-Datei


### 4.1. Allgemeines zur Log-Datei

In dem log File werden alle Aktivitäten/Programmabläufe von Kodi protokolliert und gespeichert. Wenn man nun Probleme mit Kodi hat, ist es sehr hilfreich, dieses Log File im Forum zu Posten. Nur so kann eine schnelle und Zielgerichtete Lösung erfolgen.


### 4.2 Speicherort der Log Datei

Den Speicherpfad von Kodi anzeigen lassen – Scroll weiter runter zum Punkt Debug_Logging und folgen den Beschreibungen.

Das ist immer vom Betriebssystem abhängig.
Im Folgenden werden bekannte Ordnerstrukturen der jeweiligen Betriebssysteme aufgelistet. Anstelle von "xbmc" kann in den Ordnern auch "kodi" stehen
(die Ordnerstruktur kann jedoch auch leicht von dieser Anleitung abweichen):

- Windows XP
    - `Documents and Settings\<your_user_name>\Application Data\Kodi`
- Vista/Windows 7
    - `C:\Users\<your_user_name>/%APPDATA%/Roaming/Kodi/Kodi.log`
- Mac OS X
    - `/Users/<username>/Library/Logs/ oder`
    - `/Users/<your_user_name>/Library/Application Support/Kodi/userdata`
- iOS
    - `/private/var/mobile/Library/Preferences`
- Linux, OpenElec, Raspberry Pi 1-3
    - `$HOME/.kodi/temp/`
    - `$HOME/.kodi/userdata/temp/xbmc.log`
    - `$HOME/.kodi/userdata`
- Android
    - `/android/data/org.xbmc.Kodi/files/.kodi/temp`
    - `data/data/org.xbmc.Kodi/cache/temp`

Die Ordner sind meist versteckt und müssen sichtbar gemacht werden, im Windows Explorer oder auf Android mit dem ESDateiexplorer.

Das Log File kann am besten mit Notepad++  unter Windows oder gedit unter Linux betrachtet werden.
Auch der normale Texteditor unter Windows geht, Notepad ist aber übersichtlicher.
Auf Android einen Texteditor verwenden zum Betrachten.
Übrigens die Kodi „log.old“ ist die Logdatei vom letzten Neustart/Crash. Also wenn man keine mehr erstellen kann, dann diese nehmen.


### 4.3. Erstellen und Hochladen der Log-Datei

Kodi hat Standardmäßig die beiden wichtigen Log Addons integriert (eines zum Lesen der Log, das andere zum Hochladen). Damit ist das Erstellen der Log Datei und Posten im Forum sehr viel einfacher.

In Kodi gehe zu:

- Addons
- Suche

In die Zeile "log" ein und Klicks auf Fertig.

Folgende Addons auswählen und installieren diese:

Log Viewer für Kodi (nur zum Lesen der Log-Datei)
Kodi Log Uploader (zum Auslesen & Uploaden der Log-Datei)

Mit dem LogViewer kann man die Log Datei ansehen, mit dem LogUploaded das Log-File auf den angezeigten Homepage-Link hochladen, die Anweisungen der Anzeige befolgen

Bei der Installation eine E-Mail Adresse angeben. An diese wird dir dann nach dem LogUpload ein Link zur Log Datei geschickt.
Diesen Link im Forum Posten oder alles in einen Texteditor koperien, Die Datei speicherun und im Forum hochladen.

Debug-Logging (Kodi GUI):

Manchmal ist es gut das Debug Logging in Kodi zu aktivieren um noch mehr Informationen zu erhalten. 
(geht nur wenn, wenn es nicht schon in der advancedsettings.xml akttiviert wurde)

Folgendes Ausführen:
 Desktop-Optionen
 
- Einstellungen
- System
- Debugging
- "Debug-Logging aktivieren" anklicken

Fertig

Es wird nun am oberen Rand eine Statuszeile eingeblendet mit Infos; **Hier ist auch der Speicherort der Log-Datei zu sehen!**

Starte Kodi neu und öffne das Addon welches einen Fehler verursacht. Erstellen dann sofort eine Log-Datei (dann ist der Fehler leichter herauszulesen).

Das Debug-Logging kann im Anschluss wieder deaktiviert werden.

Unter dem Punkt  Komponentenspezifische Protokollierung kann man bei der Kategorie "Konfiguration der Komponentenspezifischen Protokollierung" noch Einstellen was alles im Debug-Log Protokolliert werden soll.


## 5. Phyton Dateien


### 5.1. Allgemeines zur .py-Datei

Eine .py Datei ist eigentlich eine Textdatei. Die Endung .py verweist auf die Programmiersprache Python, welche in Kodi zur Anwendung kommt.Diese .py Dateien werden in sämtlichen/den meisten Addons verwendet.
 
 
### 5.2 Bearbeiten einer .py-Datei

Manchmal werdet Ihr lesen z.B. Wechsel die .py Datei in dem Ordner „xyz“, oder ändere den Eintrag in Zeile 134.Öffnen könnt Ihr die Datei mit vielen Programmen z.B. Notepad++ (Freeware) oder Texteditor. In Notepad werden Euch die Zeilen-Nummern angezeigt und ist somit übersichtlicher, aber es geht auch mit dem EditorMit Notepad++ könnt Ihr die .py Datei sofort öffnen und wieder speichern.

Bei Verwendung des Text-Editors müsst Ihr die Endung vorher von .py auf .txt ändern. Dann könnt Ihr die Datei öffnen und Änderungen vornehmen. Im Anschluss bitte „Speichern unter“ wählen und bei „Dateityp“ alle wählen, und wieder als .py Datei speichern


### 5.3 Speicherort der einzelnen Webseiten (.py Dateien)

In den folgenden Ordnern findet Ihr alle Addons von Kodi. 
Das Addon Exodus wird in aller Regel unter plugin.video.exodus istalliert.

- Android 
	- `/Android/data/org.xbmc.kodi/files/.kodi/addons/`
	- `/sdcard/Android/data/org.xbmc.kodi/files/.kodi/addons/`  (.kodi ist ein versteckter Ordner)
- iOS
	- `/private/var/mobile/Library/Preferences/Kodi/addons/`
- Linux 
	- `~/.kodi/addons/`
- Mac 
	- `/Users/<your_user_name>/Library/Application Support/Kodi/addons/`
- OpenELEC 
	- `/storage/.kodi/addons/`
- Windows
	- `C:\Users\BENUTZERNAME\AppData\Roaming\Kodi\addons`    (AppData ist ein versteckter Ordner)



Im Verzeichnis `resources/lib/sources_de` sind die .py Daten  der einzelnen Webseiten abgelegt.

