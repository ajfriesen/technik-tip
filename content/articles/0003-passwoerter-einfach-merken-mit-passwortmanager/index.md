---
title: 'Passwörter einfach merken mit Passwortmanager'
date: 2019-11-19
categories: ["Passwörter"]
tags: [ "" ]
draft: true
weight: 1
image: ""
author: "Andrej Friesen"
---
Was haben der Pin für die Bankkarte, das WLAN Kennwort oder der Login für Facebook, Google Mail, Amazon, eBay und Internetforen gemeinsam?

Diese haben alle ein Passwort und dieses muss man sich merken.

Es ist sehr schwer sich diese Anzahl zu merken, außer es wird immer das gleiche Passwort verwendet und genau das sollten Sie nicht machen.
Hier erfahren Sie, wie Sie mit einem Passwortmanager das Problem der hunderten komplizierten Passwörter in den Griff bekommen.
<!--more-->


{{< figure src="./logo_how-to-choose-best-password-manager.jpg" width="100%" caption="Photo by Whaaat" >}}

---

# Das Wichtigste in kürze

* Passwortmanager nutzen und sich so nur ein Passwort (das Masterpasswort) für den Passwortmanager merken
* Für jedes Konto, Account oder Dienst einen eigenen Eintrag mit eigenem Passwort erstellen
* Lange Passwörter mit mindestens 12 Zeichen verwenden (der Passwort-Generator im Passwort Manager hilft hier)
  * Es gibt eigentlich keinen Grund jetzt kurze Passwörter zu nutzen, da der Passwortmanager diese jetzt verwaltet
* Bei Passwortleaks benachrichtigen lassen und das Passwort für das betroffene Konto sofort wechseln
* 2 Faktor Authentifizierung nutzen
  * vor allem beim E-Mail Konto
  * und bei Passwortmanager, wenn dieser ebenso ein Onlinedienst ist

# So gehen Sie vor

* Entscheiden Sie sich für einen Passwortmanager und installieren Sie diesen
* Richte den Passwortmanager mit einem langen Masterpasswort ein ([Artikel: Sichere Passwörter]({{< ref "/articles/0001-was-sind-sichere-passwoerter" >}}))
* Erstelle für jedes Konto (Soziale Netzwerke, Internetforen, Onlineshops, etc.) einen neuen Eintrag mit einem zufälligen langem Passwort
    * Viele Passwort Manager bieten auch eine praktische Import Funktion an, die die Passwörter aus dem Browser holt
* Beim nächsten einloggen einfach den Passwortmanager entsperren und das Passwort aus dem passenden Eintrag kopieren und einfügen
* *(optional) Browser Erweiterungen auf dem PC installieren damit jederzeit und komfortable die Passwörter genutzt werden können*
* *(optional) Smartphone App installieren*

# Funktionsweise von Passwort Managern

Im endeffekt funktinoieren alle Passwort Manager mehr oder weniger gleich.
Beim ersten Start fragt das Programm nach einem Masterpasswort.
Dieses Passwort wird dafür verwendet die Passwortdatenbank zu verschlüsseln.
Das gleiche passiert auch beim Online Passwort Manager.
Sie setzten nicht unbedingt explizit ein Masterpasswort sondern nutzten einfach das Passwort, welches ihr für die Regestrierung des Dienstes angebt.
Klaut jemand eure Passwortdatenbank kann der oder diejenige damit nichts anfangen, da diese nur mit dem Masterpasswort geöffnet und somit gelesen werden kann.

Der große Unterschied zwischen Offline und Online Variante:
Beim Offline Passwort Manager wie Keepass liegt die Passwortdatenbank als Datei auf ihrem Gerät.
Bei Online Passwort Managern wie LastPass liegt die Passwortdatenbank auf den Servern oder neudeutsch Cloud des Anbieters.

## Wie prüft der Passwort Manager ob das Passwort richtig ist?

An sich wird nie das Passwort direkt geprüft.
Beim verschlüsseln der Passwortdatenbank geben Sie ihr Masterpasswort ein.
Die Verschlüsselung der Passwortdatenbank wird mit Hilfe eines komplexen Algorythmus bewerkstelligt.
Um die Datenbank wieder öffnen zu können braucht es das Masterpasswort.

