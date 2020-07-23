---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Passwortmanager"
subtitle: ""
summary: ""
authors: [admin]
tags: ["Passwörter"]
categories: ["Ratgeber"]
date: 2020-06-01T22:19:06+02:00
lastmod: 2020-06-01T22:19:06+02:00
featured: false
draft: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Es ist einfach unmöglich sich alle Passwörter zu merken, die man heuzutage braucht.
Erst kommt die E-Mail, dann Soziale Netzwerke, Onlinebanking, ein Forum, Online Shopping Portale, Zugangsdaten für WLAN und den Router, etc.
Damit wir wieder Herr der Passwörter werden wird hier der Passwortmanager erklärt.

<!--more-->

{{% alert primary %}}
Das Wichtigste in Kürze:

* Passwort Manager sind sichere Safes für alle deine Passwörter
* Nicht nur Passwörter, sondern auch sichere Notzien lassen sich dort ablegen
{{% /alert %}}

{{% alert info %}}
So gehst du vor:

* Suche dir einen passenden Passwort Manager aus
* Erstelle ein sicheres Master Passwort
* Trage alle deine Passwörter und Dienste dort ein
* Generiere für neue Dienste sichere Passwörter mit dem Passwort Manager

{{% /alert %}}

{{% toc %}}

## Warum ein Passwortmanager

Mitlerweile hat wirklich so gut wie jeder einiger Passwörter zu verwalten.
Sei es das Passwort für soziale Netzwerke (Facebook, Xing, etc.), diverse Online Shops (Amazon, eBay, kleinere Händer Shops) der Simkarten Pin, Pin für die Kreditkarte, E-Mails oder für den DSL Anschluss.
Alles hat ein Passwort, Pin, Kennwort etc.

Wenn du jetzt meinst du könntest dir diese einfach merken, machst du höchstwarhscheinlich etwas falsch.
Über sichere Passwörter haben wir schon einen Artikel geschrieben. Den findet du hier: [Sichere Passwörter]({{< relref"../sichere-passwoerter/index.md" >}}).

Ein Passwortmanager dient also zur Verwaltung der wahnsinnigen Anzahl an Passwörtern.
Dazu bietet dieser auch jede menge Komfortfunktionen, wie:

* Passwörter generieren
* Automatisches ausfüllen im Browser
* Synchronisation mit anderen Geräten (Nicht alle)

## Wie funktioniert ein Passwortmanager?

Den Passwortmanager kann man sich als Safe vorstellen.
Der Safe ist mit einem Passwort gesichert und dieses Passwort kennst nur du.
Dieses Passwort wird meistens Master Passwort genannt.
Dies sollte ein sicheres Passwort, welches NUR für den Passwort Safe benutzt wird.

In Safe wiederum liegen dann die Blätter/Einträge mit den Login Daten.
Pro Blatt/Eintrag ein Dienst:

1. E-Mail Account
2. Facebook
3. Amazon
4. DSL Internet Anschluss
5. Handy Pin
6. Kreditkarten Pin
7. WLAN Passwort
8. Zugangsdaten zum Router
9. etc.

Möchte man sich jetzt bei Facebook einloggen muss man erst den Safe mit dem Master Passwort öffnen.
Erst dannach kann man sich das Blatt/Eintrag für Facebook suchen und loggt sich damit ein.

## Arten von Passwort Managern

Es gibt eignelich zwei unterschiedliche Arten von Passwort-Managern.

* lokaler Passwort-Manager
* Cloudbasierter Passwort-Manager

### Lokaler Passwort-Manager

Für den lokalen Passwort-Manager installiert man ganz normal das Programm/App auf seinem Computer oder Smartphone.

Beim ersten Start eines Passwort Managers wird meistens ein Master Passwort festgelegt.
Dieses Passwort wird dazu verwendet die Passwort Manager Datei (Safe) und den Inhalt darin zu verschlüsseln.
Das heißt, dass niemand den Inhalt der Passwort Manager Datei lesen kann, wenn er das Passwort nicht kennt.

{{% alert primary %}}
Die Daten im Passwort Safe sind ohne das Master-Passwort nicht einsehbar.
Das Master-Passwort darf man daher auf keinen Fall vergessen!
{{% /alert %}}

Die Password-Manager Datei liegt jetzt einfach auf dem Laptop, PC oder Smartphone.
Falls man mit mehreren Geräten drauf zugreifen möchte, muss man sich um die Synchrinisierung der Datei auf den verschiedenen Geräten (PC und Smartphone) selber kümmern.
Das kann einfach eine Kopie auf dem USB Stick sein oder die Password-Manager Datei auf einen Cloudspeicher zu legen und über die Geräte zu synchronisieren.

### Cloudbasierter Passwort-Manager

Dieser Passwort-Manager läuft hauptsächlich in der Cloud.

Grundlegend funktionert der Cloudbasierte Passwort-Manager genauso, wie der lokale.
Anstatt eines extra Master-Passwort wird hier meist das Account Passwort genutzt, mit dem der Password-Safe dann verschlüsselt wird.
Der Password-Safe wird dann in der Cloud des Dienstanbieters gespeichert.

