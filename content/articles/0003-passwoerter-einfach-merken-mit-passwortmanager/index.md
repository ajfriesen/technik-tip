---
title: 'Passwörter einfach merken mit Passwortmanager'
date: 2019-11-19
categories: ["Passwörter"]
tags: [ "" ]
draft: true
weight: 1
image: "how-to-choose-best-password-manager.jpg"
author: "Andrej Friesen"
---
Was haben der Pin für die Bankkarte, das WLAN Kennwort oder der Login für Facebook, Google Mail, Amazon, eBay und Internetforen gemeinsam?

Die haben alle ein Passwort.

Es ist sehr schwer sich diese Anzahl zu merken, außer es wird immer das gleiche Passwort verwendet und genau das sollten Sie nicht machen.
Hier erfahren Sie, wie mit einem Passwortmanager das Problem der hunderte komplizierte Passwörter sich einfach in Luft auflöst.
<!--more-->


{{< figure src="./logo_how-to-choose-best-password-manager.jpg" width="100%" caption="Photo by Whaaat" >}}

---



Browser Plug ins erklären: Vor-und Nachteile
Backup des Passwortmanagers?
Checken:
https://netzpolitik.org/2018/kleines-einmaleins-der-digitalen-selbstverteidigung/#Browser
https://stadt-bremerhaven.de/google-g-suite-passwoerter-lagen-viele-jahre-im-klartext-vor/?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+stadt-bremerhaven%2FdqXM+%28Caschys+Blog%29

# Das Wichtigste in kürze

* Passwortmanager nutzen und sich so nur ein Passwort (das Masterpasswort) für den Passwortmanager merken
* Für jedes Konto, Account oder Dienst einen eigenen Eintrag mit eigenem Passwort erstellen
* Lange Passwörter mit mindestens 12 Zeichen verwenden (der Passwort-Generator im Passwort Manager hilft hier)
  * Es gibt eigentlich keinen Grund jetzt kurze Passwörter zu nutzen
* Bei Passwortleaks benachrichtigen lassen und das Passwort für das betroffene Konto sofort wechseln
* 2 Faktor Authentifizierung nutzen
  * vor allem beim E-Mail Konto
  * und bei Passwortmanager, wenn dieser ebenso ein Onlinedienst ist

# So gehen Sie vor

* Entscheiden Sie sich für einen Passwortmanager und installieren Sie diesen
* Richte den Passwortmanager mit einem langen Masterpasswort ein ([Artikel: Sichere Passwörter]({{< ref "/articles/0001-was-sind-sichere-passwoerter" >}}))
* Erstelle für jedes Konto (Soziale Netzwerke, Internetforen, Onlineshops, etc.) einen neuen Eintrag mit einem zufälligen langem Passwort
* Beim nächsten einloggen einfach den Passwortmanager entsperren und das Passwort aus dem passenden Eintrag kopieren und einfügen
* *(optional) Browser Erweiterungen auf dem PC installieren damit jederzeit und komfortable die Passwörter genutzt werden können*
* *(optional) Smartphone App installieren*


# Richte den Passwortmanager mit einem langen Masterpasswort ein
 
Dieses Passwort wird von nun an das einzige welches Sie sich merken müssen.
Wie Sie ein gutes Passwort erstellen können Sie in diesem Artikel nachlesen:([Sichere Passwörter]({{< ref "/articles/0001-was-sind-sichere-passwoerter" >}}))

Bitte nutzen Sie auf keinen Fall ein schon bekanntes Passwort!
Wie Sie das nachprüfen folgt in einem weiteren Artikel.

Es lohnt sich auch dieses Passwort aufzuschreiben und an einem sicherem Ort zu verwahren.
Ein Safe, eine abschließbare Schublade, Bankschließfach, was auch immer.
Schließlich kann Gedächtnisverlust Sie auch das Masterpasswort vergessen lassen.

# Sie können mehr als nur Passwörter speichern

Ein Passwortmanager ist eigentlich nur ein verschlüsselter Container, der nur mit ihrem Passwort zu öffnen ist.
Das heißt Sie können dort auch geheime Notizen oder Sicherheitsfragen, Kundennummern, Sozialversicherungsnummer, Steuernummer, ADAC Mitgliedsnummer und so weiter speichern.

# Welche Art von Passwortmanager brauche ich?

Das kommt drauf an welche persönlichen Anforderungen und Nutzungsgewohnheiten hat.

## Typ 1

Nur am PC


# Welche Passwortmanager sind zu empfehlen?

Hier eine Auswahl an Passwortmanagern, die ich selbst im Einsatz hatte und entsprechend der Anforderungen empfehlen kann.

## KeePass2

{{< figure src="./keepass_512x512.png" width="50%" caption="Keepass Logo" >}}

Was Passwortverwaltung betrifft ist Keepass einfach nicht wegzudenken.
Der Klassiker unter den Passwortmanagern.
Die Webseite und das Programm mögen etwas altbacken wirken, aber lassen Sie sich nicht täuschen.
Es ist das Programm mit den meisten Funktionen,

Ein wirklich gutes Programm verbirgt sich dahinter.
Für wen?
In meinen Augen ist Keepass2 der beste Passwortmanager.
komplett kostenlos
Mehrfach ausgezeichnet ist Keepass ein sicherer Passwortmanager, der regelmäßig Upadtes erhält.Keepass und das Dateiformat in welchem der Passwortmanger die Passwörter speichert sind OpenSource.
Daher gibt es auch viele Client, die das Keepass Dateiformat bearbeiten können.

### Eigentschaften:

* Kostenlos
* Apps für Windows, Mac, Linux, Android und iOS sind vorhanden
* Viele verschiedene Clients/Apps die das Keepass Format lesen können:
  * [KeePassXC](https://keepassxc.org/)
  * [KeePassX](https://www.keepassx.org/)
  * [KeeWeb](https://keeweb.info/)
* OpenSource
* Kostenlos
* Speichert die Passwörter lokal auf der Festplatte
* Keine Onlinezwang
* Keine Synchronisierung (Kann durch Dropbox, Owncloud nachgerüstet werden)
* Hat sehr viele Plugins: [KeePass Plugins and Extensions](https://keepass.info/plugins.html)
* In vielen Sprachen verfügbar (https://keepass.info/translations.html)
* Anpassbar auf viele Anwedungsfälle weit über dem Speichern von Passwörtern für Webseiten
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






Was hälst du von Passwortmanagern?
Geschmäcker und Anforderungen variieren. Ich kenne auch nicht jeden Passwortmanager auf dem Markt. Daher verzeih mir, dass ich deinen Favoriten nicht gelistet habe und schreib es einfach in die Kommentare. Welchen Passwortmanager nutzt du und vor allem warum?
Quellen
[1] https://www.bsi-fuer-buerger.de/BSIFB/DE/Empfehlungen/Passwoerter/Passwort_Manager/Passwort_Manager_node.html