Wenn Sie jetzt ihren Passwort Manager entsperren wollen, tippen Sie ihr Passwort ein und das Programm erstellt einen sogenannten Hash.
Dieser Hash wird genutzt, um zu prüfen ob das Passwort welches Sie eintippen auch das richtige für die Passwortdatenbank ist.

**Das gilt auch für einen Online Passwort Manager.**
Viele glauben, dass man bei einem Online Passwort Manager wie Lastpass und andere das Passwort mitschickt.
Das stimmt allerdings nicht ganz.
Es wird immer nur der Hash mitgeschickt der lokal berechnet wird.
Die Berechnung des Hashes passiert immer auf Seite des Clients.
In diesem Fall also vom Lastpass Programm, wenn dieses installiert ist.
Falls kein Programm/App installiert ist und man im Browser sich anmeldet ist der Browser der Client.

Zusammenfassend: Es wird nie das eigentliche Passwort übertragen.
Der Online Passwort Manager Anbieter kann somit bei vernünftiger Verschlüsselung auch nicht auf eure Daten zugreifen.
Das ist auch gut so!

# Masterpasswort einrichten
 
Dieses Passwort wird von nun an das einzige welches Sie sich merken müssen.
Wie Sie ein gutes Passwort erstellen können Sie in diesnm Artikel nachlesen:([Sichere Passwörter]({{< ref "/articles/0001-was-sind-sichere-passwoerter" >}}))

Bitte nutzen Sie auf keinen Fall ein schon bekanntes Passwort!
Wie Sie das nachprüfen folgt in einem weiteren Artikel.

Es lohnt sich auch dieses Passwort aufzuschreiben und an einem sicherem Ort zu verwahren.
Ein Safe, eine abschließbare Schublade, Bankschließfach, was auch immer.
Ein Gedächtnisverlust nach einem Unfall oder Demenz und schon kommen Sie nicht mehr an alle ihre Daten.

# Sie können mehr als nur Passwörter speichern

Ein Passwortmanager ist eigentlich nur ein verschlüsselte Datenbank, der nur mit ihrem Passwort zu öffnen ist.
Das heißt Sie können dort auch geheime Notizen, Sicherheitsfragen, Kundennummern, Sozialversicherungsnummer, Steuernummer, ADAC Mitgliedsnummer und so weiter speichern.

Wenn Sie solche persönlichen Daten speichern sollten, Sie vorher überlegen, wie und vor allem wogegen Sie sich schützen sollten/müssen.

# Wie entscheide ich mich für welchen Passwort Manager?

Wie vorhin schon erwähnt gibt es im Grunde 2 verschiedene Arten von Passwort Managern.

1. Einmal die Online Variante wo Sie ein Konto erstellen und die Passwörter im Rechenzentrum des Anbieters gespeichert werden. Gerne auch Cloud genannt, aber es sind auch nur Server.
2. Die Offline Variante speichert die Passwörter in einer lokalen Datei auf ihrem Gerät ab.
3. Die Offline Variante bietet eine dritte Variante an.
Sie können einen Offline Passwort Manager nutzen, der die Datei lokal auf ihrem PC ablegt.
Dann können Sie die Datei mit einem Dienst ihrer Wahl (Dropbox, Google Drive, Microsoft OneDrive) in die Cloud synchronisieren.

## 1. Offline Variante

Angriffsvektor:

* Ihr lokales Gerät

Pro:

* Die Passwortdatenbank ist nur auf ihrem Gerät vorhanden
* Angriffsvektor ist nur ihr Gerät
  * Um an ihre Datenbank zu kommen braucht der Angreifer physischen Zugriff oder muss die Kontrolle über ihren Computer übernehmen

Contra:

* Keine Synchronisierung auf andere Geräte möglich
* Sie müssen sich selbst um die Backups kümmern

## 2. Online Variante

Angriffsvektor:

* Online Passwort Manager Anbieter

Pro:

* Synchronisierung ist meisten über merhere Geräte möglich (Windows, Mac, Linux, ChromeOS, Android, iOS,)
* Der Anbieter kümmert sich eigentlich um Backups

Contra:

* Die Passwort Datenbank liegt in der Cloud/ fremden Servern (Vertrauensfrage)
* Der Angrifsvektor ist jetzt größer, da ein potentieller Angreifer ihr Passwort ausprobieren kann
  * Hier ist es absolute Pflicht neben dem Masterpasswort auch eine 2-Faktor-Authentifizierung einzurichten.
