---
title: 'Sichere Passwörter'
subtitle: 'Was sind sichere Passwörter und wie erstellt man diese?'
summary: ''
authors:
- admin
tags:
- Passwörter
categories:
- Passwörter
date: 2019-11-11T00:00:00Z
lastmod: 2020-07-06T22:00:00Z
featured: false
draft: false
---

Passwörter sind nervig, aber notwendig.
Hier erfährst du was sichere Passwörter sind und worauf du bei der Erstellung von Passwörtern achten solltest.
Vor allem auch was du nicht machen solltest und auch warum.

<!--more-->
---

{{% alert primary %}}

Das wichtigste in Kürze

* :white_check_mark: Lange Passwörter sind sicherer als komplexe Passwörter
* :white_check_mark: Passphrasen sind besser als Passwörter
* :white_check_mark: Eine Passwortlänge von mindestens 12 Zeichen
* :x: Das selbe Passwort auf mehreren Seiten verwenden ist nicht erlaubt!
* :x: Persönliche Daten haben in Passwörtern nichts zu suchen (Namen, Wohnorte, Geburtsdaten, Sonstige perönliche und öffentlich auffindbare Informationen)
* :x: Tastaturmuster wie ASDF, 1234, jklö auf jeden Fall vermeiden
* :x: Alte Passwörter niemals wieder verwenden

{{% /alert %}}

{{% alert info %}}

So gehst du vor:

* Passwortmanager nutzen (Artikel folgt)
* Falls ein Passwortmanager für dich nichts ist kann ein Password Buch helfen (Artikel folgt)
* Für wichtige Konten (E-Mail, Bank, etc.) 2-Faktor-Authentifizierung aktivieren (Artikel folgt)

{{% /alert %}}

{{% toc %}}

## Was sind Passphrasen?

Eine Passphrasen ist eigentlich nicht anderes als ein paar Worte aneinandergereiht.
Um eine sichere Passphrase zu erstellen kann man einfach folgende Schirtte befolgen:

1. Ein paar Worte hintereinander schreiben (Am besten völlig ohne Zusammenhand)
2. Ein paar Buchstaben durch Ziffern austauschen (Ziffern werden häufig von Diensten bei Passwörtern verlangt)
3. Die Worte durch Sonderzeichen wie einem "-" ternnen (Sonderzeichen werden häufig von Diensten bei Passwörtern verlangt)

Die Wörter aus der Passphrase können auch aus verschiedenen Sprachen kommen.
Sei einfach kreativ.

Schon hat man eine sichere Passphrase erzeugt.
Diese ist länger als ein Passwort, lässt sich besser merken und ist zudem sicherer.

Wichtig:
Bitte keine bekannten Sätze oder Zitate nutzen!

Beispiel für eine Passphrase mit einer Passwortlänge von 36 Zeichen wäre:
>Haus!-Apfel-Auto-G0rilla-Advent5kranz-3Walnuss


## Wie merke ich mir ein Passwort?

Passphrasen sind definitiv zu bevorzugen, da diese meist länger sind als Passwörter, aber auch Passwörter kann man sich mit einer einfachen Methode merken.

Erstellen einen Satz wie:

***M**eine **H**eizung **f**unktioniert **i**m **W**inter **n**icht **u**nd **d**as **f**ind **i**ch **t**otal **d**oof **v**on **m**einem **V**ermieter*

Nimmt man jeden ersten Buchstaben eines Wortes, bekommt man folgendes Passwort:

*MHfiWnudfitdvmV*

Nun könnten noch einige Buchstaben durch Zahlen oder Sonderzeichen ersetzt werden und man hat ein solides Passwort generiert, welches man sich darüber hinaus noch gut merken kann.
Bitte immer daran denken: Je länger desto besser!

---

## Warum sind lange Passwörter besser als komplexe Passwörter?

Dieses comic von XKDC zeigt es schnell und einfach (leider nur auf englisch):

{{< figure src="password_strength.png"
width="100%"
caption="Password Strength by xkcd"
link=https://xkcd.com/936
target="_blank"
alt="xkcd Comic über Passwortstärke"
>}}

Immer wieder wird uns gesagt, dass ein Passwort sicher sein soll.
Mindestens eine Zahl, auf jeden Fall 2 Sonderzeichen, Groß- und Kleinbuchstaben.
Was passiert?
Man nimmt einen Begriff (häufig den eigenen Namen oder den des Partners, der Kinder etc.), tauscht ein paar Buchstaben durch Sonderzeichen und Zahlen aus oder hängt sie lediglich vorne und hinten an den Begriff und schon ist das Passwort fertig.

