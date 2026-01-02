# Initiales Home-Lab Setup


Zum Einstieg habe ich ein Raspberry Pi 5 Starter-Set angeschafft, um darauf erste Netzwerkdienste zu betreiben.
Bereits zu Beginn zeigte sich jedoch eine Einschränkung durch die vom Internetanbieter bereitgestellte ISP-Box, insbesondere im Zusammenspiel mit DNS- und Netzwerkeinstellungen.
Diese Problematik wurde im weiteren Verlauf genauer analysiert.


Als Betriebssystem wurde bewusst ein leichtgewichtiges, headless Linux-System (Raspberry Pi OS Lite) gewählt, um eine servernahe Umgebung ohne grafische Oberfläche zu nutzen.
Darauf wurde Pi-hole als DNS-Filter installiert, mit dem Ziel, DNS-Anfragen im Heimnetz zentral zu kontrollieren und besser nachvollziehen zu können.


Die grundlegende Installation von Pi-hole funktionierte wie erwartet.
Im laufenden Betrieb stellte sich jedoch heraus, dass der vorhandene Router das über Pi-hole gesetzte DNS teilweise umging.
Trotz manueller DNS-Konfiguration auf einzelnen Geräten nutzten einige Clients weiterhin den vom Router verteilten DNS-Server, was eine zentrale DNS-Kontrolle unmöglich machte.


Als Übergangslösung wurden die DNS-Einstellungen auf den einzelnen Geräten manuell angepasst.
Da dieses Vorgehen weder skalierbar noch zufriedenstellend war, wurde nach einer nachhaltigen Lösung gesucht.
Als nächster Schritt wurde die Entscheidung getroffen, einen eigenen Router einzusetzen, der die ISP-Box teilweise ersetzt und eine saubere, zentrale Netzwerk- und DNS-Konfiguration ermöglicht.

