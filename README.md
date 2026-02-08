## 🧱 Aktive Services (Docker)

| Service        | Zweck | Image | Status |
|---------------|------|-------|--------|
| nginx-proxy   | Reverse Proxy & TLS Termination | jc21/nginx-proxy-manager | running |
| Pi-hole       | Netzwerkweites DNS-Filtering | pihole/pihole | paused |
| Unbound       | Rekursiver DNS Resolver | klutchell/unbound | running |
| Vaultwarden   | Self-hosted Password Manager | vaultwarden/server | healthy |
| Portainer     | Container Management UI | portainer/portainer-ce | running |


# Home-Lab – Netzwerk & Self-Hosting

Dieses Repository dokumentiert den Aufbau und die Weiterentwicklung
meines persönlichen Home-Labs.

Der Fokus liegt auf Netzwerkgrundlagen, DNS, IPv4/IPv6-Verhalten
(SLAAC, Router Advertisements) sowie dem Betrieb selbst gehosteter
Dienste auf Linux-Systemen.

Ziel des Projekts ist es, praxisnahes IT-Know-how durch eigenes
Experimentieren, systematisches Troubleshooting und Dokumentation
aufzubauen.

## Aktueller Fokus
- Zentrales DNS-Filtering mit Pi-hole
- Analyse von IPv4- und IPv6-Verhalten im Heimnetz
- Verständnis von DHCP, SLAAC und Router Advertisements

## Geplante nächste Schritte
- Router-basierte DNS-Verteilung für das gesamte Netzwerk
- VPN-Zugriff (WireGuard)
- Containerisierte Dienste mit Docker
