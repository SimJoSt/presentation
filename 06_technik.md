# eingesetzte Technik


# gluon
die Software, auf welcher die Bremer Firmware basiert

haupts&auml;chlich in L&uuml;beck entwickelt

baut auf OpenWRT auf, ein Linux f&uuml;r Kleinger&auml;te


# Mesh-Protokoll
## gluon nutzt B.A.T.M.A.N.
daf&uuml;r zust&auml;ndig, dass alle Knoten wissen, wohin Daten auf welchem Wege &uuml;bertragen werden m&uuml;ssen


# VPN-Verbindungen
## Verbindung zu Gateways mit fastd
**fastd** ist ein ressourcensparendes VPN-Protkoll, welches die Knoten trotz schwacher CPU nicht &uuml;berm&auml;&szlig;ig belastet


# InterCity-VPN
## tinc verbindet alle Communities
**tinc** ist ein weiteres VPN-Protokoll

&uuml;ber eine Liste von Gegenstellen verbindet es sich automatisch mit allen Communities