Nichts ist zu 100% sicher und so auch nicht der Online Passwort Mangager Server.
Kommen Dritte an ihr Passwort für den Dienst sollte die 2-Faktor-Authentifizierung Sie dafür schützen, dass nicht gleich auch der Zugriff auf alle Account möglich ist.

## 3. Offline Variante mit Online Speicher

Angriffsvektor:

* Alle Geräte die synchronisiert werden
* Online Speicher Anbieter

Pro:

* Synchronisierung über mehrere Geräte hinweg
* Angriffsvektor sind die Geräte und der Online Speicher Anbieter den Sie nutzen
  * Ihr Online Speicher Anbieter weiß nicht, 
  * Kann auch auf eigenen Severn, NAS (Network Attached Storage) zu Hause oder auf gemietet Servern betrieben werden.
Hier würde ich sagen, dass ist nichts für Leien.
Man muss sich mit der Technik auskennen und aktuell bleiben.
Port Forwarding oder VPN dauerhaft sicher zu betreiben ist für den Otto Normalverbraucher einfach nicht praktikabel.

Contra:

* Sie müssen sich selbst um die Backups kümmern
  * Auch wenn die Passwortdatenbank jetzt über mehrere Geräte synchronisiert
  * Zum Thema Backup generell kommt noch ein gesonderter Artikel, der dann hier verlinkt wird

# Fazit

Wie man in der obigen Aufführung der drei Unterschiedlichen Varianten sieht geht es bei der Entscheidung des Passwort Managers immer im eine Abwägung von Komfort und Vertrauen.
Vertraue ich Anbieter X oder lieber Y.
Dazu kommen noch individuelle Ansprüche, wie:
* Brauche ich meine Passwortdatenbank auf dem Handy und somit die Synchronisierung?
* Habe ich Lust mich um die Backups zu kümmern?
* Möchte ich dafür Geld ausgeben?
* Dieser Passwort Manager funktinoiert leider nicht auf meinem iPhone

Mit den ganzen Informationen die Sie jetzt bekommen suchen Sie sich den passenden Passwort Manager aus.
Probieren Sie diese am besten ein paar Tage aus.
Die Entscheidung kann man ja früher oder später noch ändern und die Passwörter migrieren.

# Auswahl an Passwort Managern

Eins möchte ich Ihnen noch mitgeben:
Hören Sie nicht auf die Leute, die predigen, dass man auf keinen Fall etwas in der Cloud machen soll.
Egal für welchen Passwort Manager Sie sich entscheiden.

**Jeder Passwort Manager ist besser, als immer das gleiche unsichere Passwort für alle Dienste zu nutzen!**

## KeePass2

{{< figure src="./keepass_512x512.png" width="50%" caption="Keepass Logo" >}}

