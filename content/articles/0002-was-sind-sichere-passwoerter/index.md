---
title: 'Sichere Passwörter'
date: 2019-08-01
categories: ["Passwörter"]
tags: [ "" ]
draft: false
weight:
image:
author: "Andrej Friesen"
slug: sichere-passwoerter
---

Passwörter sind nervig, aber notwendig.
Hier erfahren Sie was sichere Passwörter sind.

<!---more-->
---

# Das wichtigste in Kürze

Das sollten Sie tun:

* :white_check_mark: Passwortmanager nutzen
* :white_check_mark: Lange Passwörter sind sicherer als komplexe Passwörter
* :white_check_mark: Passphrasen anstatt Passwörter
* :white_check_mark: Mindestens 12 Zeichen

Das sollten Sie auf jeden Fall lassen:

* :x: Das selbe Passwort auf mehreren Seiten verwenden
* :x: Persönliche Daten nutzen,wie:
  * :x: Namen (Kinder, Haustiere, Eltern, etc.)
  * :x: Wohnorte
  * :x: Geburtsdaten
  * :x: Sonstige perönlich öffenltich auffindbare Informationen (Fußballverein, etc.)
* :x: Tastaturmuster wie ASDF, 1234, jklö nutzen


# So gehen Sie vor

1. Passwortmanager nutzen (Artikel folgt)

## Passphrase erstellen

5 bis 6 Wörter ohne Sinn aneinander reihen und eventuell mit Sonderzeichen verknüpfen bzw. noch ein oder zwei Buchstaben durch Ziffern austauschen, da dies von einigen Diensten gefordert wird.
Die Wörter können auch aus verschiedenen Sprachen kommen.
Seien Sie Kreativ.

Keine bekannten Sätze oder Zitate nutzen!

Eine Passphrase mit einer Passwortlänge von 36 Zeichen
: Haus-Apfel-Auto-Gorilla-Adventskranz-Walnuss

Schon haben Sie ein sehr lange Passwort welches schwer zu knacken ist und dazu noch einfach zu merken.

## Komplexes Passwort merken

Passphrasen sind definitiv zu bevorzugen, da diese meist länger sind als Passwörter, aber auch Passwörter kann man sich mit einer Methode merken.

Erstellen Sie einen Satz wie:

***M**eine **H**eizung **f**unktioniert **i**m **W**inter **n**icht **u**nd **d**as **f**ind **i**ch **t**otal **d**oof **v**on **m**einem **V**ermieter*

Jetzt kann mein zum Beispiel die Regel nehmen, dass man jeden ersten Buchstaben nimmt:

*MHfiWnudfitdvmV*

Jetzt könnten noch einige Buchstaben durch Zahlen oder Sonderzeichen ersetzt werden und man hat ein solides Passwort.

---

# Warum sind lange Passwörter besser als komplexe Passwörter?

Dieses comic von XKDC zeigt es schnell und einfach (leider nur auf englisch):

{{< figure src="./password_strength.png"
width="100%"
caption="Password Strength by xkcd"
link=https://xkcd.com/936
target="_blank"
>}}

Über die Jahre wurde uns gesagt, dass ein Passwort sicher sein soll.
Mindestens eine Zahl, auf jeden Fall 2 Sonderzeichen, Groß- und Kleinbuchstaben. Dann hat man meist einen Begriff (häufig den Namen) genommen, ein paar Buchstaben durch Sonderzeichen und Zahlen ausgetauscht und schon war das Passwort fertig.

Dann wird aus **Andrej** schnell **AnDr3|!** und schnell tritt der Glaube auf, dass sei ein sicheres Passwort.

Leider ist dies meist auch ein kurzes Passwort, da Namen meist kurz sind und schwer zu merken.
Schade, denn das Passwort ist alles andere als gut.

## Warum sind denn jetzt lange Passwörter besser als komplexe Passwörter?

Eine sehr gute Erklärung gibt es von Heiko Schröder [^1].

Da das wirklich schon gut aufbereitet worden ist gibt es hier nur eine kurze Zusammenfassung:

Die Formel um alle Kombinationsmöglichkeiten zu bekommen ist wie folgt:

**Kombinationsmöglichkeiten = Zeichenanzahl<sup>Passwortlänge</sup>**

Bei einem Passwort von 7 Zeichen und 26 verschiedenen Kleinbuchstaben (ä,ö,ü,ß ausgeschlossen) gibt es folgende Anzahl Kombinationsmöglichkeiten:

Kombinationen = 26 <sup>7</sup> <br>
              = 26 * 26 * 26 * 26 * 26 * 26 * 26 <br>
              = 8.031.810.176

Gleiche Zeichenanzahl aber eine Passwortlänge von 8 anstatt 7:

Kombinationen = 26 <sup>8</sup><br>
              = 26 * 26 * 26 * 26 * 26 * 26 * 26 * 26<br>
              = 208.827.064.576 (Mehr als 208 Milliarden) <br>

