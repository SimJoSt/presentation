# Funktionsweise


## 2 Knoten verbinden sich untereinander, wenn sie sich in Funkreichweite befinden
sie *"meshen"*


## generell k&ouml;nnen sich unbegrenzt viele Knoten dazugesellen
sie bilden eine gro&szlig;e "Wolke", eine "Mesh"


## nicht alle Knoten m&uuml;ssen sich gleichzeitig sehen
sie kommunizieren &uuml;ber die anderen Knoten

Daten werden weitergeleitet


## jede Art von Datenkommunikation kann dar&uuml;ber get&auml;tigt werden
* Websiten
* E-Mail
* Chat
* Telefonie
* Spiele
* Austausch von Dateien


# gr&ouml;&szlig;ere Fl&auml;chen
## Problem:
nicht alle Knoten sind mit dem Mesh verbunden, da sie nicht in Funkreichweite sind

## L&ouml;sung:
### Gateways schlie&szlig;en die L&uuml;cke
* Knoten mit Internetzugang, verbinden sich mit Gateways
* kommunizieren so mit allen anderen Knoten


# fehlendes Internet
## Problem:
jeder, der Freifunk nutzt, kann gleichzeitig keine Dienste aus dem Internet verwenden

## L&ouml;sung:
### Internetzugang an Gateways
Knoten mit einer Verbindung zu den Gateways, kommen ins Internet


# St&ouml;rerhaftung
## Problem:
* kein Problem f&uuml;r Knotenbetreiber
  * sie stellen keinen Internetzugang
* Problem f&uuml;r Gatewaybetreiber
  * alle Missbrauchsanfragen landen bei ihnen

## L&ouml;sungsans&auml;tze
* Verschleierung
* Ausland
* Providerprivileg


## Verschleierung
* Nutzung eines VPN-Anbieters, verschleiert die Identit&auml;t
* Grauzone, Nutzung des Dienstes legal, Verschleierung von Straftaten nicht legal, jedoch keine geplanten Straftaten

## Ausland
* Nutzung eines VPN-Anbieters, Ausgangspunkt in einem Land, in welchem es die St&ouml;rerhaftung nicht gibt
* Grauzone, Nutzung des Dienstes legal, **Umgehung** der St&ouml;rerhaftung, obwohl Nutzung aus Deutschland **= Umgehung** des deutschen Rechtes


# Providerprivileg
## Provider von St&ouml;rerhaftung frei
darunter fallen:
* Telekom
* Vodafon
* etc...

> Diensteanbieter sind f&uuml;r fremde Informationen, die sie in einem Kommunikationsnetz &uuml;bermitteln oder zu denen sie den Zugang zur Nutzung vermitteln, nicht verantwortlich, sofern sie [...]

Quelle: [Telemediengesetz](http://www.gesetze-im-internet.de/tmg/index.html)


# Providerstatus
## &uuml;ber RIPE-Mitgliedschaft zu erlangen als:
* Privatperson
* Firma
* Verein

## basiert auf Auslegung
* teilweise werden Freifunker von Gerichten schon direkt als Provider angesehen
* in Zukunft evlt. im Gesetz verankert


# Fazit:
## St&ouml;rerhaftung
* Providerprivileg ist die bevorzugte L&ouml;sung


# nur Dienste aus der eigenen Community
## Problem:
Im Bremer Freifunk-Netz kann ich nur Ger&auml;te und Dienste aus Bremen erreichen.

## L&ouml;sung:
### InterCity-VPN
stellt &uuml;ber die Gateways eine VPN-Verbindung zu allen anderen Communities her