Was Passwortverwaltung betrifft ist Keepass einfach nicht wegzudenken.
Der Klassiker unter den Passwortmanagern.
Die Webseite und das Programm mögen etwas altbacken wirken, aber lassen Sie sich nicht täuschen.
Der Qellcode ist open source und ist so für jederman einsehbar.
Keepass wird redelmäßig auditiert und wird sogar von einigen Regierungen, darunter auch Deutschland, empholen (https://keepass.info/ratings.html)
Dazu ist es das Programm mit den meisten Funktionen und lässt sich durch die Plugins sehr gut erweitern.

Das Keepass Dateiformat kann auch von vielen anderen Programmen gelesen werden und daher gibt es eine Vielzahl an Alternativen.

### Eigentschaften:

* Kostenlos
* Braucht keine Installation
  * Kann einfach auf den USB Stick gepackt werden
* Apps für Windows, Mac, Linux, Android und iOS sind vorhanden
* Viele verschiedene Clients/Apps die das Keepass Format lesen können:
  * PC
    * [KeePassXC](https://keepassxc.org/)
    * [KeePassX](https://www.keepassx.org/)
    * [KeeWeb](https://keeweb.info/)
  * Smartphone
    * [Keepass2Droid](https://play.google.com/store/apps/details?id=keepass2android.keepass2android)
    * [Keepass2Android Offline](https://play.google.com/store/apps/details?id=keepass2android.keepass2android_nonet)
    * [MiniKeepass](https://apps.apple.com/de/app/minikeepass/id451661808)
* OpenSource
* Speichert die Passwörter lokal auf der Festplatte
* Keine Onlinezwang
* Keine Synchronisierung (Kann durch Dropbox, Google Drive, Microsoft Ondrive, etc. nachgerüstet werden)
* Hat sehr viele Plugins: [KeePass Plugins and Extensions](https://keepass.info/plugins.html)
* In vielen Sprachen verfügbar (https://keepass.info/translations.html)
* Anpassbar auf viele Anwedungsfälle weit über dem Speichern von Passwörtern für Webseiten
  * TANS
  * SSH Logins mit Putty
* Mächtigstes Tool

### Lohnenswerte Plugins

* Kein Plugin, aber hier ist die [Anleitung für das Hinzufügen der deutschen Übersetzung](https://keepass.info/translations.html)
* [Favicon Downloader[(https://keepass.info/plugins.html#faviconimp) läd die kleinen Bildchen von Facebook und Co automatisch herunter und sorgt so für mehr Übersicht.
* [KeePassHttp](https://keepass.info/plugins.html#keepasshttp) füllt automatisch Passwörter im Browser aus
  * Hier kann man auch einfach die Autofill Funktion nutzen
* [KPSimpleBackup](https://keepass.info/plugins.html#kpsimplebackup) erstellt Backups der Datenbank beim speichern

### Weitere KeePass Apps/Clients

Eigentlich gibt es KeePass 2 offiziell auf Windows, aber 

## Enpass

Enpass Logo
Webseite: https://www.enpass.io
Ein moderner und relativ neuer Passwortmanager auf dem Markt.
Größter Vorteil für enpass ist die direkte Nutzung für Cloudspeicher über die API. Es muss kein Client für Google Drive, OneDrive, Dropbox oder OwnCloud installiert sein.Google Drive bietet für Linux z.B. keinen offiziellen Google Drive Client an. Enpass selbst kümmert sich um die Synchronisation die wirklich hervorragend funktioniert und ermöglicht so die Synchronisation über den eigenen Cloud Speicher Anbieter.





Basisapplikation für Windows, Mac und Linux ist kostenlos (https://www.enpass.io/pricing/)
Premiumfeatures kosten wiederum auf dem Desktop und auf Smartphones extra ( https://www.enpass.io/pricing/)
Kosten belaufen sich auf eine Moderate Einmalzahlung (Kein Abomodell)
Kein Onlinezwang, kann auch nur lokal genutzt werden
Der Passwordsafe kann lokal abgespeichert werden oder über verschiedenen Cloud Speicher Anbietern
Der Cloudspeicher funktionert ohne Client, dass heißt es Enpass kümmert sich um das speichern und synchronisieren. Es muss z.B. kein Google Drive Client installiert werden, der dann den Passwortsafe synchronisiert
Browsererweiterung vereinfacht das Eingeben der Passwörter ungemein

## 1Password

1Password ist schon lange auf dem Markt und vor allem bei Benutzern von Apple Geräten beliebt. Seit längerer Zeit ist aber auch ein Client für Windows erhältlich.
Seit längerem ist 1Password auf ein monatliches Abomodell geweschelt. Die Preise sind hier zu finden:
https://1password.com/sign-up/
Sehr schönes Design
Gut in MacOS integriert
Alle gängigen Betriebssysteme werden unterstützt (Windows, Max, Linux, Android, iOS)


Es gibt Browsererweiterungen für sehr viele Browser










## Bitwarden

Bitwarden Logo






Browser Plug ins erklären: Vor-und Nachteile
Backup des Passwortmanagers?

Was hälst du von Passwortmanagern?
Geschmäcker und Anforderungen variieren. Ich kenne auch nicht jeden Passwortmanager auf dem Markt. Daher verzeih mir, dass ich deinen Favoriten nicht gelistet habe und schreib es einfach in die Kommentare. Welchen Passwortmanager nutzt du und vor allem warum?

# Quellen

[1] https://www.bsi-fuer-buerger.de/BSIFB/DE/Empfehlungen/Passwoerter/Passwort_Manager/Passwort_Manager_node.html

[2] https://stadt-bremerhaven.de/google-g-suite-passwoerter-lagen-viele-jahre-im-klartext-vor/?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+stadt-bremerhaven%2FdqXM+%28Caschys+Blog%29

https://netzpolitik.org/2018/kleines-einmaleins-der-digitalen-selbstverteidigung/#Browser