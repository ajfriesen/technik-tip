---
title: 'Sichere Passwörter'
date: 2019-11-11
categories: ["Passwörter"]
tags: [ "" ]
draft: false
weight:
image:
author: "Andrej Friesen"
slug: sichere-passwoerter
---

Passwörter sind nervig, aber notwendig.
Hier erfahren Sie was sichere Passwörter sind und worauf Sie bei der Erstellung von Passwörtern lieber verzichten sollten.

<!---more-->
---

# Das wichtigste in Kürze

Das sollten Sie tun:

* :white_check_mark: Passwortmanager nutzen
* :white_check_mark: Lange Passwörter sind sicherer als komplexe Passwörter
* :white_check_mark: Passphrasen anstatt Passwörter
* :white_check_mark: Eine Passwortlänge von mindestens 12 Zeichen

Das sollten Sie auf keinen Fall tun:

* :x: Das selbe Passwort auf mehreren Seiten verwenden
* :x: Persönliche Daten nutzen:
  * :x: Namen (Kinder, Haustiere, Eltern, etc.)
  * :x: Wohnorte
  * :x: Geburtsdaten
  * :x: Sonstige perönliche und öffentlich auffindbare Informationen über Sie (Fußballverein, etc.)
* :x: Tastaturmuster wie ASDF, 1234, jklö nutzen


# So gehen Sie vor

Passwortmanager nutzen (Artikel folgt)

## Passphrase erstellen

Passphrasen stellen aneinandergereihte Worte dar.
Sinnvoll ist es, 5 bis 6 Wörter ohne semantischen Zusammenhang aneinander zu reihen und eventuell mit Sonderzeichen zu verknüpfen.
Je sinnloser, desto besser.
Dabei können und sollten ein bis zwei Buchstaben durch Ziffern austauausgetauscht werden, da dies von zahlreichen Diensten zur Erfassung des Passwortes ohnehin gefordert wird.
Die Wörter aus der Passphrase können auch aus verschiedenen Sprachen kommen.
Seien Sie kreativ.

Wichtig:
Keine bekannten Sätze oder Zitate nutzen!

Eine Passphrase mit einer Passwortlänge von 36 Zeichen wäre:
Haus-Apfel-Auto-Gorilla-Adventskranz-Walnuss

Schon haben Sie ein sehr langes Passwort welches schwer zu knacken und dazu noch einfacher zu merken ist als eine bloße Aneinanderreihung von Buchstaben, Zahlen und Sonderzeichen.

## Komplexes Passwort merken

Passphrasen sind definitiv zu bevorzugen, da diese meist länger sind als Passwörter, aber auch Passwörter kann man sich mit einer einfachen Methode merken.

Erstellen Sie einen Satz wie:

***M**eine **H**eizung **f**unktioniert **i**m **W**inter **n**icht **u**nd **d**as **f**ind **i**ch **t**otal **d**oof **v**on **m**einem **V**ermieter*

Nimmt man jeden ersten Buchstaben eines Wortes, bekommt man folgendes Passwort:

*MHfiWnudfitdvmV*

Nun könnten noch einige Buchstaben durch Zahlen oder Sonderzeichen ersetzt werden und man hat ein solides Passwort generiert, welches man sich darüber hinaus noch gut merken kann.

---

# Warum sind lange Passwörter besser als komplexe Passwörter?

Dieses comic von XKDC zeigt es schnell und einfach (leider nur auf englisch):

{{< figure src="./password_strength.png"
width="100%"
caption="Password Strength by xkcd"
link=https://xkcd.com/936
target="_blank"
>}}

Immer wieder wird uns gesagt, dass ein Passwort sicher sein soll.
Mindestens eine Zahl, auf jeden Fall 2 Sonderzeichen, Groß- und Kleinbuchstaben.
Was passiert?
Man nimmt einen Begriff (häufig den eigenen Namen oder den des Partners, der Kinder etc.), tauscht ein paar Buchstaben durch Sonderzeichen und Zahlen aus oder hängt sie lediglich vorne und hinten an den Begriff und schon ist das Passwort fertig.

Dann wird aus **Andrej** schnell **AnDr3|!** oder **!Andrej456** und schnell tritt der Glaube auf, dass sei ein sicheres Passwort.

Leider ist dies meist begriffsbedingt (Namen sind selten länger als 8 Zeichen) auch ein ziemlich kurzes Passwort und somit auch dementsprechend unsicher.
Ganz so einfach sollte man es sich also aus diesen obigen Sicherheitsgründen nicht machen.

## Warum sind denn jetzt lange Passwörter besser als komplexe aber kurze Passwörter?