Meistens hat man dann keinen lokalen Zugriff auf den Passwort-Manager Safe auf dem PC oder Smartphone.

{{% alert primary %}}
Bei Einhaltung moderner Verschlüsselungsstandards kann der Clouddienst tatsächlich nicht eure Passwörter einsehen.
{{% /alert %}}

#### Exkurs zur Verschlüsselung

Passwörter werden von Onlinediensten eígentlich nicht gespeichert.  
Was heißt das jetzt? Wie sollen die dann wissen, dass ich das richtige Passwort eintippe?

Wenn ein jemand richtig Passwörter speichert, dann speichert der Dienst nicht das Passwort, sonern einen sogenannten Hash.
Dieser Hash wird aus dem Passwort generiert. Dazu gibt es viele unterschiedlich kryptografische Verfahren.

Man kann sich das aber einfach so vorstellen.
Beim erstellen eines Online Accounts gibt man sein E-Mail Adresse, Name und das Passwort ein.
Das Passwort meist zwei mal, um vertipper zu vermeiden. Das Passwort ist in unserem Bild der **Schlüssel**.

{{< figure src="./vanna-phon-hRXIKdxoaPo-unsplash.jpg"
width="100%"
caption="Der Schlüssel als Passwort"
link=https://unsplash.com/photos/hRXIKdxoaPo
target="_blank"
alt="offenes Vorhängeschloss mit Schlüssel"
>}}

Beim Absenden des Formulars erstellt der Browser lokal auf dem PC den Hash.
In unserem Bild das **Schloss**.
Nach dem erstellen des Hashes (Schloss), schickt der Browser nur den Hash selbst zu dem Onlinedienst, nie das eigentlich Passwort.

Nur die Person, die den Schlüssel hat, kann das Schloss öffnen.
Da der Onlinedienst den Schlüssel nie bekommen hat, sind die Daten, falls diese damit verschlüsselt wurden, auch nicht für den Dienst einsehbar.

Hierbei spielt natürlich Vertrauen eine große Rolle.
Dieses kann man der Firma dahinter so geben.
Dies kann aber auch durch Audits passieren oder aber auch dadurch, dass die Software Open Source ist.
Somit kann in der Theorie jeder diese Sofware überprüfen.
Ob dies der Fall ist, steht auf einem anderem Blatt.

### Die etwas technischere Erklärung

Beim ersten Start eines Passwort Managers wird erstmal immer ein Master Passwort festgelegt.
Dieses Passwort wird dazu verwendet die Passwort Manager Datei (Safe) und den Inhalt darin zu verschlüsseln.
Das heißt, dass niemand den Inhalt der Passwort Manager Datei lesen kann, wenn er das Passwort nicht kennt.

{{% alert primary %}}
Deswegen muss dieses Passwort sehr sicher sein!
{{% /alert %}}

Bein Online Passwort Manager Tools funktioniert das ähnlich.
Es wird zwar keine Password Safe Datei erstellt, aber beim jeweiligen Anbieter in der Cloud.
Der Anbieter kann bei richtiger kryptografischer Implementierung wirklich nicht eure Passwort Datei öffnen.
Dazu muss man dem Anbieter vertrauen oder dieser hat den 







### Komfortfunktionen von Passwortmanagern


Eigentlich handel es sich beim Passwort Manager um eine digitale Version des [Passwort Buches](/../post/passwort-buch/) der in einem Safe liegt.
Jedes mal zum Safe rennen, das Passwort eintippen, den richtigen Eintrag finden und eintippten ist natürlich sehr mühsam und muss inder heutigen Zeit nicht sein.

Passwort Manager bieten hier viele Funktionen die das Arbeiten erheblich erleichtern.
Hier eingie Funktionen die den Alltag doch sehr erleichtern.
Nicht alle Passwort Manager haben die gleichen Funktionen, daher müsst ihr selber testen, welcher euch gefällt.

* Suchfunktion
* Automatisches Ausfüllen von Passwörtern auf Webseiten
* Automatisches generieren von sicheren Passwörtern für einen neuen Eintrag
* Synchronisierung zwischen mehreren Geräten
* Mobile Nutzung auf Smartphones
* Automatisches ausfüllen von Passwörtern im Handy auf Webseiten und Apps
* Zugriff aus dem Internet, falls das Handy oder der eigene PC nicht erreichbar sind
* Passwort Historie


## Meine Persönliche Empehlung


## Eine unvollständige Liste an Passwortmanagern

* [KeePass](https://keepass.info/)
* KeePass Varianten:
  * [KeeWeb](https://keeweb.info/)
  * [KeePassXC](https://keepassxc.org/)
  * Android App: [Keepass2Android Password Safe](https://play.google.com/store/apps/details?id=keepass2android.keepass2android&hl=en_US)
* [Bitwarden](https://bitwarden.com/)
* [1Password](https://1password.com/de/)
* [Dashlane](https://www.dashlane.com/de/features/password-manager)
* [Enpass](https://www.dashlane.com/)
* [LastPass](https://www.dashlane.com/)
