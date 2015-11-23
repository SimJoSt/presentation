# eingesetzte Technik


# gluon
* die Software, auf welcher die Bremer Firmware basiert
* haupts&auml;chlich in L&uuml;beck entwickelt
* baut auf OpenWRT auf, ein Linux für Kleinger&auml;te


# Mesh-Protokoll
## gluon nutzt B.A.T.M.A.N.
es ist daf&uuml;r zust&auml;ndig, dass alle Knoten wissen, wohin Daten &uuml;bertragen werden m&uuml;ssen


# VPN-Verbindungen
## Verbindung zu Gateways mit fastd
**fastd** ist ein ressourcensparendes VPN-Protkoll, welches die Knoten nicht &uuml;berm&auml;&szlig;ig belastet


# InterCity-VPN
## tinc verbindet alle Communities
**tinc** ist ein weiteres VPN-Protokoll. &Uuml;ber dieses verbinden sich alle Freifunk Communities untereinander
