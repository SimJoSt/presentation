# eingesetzte Technik


# gluon
die Software, auf welcher die Bremer Firmware basiert

hauptsächlich in Lübeck entwickelt  
baut auf OpenWRT/LEDE auf, ein Linux für Kleingeräte


# Mesh-Protokoll
## gluon nutzt B.A.T.M.A.N.
dafür zuständig, dass alle Knoten wissen, wohin Daten auf welchem Wege übertragen werden müssen


# VPN-Verbindungen
## Verbindung zu Gateways mit fastd
**fastd** ist ein ressourcensparendes VPN-Protkoll, welches die Knoten trotz schwacher CPU nicht übermäßig belastet


# InterCity-VPN
## tinc verbindet alle Communities
**tinc** ist ein weiteres VPN-Protokoll

über eine Liste von Gegenstellen verbindet es sich automatisch mit allen Communities