Dann wird aus **Andrej** schnell **AnDr3|!** oder **!Andrej456** und schnell tritt der Glaube auf, dass sei ein sicheres Passwort.

Leider ist dies meist begriffsbedingt (Namen sind selten länger als 8 Zeichen) auch ein ziemlich kurzes Passwort und somit auch dementsprechend unsicher.
Dazu kommt, dass ich nicht der einzige mit diesem Namen bin und jemand anderes dieses Passwort schon nutzt?
An sich ist das nicht schlimm, aber dadurch steigt die Wahrscheinlichkeit, dass dieses Passwort irgendwann in einer Passwortdatenbank landet.

### Warum sind denn jetzt lange Passwörter besser als komplexe aber kurze Passwörter?

Eine sehr gute Erklärung gibt es von Heiko Schröder.
Bei Interesse kann hier der ganze Artikel direkt gelesen werden: [Zusammenhang von Brute-Force-Attacken und Passwortlängen](https://www.1pw.de/brute-force.php)

Zusammengefasst und veranschaulicht gibt er folgendes Beispiel:

Die Formel um alle Kombinationsmöglichkeiten von Zeichen zu bekommen ist wie folgt:

**Kombinationsmöglichkeiten = Zeichenanzahl<sup>Passwortlänge</sup>**

Bei einem Passwort von 7 Zeichen und 26 verschiedenen Kleinbuchstaben (ä,ö,ü,ß ausgeschlossen) gibt es folgende Anzahl an Kombinationsmöglichkeiten:

Kombinationen = 26 <sup>7</sup> <br>
              = 26 * 26 * 26 * 26 * 26 * 26 * 26 <br>
              = 8.031.810.176

Gleiche Zeichenanzahl aber eine Passwortlänge von 8 anstatt 7:

Kombinationen = 26 <sup>8</sup><br>
              = 26 * 26 * 26 * 26 * 26 * 26 * 26 * 26<br>
              = 208.827.064.576 (Mehr als 208 Milliarden) <br>

Es ist also klar: die Passwortlänge hat einen unfassbar großen Einfluss auf die Kombinationsmöglichkeiten.
Je länger das Passwort desto großer die Kombinationsmöglichkeiten und desto schwieriger ist es dieses zu erraten oder einfach auszuprobieren.
Die Zeichen sind nur begrenzt erweiterbar, schließlich sind irgenwann alle Zeichen auf der Tastatur enthalten (Großbuchstaben, Sonderzeichen und Ziffern).
Die Passwortlänge hingegen ist unendlich (theoretisch) erweiterbar und lässt die Kombinationsmöglichkeiten in die Höhe schnellen.

Warum ist das wichtig?  
Computer sind in den letzten Jahren immer Leistungsfähiger geworden und können unvorstellbar viele Rechenoperationen pro Sekunde durchführen.
Wir rechnen mit 2.147.483.600 Passwörtern pro Sekunden, die ein Computer ausprobiert kann. (Stand 2016) [^1].

Ein Computer braucht für ein Passwort mit der Passwortlänge von 7 Zeichen nur <br>**8.031.810.176 Kombinationen / 2.147.483.600 Passwörter/sec <br>= 3,74 Sekunden**, um alle Passwortkombinationen auszuprobieren.

Für ein Passwort mit einer Passwortlänge von 8 Zeichen sind es <br>**208.827.064.576 Kombinationen / 2.147.483.600 Passwörter/sec <br>= 97 Sekunden <br>= mehr als 1,5 Minuten**.

Für längere Passwörter brauchen Computer einfach länger, um diese zu "knacken".

### Wie lang sollen Passwörter denn sein?

Das ist also nun die Gretchenfrage: Eindeutig und pauschal ist das nicht zu beantworten, da dabei noch weitere Fakrotren eine Rolle spielen.
Das BSI für Bürger empfielt mindestens 8 Zeichen [^2].
Das finde ich persönlich etwas wenig, da man solch ein Passwort mit bspw. einer Zeichenanzahl von 62 (Groß- und Kleinbuchstaben sowie Ziffern) und einer Passwortlänge von 8 Zeichen in 1,18 Tagen durch stupides "ausprobieren" herausbekommen könnte.

{{% alert dark %}}
Exkurs:  
Natürlich kann niemand sich jetzt einfach 2 Tage hinsetzten und alle Passwörter der Welt bei einem Dienst ausprobieren.
Dafür gibt es noch weitere Sicherheitsmechanismen auf Seiten des Dienstes.
Zum Beispiel hat man nur 3 Versuche und dannach muss man sich wieder freischalten.
Auch ist es möglich, dass das IT System von dem Dienst diese Versuche erkennt und die Anmeldung von diesen Geräten erstmal sperrt und den echten Benutzer per E-Mail oder SMS benachrichtigt.
{{% /alert %}}

Und je nach Benutzer und Relevanz des Erfolges ein solches Passwort zu knacken ist das ein vertretbarer Auswand.
Daher würde ich eine Passwortlänge von mindestens 12 Zeichen empfehlen.
Mit Groß- und Kleinbuchstaben sowie Ziffern bräuchte ein Computer dafür **47639,13 Jahre**.

Das ist defintiv kein vertretbarer Aufwand.
Für dich also ein Grund mehr sich für eine Passphrase anstatt kurzes und komplexes Passwort zu entscheiden.

## Warum persönliche Daten in Passwörtern nichts verlorgen haben

Beim Thema Sicherheit geht es generell immer um das Risko.
100%ige Sicherheit gibt es nicht, wer das verspricht lügt schlicht und ergreifend.
Das Risiko für die jeweilige Person ist dabei immer unterschiedlich.

Personen, die sowieso in der öffentlichkeit stehen und dadruch viele Informationen über sich für Dritte einsehbar machen, sind potenziell gefährdeter als der der Otto Normal Verbraucher.
Das Risiko, dass Dritte auf sensible Daten Zugriff haben wollen steigt (Attraktivität der Daten) und durch die vielen frei auffindbaren Informationen auch das Risiko, dass (schlechte) Passwörter schneller geknackt werden können.

Durch soziale Netzwerke, Hobbyseiten, etc. lässt sich allerdings über fast jeden sehr viel herausfinden.
Facebook Likes auf einer Bandseite, Fotos von Konzerten, ein Foto vom Haustier mit Namen, Geburtstagsgrüße auf der Pinnwand, Lieblingsurlaubsziele und und und.
Schon kann die Passwortliste möglicher Passwörter erstellt werden.

Das Interesse an Personen und dadruch das Risiko sind natürlich sehr verschieden.

Wird das Facebook Passwort einer Schülerin herausgefunden, können sich Mitschüler einen Scherz in ihrem Namen erlauben.
Bei einem CEO eines großen Unternehmens hingegen kommt man eventuell sogar an seinen E-Mail Account und kann Geschäftsprozesse und sensible Daten einsehen oder Überweisung anfordern.

Egal wie hoch das Riskoprofil ist und welche Auswirkungen das haben könnte: Niemand möchte seine Daten gerne aus der Hand geben oder die Kontrolle über ihre Verbreitung verlieren.

Daher gilt:

{{% alert warning %}}
Persönliche Daten sind in Passphrase und Passwort absolut Tabu
{{% /alert %}}

## Warum Passwörter nicht wiederverwendet werden dürfen

Heutzutage ist man bei unzähligen Diensten angemeldet.
Sei es soziale Netzwerke (Facebook, Twitter, Instagram), Foren, Onlineshops (Amazon, eBay, etc.), Onlinebanking und viel mehr.

Das selbe Passwort bei allen Diensten zu verwenden ist grob fahrlässig und das größte Problem für den Privatnutzer.
Denn auch wenn das Passwort sicher ist, muss es nur einmal geleakt werden und schon sind alle Dienste derjenigen Person in Gefahr.

Dann ist der Aufwand enorm groß *alle* Passwörter zu ändern.
Daher ist es so wichtig, immer ein anderes Passwort für unterschiedliche Seiten und Dienste zu verwenden.

Ist etwas Unklar?  
Habt ihr sonstige Fragen?  
Schreibt diese einfach unten in die Kommentare oder schreibt eine Mail an [kontakt@technik-tip.de](mailto:kontakt@technik-tip.de)

## Quellen

[^1]: [Zusammenhang von Brute-Force-Attacken und Passwortlängen](https://www.1pw.de/brute-force.php)

[^2]: [BSI für Bürger: Passwörter](https://www.bsi-fuer-buerger.de/BSIFB/DE/Empfehlungen/Passwoerter/passwoerter_node.html)