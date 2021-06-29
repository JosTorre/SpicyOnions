# Spicy Onions
Still in development...

A new more standarized version of Sweet Onions based on the work of LeonHeFirst and MaitreRenard, which aimes to be closer to Tor Project's specifications.

Portable Tor version (linux / dockers / python3)

By Jose Torre and David Leutgeb.


Spicy Onions besteht aus den folgenden Komponenten:
•	Directory
  o	Bietet die Information über jeder verfügbare Node im Netzwerk.
•	Server
  o	Bekommt und antwortet auf empfangene Nachrichten.
•	Client
  o	Wählt eine Route aus, baut den Circuit auf, sendet, empfängt, verschlüsselt und entschlüsselt Nachrichten.
•	Nodes
  o	Bauen den Circuit auf, senden, empfangen, verschlüsseln und entschlüsseln Nachrichten.
•	Zellen
  o	Sind die Objekte, die hin und her gesendet werden, um den Circuit aufzubauen und um die Kommunikation zwischen dem Client und dem Server zu ermöglichen.
•	Netzwerkanalyse
  o	Zeichnet den Netzwerkverkehr von Spicy Onions auf, um es später analysieren zu können.
  
Mit diesen Komponenten funktioniert Spicy Onions und ermöglicht damit eine Umgebung wie die von Tor für weitere Forschungsprojekte.