Es ist klar zu sehen, dass die Passwortlänge einen unfassbar großen Einfluss auf die Kombinationsmöglichkeiten hat.
Der Einfluss ist weit aus größer als der der Zeichenanzahl.
Die Zeichenanzahl ist auch nur begrenzt erweiterbar.
Schließlich sind irgenwann alle Zeichen auf der Tastatur wie Großbuchstaben, Sonderzeichen und Ziffern in der Zeichenanzahl enthalten.
Die Passwortlänge hingegen ist unendlich erweiterbar und bringt viel mehr im Bezug auf die Anzahl der Kombinationsmöglichkeiten.

Warum ist das wichtig?
Computer sind in den letzten Jahren immer Leistungsstärker geworden und können unfassbar viele Rechenoperationen pro Sekunde durchführen.
Wir rechnen mit 2.147.483.600  Passwörter pro Sekunden, die der Computer ausprobiert kann. (Stand 2016) [^1].

Damit braucht ein Rechner für ein Passwort mit der Passwortlänge von 7 Zeichen nur <br>**8.031.810.176 Kombinationen / 2.147.483.600 Passwörter/sec <br>= 3,74 Sekunden**.

Für ein Passwort mit einer Passwortlänge von 8 Zeichen  sind es <br>**208.827.064.576 Kombinationen / 2.147.483.600 Passwörter/sec <br>= 97 Sekunden <br>= mehr als 1,5 Minuten**.

Für längere Passwörter brauchen Computer einfach länger, um diese zu knacken.

### Wie lang sollen Passwörter denn sein?

Das ist nicht ganz eindeutig, da dabei noch mehr Fakrotren eine Rolle spielen.
Das BSI für Bürger emphielt mindestens 8 Zeichen [^2].
Das finde ich persönlich etwas wenig, da man solch ein Passwort in 1,18 Tagen durch stupides ausprobieren errarten kann.
Also mit einer Passwortlänge von 8 und Zeichenzahl von 62 (Groß- Kleinbuchstaben & Ziffern).

Das ist in meinen Augen schon vertretbarer Aufwand. 
Daher würde ich eher in die Richtung von mindestens 12 Zeichen tendieren.
Mit Groß- und Kleinbuchstaben und Ziffern bräuchte ein Computer **47639,13 Jahre**.

Das ist alles andere als vertretbarer Aufwand.
Zudem gibt es Methoden, wie man sich solche Passwörter sehr einfach erstellen und merken kann.

# Warum persönliche Daten in Passwörtern nichts verlorgen haben

Generell beim Thema Sicherheit geht es immer um Risko.
100%ige Sicherheit gibt es nicht, wer das verspricht lügt schlicht und ergreifend.
Das Risiko für eine Person ist dabei immer unterschiedlich.

Personen, die sowieso in der öffentlichkeit stehen und dadruch viele Daten für andere einsehbar haben, teilweise sogar auf Wikipedia, haben ein Potentiell größeres Risiko.
Einfach schon dadurch, dass eventuell mehr Leute diesen Schaden wollen.
Eventuell auch, dass es sich mehr lohnt, als beim Nachbarn.

Durch soziale Netzwerke, Hobbyseiten und so weiter lässt sich allerdings sehr viel über fast jeden herausfinden.
Facebook Likes auf eine Band, Fotos von Konzerten, ein Foto vom Haustier mit Namen, Geburtstagsgrüße auf der Pinnwand.
Schon kann die Passwortliste erweitert werden mit der der Copmuter versucht Kombinationen zu finden.

Das Interessa an Personen und dadruch das Risiko sind natürlich sehr verschieden.

Wird das Facebook Passwort einer Schülerin herausgefunden, können sich Mitschüler einen Scherz in ihrem Namen erlauben.
Bei einem CEO eines großen Unternehmens kommt man eventuell an seinen E-Mail Account und kann Geschäftsprozesse einsehen oder Überweisung anordern.

Egal wie hoch das Riskoprofil ist und welche Auswirkungen das haben könnte, niemand will seine Daten außer Hand lassen.

Daher gilt:

**Persönliche Daten sind im Passwort Tabu**

# Warum Passwörter nicht wiederverwendet werden dürfen

Heutzutage ist man bei unzähligen Diensten angemeldet.
Sei es soziale Netzwerke (Facebook, Twitter, Instagram), Foren,Onlineshops (Amazon, eBay, etc.) Onlinebanking und vieles mehr.

Das selbe Passwort bei allen Diensten zu haben ist das größte Problem für den Privatnutzer.
Denn auch wenn das Passwort sicher ist, muss es nur einmal geknackt oder geleakt werden und schon sind alle Dienste derjenigen Person in Gefahr.

Dann ist der Aufwand enorm groß *alle* Passwörter zu ändern.
Daher immer ein anderes Passwort pro Dienst nutzen.

# Quellen

[^1]: [Zusammenhang von Brute-Force-Attacken und Passwortlängen](https://www.1pw.de/brute-force.php)

[^2]: [BSI für Bürger: Passwörter](https://www.bsi-fuer-buerger.de/BSIFB/DE/Empfehlungen/Passwoerter/passwoerter_node.html)