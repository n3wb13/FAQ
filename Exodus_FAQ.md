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
 
- [3. Bekannte Probleme](#3-bekannte-probleme)
    - [3.1 Fehler bei der Installation](#31-fehler-bei-der-installation)
    - [3.2 URL Resolver Fehler](#32-url-resolver-fehler)
   - [3.3 Fehlermeldungen im Betrieb](#35-fehlermeldungen-im-betrieb)
  
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

Der Menüaufbau von Exodus ist eigentlich selbsterklärend

Die Menüsprache von Exodus ist jene Sprache, auf die Kodi eingestellt ist

Bei Exodus liegt der Vorteil für viele User darin, dass auch Englisch sprachliche Streams genutzt werden können.

Die Englischen Seiten werden jedoch von uns nicht Supportet.
Fragen dazu bitte im Englischen Forum stellen: [Link](https://forums.tvaddons.ag/lambda-s-xbmc-addons/41161-exodus-add.html)

Unterstützung und Anfragen zu den Deutschen Seiten, Problemen usw. werden derzeit über das xStream Forum abgewickelt.

Ob es ein eigenes deutsches Exodus Forum geben wird, steht momentan noch nicht fest.

### 1.1 Verfügbare Webseiten

| Name           | Domain            | Verfügbarkeit          | Stand      |
|:-------------- |:----------------- | :------------------| :--------- |
|1Kino| 1kino.in| 	funktioniert| 12.01.2017
| BurningSeries  | bs.to             | funktioniert           | 12.01.2017 |
| Cine           | cine.to           | funktioniert           | 12.01.2017 |
| DirectDownLoad | ddl.me            | funktioniert           | 12.01.2017 |
| FilmPalast     | filmpalast.to     | funktioniert           | 12.01.2017 |
| HDfilme        | hdfilme.tv        | funktioniert           | 12.01.2017 |
|iLoad |iload.to |funktioniert|	12.01.2017
| KinoX          | kinox.to          | funktioniert           | 12.01.2017 |
|MeinKino 	 |meinkino.to  	 |funktioniert 	 |12.01.2017
|StreamDream| 	streamdream.ws| 	funktioniert |12.01.2017
| Tata           | tata.to           | funktioniert           | 12.01.2017 |
| Video4k        | video4k.to        | funktioniert           | 12.01.2017 |
|View4U 	|view4u.co |funktioniert |12.01.2017

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

Das Video Addon Exodus wird über das  EXODUS Repository installiert (empfohlen). 

Diese ist momentan hier verfügbar: 
[Download](https://offshoregit.com/exodus/repository.exodus/repository.exodus-1.0.1.zip)

(INFO) Exodus auf Offshoregit: [Link](https://offshoregit.com/exodus/)

Die Aktualisierung von Exodus erfolgt NUR über das Exodus Repository, so wie bei jedem anderen Repo auch. 
Nach einem Repo Update, werden dann auch neu hinzugefügte Index-Seiten automatisch angezeigt.

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



***Zeitlimit für Index Seiten: ***

*Standard (default):* 30 Sekunden

Ist die Zeit, wie lange Exodus die Anbieter durchsuchen soll  bevor das Suchergebniss , als Liste zur Auswahl  angezeigt  wird

Exodus liefert ein exzellentes Ergebnisse mit einem Wert von 12 -  
15 Sekunden, vor allem wenn ihr einen Premium Service verwendet.

Wenn Ihr Schwierigkeiten habt Streams zu finden, kann dieser Wert erhöht werden

***Indikator***

*Standard (default): Lokal*

*Lokal: * der gesehen Status wird innerhalb von Kodi behandelt

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

All

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
Es wird der beste verfügbare Hoster gewählt

**Fortschrittsdialog**

Vordergrund: 
nach Streamauswahl wird das Info-Fenster, groß in der mitte des Bildschirmes dargestellt

Hintergrund: 
nach Streamauswahl wird das Info-Fenster, klein am Rand des Bildschirmes dargestellt

**DATEIANBIETER FILTER**

**Höchste Qualität: **

1080p, 720p und 480p stehen zur Auswahl

**SD Anbieter in Autoplay**

*Wenn aktiviert:*

werden im Auto-Play Modus nur SD Streams wiedergegeben. 
HD Streams werden dabei ignoriert. 
Ist nur dann sinnvoll, wenn man einen langsamen Internet Anbieter oder eine schwache Hardware hat

**Dateianbieter mit Captcha Abfrage* *

Wenn aktiviert, werden alle Hoster die Captcha-Abfragen durchführen ignoriert

**Nach Index-Seiten sortieren**

Wenn aktiviert, werden nur die Streams der Ausgewählten Anbieter angezeigt.
Premium Services sind immer Gruppiert und stehen  an der Spitze der Liste
Beispiel: Alle Streams, die z.B. auf PrimeWire gefunden werden, sind aufgelistet

***Wenn Wiedergabe startet......***

*Wiedergabe fortsetzen*

Wenn ein Stream gestoppt wird, wird automatisch ein Fortsetzungspunkt gespeichert/erstellt 

*Option Wiedergabe fortsetzten EIN:*

Es erscheint bei Fortsetzung des Streams eine  Anzeige  wo gewählt werden kann: Fortsetzen oder Vom Anfang abspielen an, egal welcher Hoster dabei gewählt wird

*Option Wiedergabe fortsetzten AUS:*

Stream startet immer vom Anfang (auch wenn Ihr eine advancedsettings.xml verwendet)


Wenn in Kodi unter: 
Addons-Seitenmenü, Automatische Aktualisierung auf AUS gestellt ist, wird Exodus nicht automatisch aktualisiert

**Exodus: Cache löschen/Index Seiten löschen**

Löscht den Cache (Speicher) von Exodus
Keine Angst, hierbei passiert nichts!!

### 2.3 Index Seiten Aktivieren und Deaktivieren

*Standard:* Alle Index Seiten aktiviert

In Exodus, unter dem Menüpunkt Werkzeuge, *Index-Seiten*, besteht die Möglichkeit bestimmte Seiten an bzw. auszuschalten. 

Ebenso kann jetzt hier eingestellt werden ob Deutsche und/oder Englische Seiten durchsucht werden
Dies kann von Nutzen sein, wenn kein Interesse an bestimmten Medien besteht. 
Diese werden dann auch nicht in der Suche angezeigt.

Nache einem Exodus Update werden auch neu hinzugefügte Seiten automatisch angezeigt. 
Das Update erfolgt aber nur, wenn das Exodus Repo installiert ist, wie am Anfang beschrieben

### 2.4 Hosterwahl

Wenn Ihr im Menü z.B. Filme- Jahr- 2017- beliebigen Film auswählen- klickt, werden alle verfügbaren Anbieter/Hoster durchsucht.

Auch nachdem eine Suche gestartet wurde, werden alle verfügbaren Anbieter/ Hoster angezeigt. 

Die Anzeige sieht wie Folgt aus:

BS I OPENLOAD I HD

(Anbieter I Hoster I Qualität)

Die Qualität des Streams kann sein:  HD, SD, CAM usw.

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

Damit dies nicht der Fall ist und die Hoster xStream so arbeiten lassen, wurde mit den Betreibern diese "pair" Funktion vereinbart.
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

## 3. Bekannte Probleme

### 3.1 Fehler bei der Installation

Keine bekannt

### 3.2 URL Resolver Fehler

Sollte dies der Fall sein, bitte den aktuellste Version des "URLResolver" über dier folgende Bezugsquellen beziehen:

 https://github.com/tknorris/script.module.urlresolver/archive/master.zip


### 3.3 Fehlermeldungen im Betrieb

Derzeit nichts bekannt 
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

