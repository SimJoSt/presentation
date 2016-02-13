# Funktionsweise


## 2 Knoten verbinden sich untereinander, wenn sie sich in Funkreichweite befinden
sie *„meshen“*


## generell können sich unbegrenzt viele Knoten dazugesellen
sie bilden eine große „Wolke“, eine „Mesh“


## nicht alle Knoten müssen sich gleichzeitig sehen
sie kommunizieren über die anderen Knoten

Daten werden weitergeleitet


## jede Art von Datenkommunikation kann darüber getätigt werden
* Websiten
* E-Mail
* Chat
* Telefonie
* Spiele
* Austausch von Dateien


# größere Flächen
## Problem:
nicht alle Knoten sind mit dem Mesh verbunden, da sie nicht in Funkreichweite sind

## Lösung:
### Gateways schließen die Lücke
Knoten mit Internetzugang, verbinden sich mit Gateways

kommunizieren so mit allen anderen Knoten


# fehlendes Internet
## Problem:
jeder, der Freifunk nutzt, kann gleichzeitig keine Dienste aus dem Internet verwenden

## Lösung:
### Internetzugang an Gateways
Knoten mit einer Verbindung zu den Gateways, kommen über sie ins Internet


# Störerhaftung
## Problem:
kein Problem für Knotenbetreiber, da sie keinen Internetzugang stellen

Problem für Gatewaybetreiber, alle Missbrauchsanfragen landen bei ihnen

## Lösungsansätze
* Verschleierung
* Ausland
* Providerprivileg


## Verschleierung
Nutzung eines VPN-Anbieters, verschleiert die Identität

Grauzone, Nutzung des Dienstes legal, Verschleierung von Straftaten nicht legal, jedoch keine geplanten Straftaten

## Ausland
Nutzung eines VPN-Anbieters, Ausgangspunkt in einem Land, in welchem es die Störerhaftung nicht gibt

Grauzone, Nutzung des Dienstes legal, **Umgehung** der Störerhaftung, obwohl Nutzung aus Deutschland **= Umgehung** des deutschen Rechtes


# Providerprivileg
## Provider von Störerhaftung frei
darunter fallen Telekom, Vodafon, …

> Diensteanbieter sind für fremde Informationen, die sie in einem Kommunikationsnetz übermitteln oder zu denen sie den Zugang zur Nutzung vermitteln, nicht verantwortlich, sofern sie […]

Quelle: [Telemediengesetz](http://www.gesetze-im-internet.de/tmg/index.html)


# Providerpflicht
## Provider müssen protokollieren
Die Vorratsdatenspeicherung …

* … ist für Freifunk-Netze nicht umsetzbar, da „Kunden“ nicht bekannt sind.
* … widerspricht ferner dem Datenschutzverständnis des Freifunk-Projekts.


# Providerstatus
## über RIPE-Mitgliedschaft
zu erlangen als Privatperson, Firma oder Verein

## basiert auf Auslegung
teilweise werden Freifunker von Gerichten schon jetzt direkt als Provider angesehen

in Zukunft evlt. im Gesetz verankert


# Fazit:
## Providerprivileg ist die bevorzugte Lösung
solange die Störerhaftung besteht

bei Abschaffung würde jeder Knoten seinen eigenen Uplink direkt verwenden


# nicht alle Dienste
## Problem:
Im Bremer Freifunk-Netz kann ich nur Geräte und Dienste aus Bremen erreichen

## Lösung:
### InterCity-VPN
stellt über die Gateways eine VPN-Verbindung zu allen anderen Communities her