Eine sehr gute Erklärung gibt es von Heiko Schröder [^1].
Bei Interesse kann hier der ganze Artikel direkt gelesen werden: [Zusammenhang von Brute-Force-Attacken und Passwortlängen](https://www.1pw.de/brute-force.php)[^1]

Zusammengefasst und veranschaulicht gibt er folgendes Beispiel:

Die Formel um alle Kombinationsmöglichkeiten zu bekommen ist wie folgt:

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
Je länger das Passwort desto großer die Kombinationsmöglichkeiten und desto sicherer ist das Passowort.
Die Zeichen sind nur begrenzt erweiterbar, schließlich sind irgenwann alle Zeichen auf der Tastatur enthalten ( Großbuchstaben, Sonderzeichen und Ziffern).
Die Passwortlänge hingegen ist unendlich erweiterbar und lässt die Kombinationsmöglichkeiten in die Höhe schnellen.

Warum ist das wichtig?
Computer sind in den letzten Jahren immer Leistungsstärker geworden und können unvorstellbar viele Rechenoperationen pro Sekunde durchführen.
Wir rechnen mit 2.147.483.600 Passwörtern pro Sekunden, die ein Computer ausprobiert kann. (Stand 2016) [^1].

Damit braucht ein Rechner für ein Passwort mit der Passwortlänge von 7 Zeichen nur <br>**8.031.810.176 Kombinationen / 2.147.483.600 Passwörter/sec <br>= 3,74 Sekunden**.

Für ein Passwort mit einer Passwortlänge von 8 Zeichen sind es <br>**208.827.064.576 Kombinationen / 2.147.483.600 Passwörter/sec <br>= 97 Sekunden <br>= mehr als 1,5 Minuten**.

Für längere Passwörter brauchen Computer einfach länger, um diese zu knacken.

### Wie lang sollen Passwörter denn sein?

Das ist also nun die Gretchenfrage: Eindeutig und pauschal ist sie nicht zu beantworten, da dabei noch weitere Fakrotren eine Rolle spielen.
Das BSI für Bürger empfielt mindestens 8 Zeichen [^2].
Das finde ich persönlich etwas wenig, da man solch ein Passwort mit bspw. einer Zeichenanzahl von 62 (Groß- und Kleinbuchstaben sowie Ziffern) und einer Passwortlänge von 8 Zeichen in 1,18 Tagen durch stupides "ausprobieren" herausbekommen kann.

Und je nach Benutzer und Relevanz des Erfolges ein solches Passwort zu knacken ist das ein vertretbarer Auswand.
Daher würde ich eine Passwortlänge von mindestens 12 Zeichen empfehlen, die mit der obigen Methode schnell zusammenkommen können.
Mit Groß- und Kleinbuchstaben sowie Ziffern bräuchte ein Computer dafür **47639,13 Jahre**.

Das aus rein wirtschaftlicher Sicht bereits alles andere als ein vertretbarer Aufwand für denjenigen, der es knacken möchte.
Für Sie also ein Grund mehr sich für ein längeres anstatt kurzes und komplexes Passwort zu entscheiden.

# Warum persönliche Daten in Passwörtern nichts verlorgen haben

Beim Thema Sicherheit geht es generell immer um das Risko.
100%ige Sicherheit gibt es nicht, wer das verspricht lügt schlicht und ergreifend.
Das Risiko für die jeweilige Person ist dabei immer unterschiedlich.

Personen, die sowieso in der öffentlichkeit stehen und dadruch viele Informationen über sie für Dritte einsehbar sind, sind potenziell gefährdeter als der Normalo.
Das Risiko, dass Dritte auf sensible Daten Zugriff haben wollen steigt (Attraktivität der Daten) und durch die vielen frei auffindbaren Informationen auch das Risiko, dass (schlechte) Passwörter schneller geknackt werden können.

Durch soziale Netzwerke, Hobbyseiten und co lässt sich allerdings über fast jeden sehr viel herausfinden.
Facebook Likes auf einer Bandseite, Fotos von Konzerten, ein Foto vom Haustier mit Namen, Geburtstagsgrüße auf der Pinnwand, Lieblingsurlaubsziele und und und.
Schon kann die Passwortliste Dritter erweitert werden, mit der der Copmuter dann versucht mögliche Kombinationen zu finden.

Das Interesse an Personen und dadruch das Risiko sind natürlich sehr verschieden.

Wird das Facebook Passwort einer Schülerin herausgefunden, können sich Mitschüler einen Scherz in ihrem Namen erlauben.
Bei einem CEO eines großen Unternehmens hingegen kommt man eventuell sogar an seinen E-Mail Account und kann Geschäftsprozesse und sensible Daten einsehen oder Überweisung anfordern.

Egal wie hoch das Riskoprofil ist und welche Auswirkungen das haben könnte: Niemand möchte seine Daten gerne aus der Hand geben oder die Kontrolle über ihre Verbreitung verlieren.

Daher gilt:

**Persönliche Daten sind im Passwort Tabu**

# Warum Passwörter nicht wiederverwendet werden dürfen

Heutzutage ist man bei unzähligen Diensten angemeldet.
Seien es soziale Netzwerke (Facebook, Twitter, Instagram), Foren, Onlineshops (Amazon, eBay, etc.), Onlinebanking und viele mehr.

Das selbe Passwort bei allen Diensten zu verwenden ist grob fahrlässig und das größte Problem für den Privatnutzer.
Denn auch wenn das Passwort sicher ist, muss es nur einmal geknackt oder geleakt werden und schon sind alle Dienste derjenigen Person in Gefahr.

Dann ist der Aufwand enorm groß *alle* Passwörter zu ändern.
Daher ist es so wichtig, immer ein anderes Passwort für unterschiedliche Seiten und Dienste zu verwenden.

# Quellen

[^1]: [Zusammenhang von Brute-Force-Attacken und Passwortlängen](https://www.1pw.de/brute-force.php)

[^2]: [BSI für Bürger: Passwörter](https://www.bsi-fuer-buerger.de/BSIFB/DE/Empfehlungen/Passwoerter/passwoerter_node.html)