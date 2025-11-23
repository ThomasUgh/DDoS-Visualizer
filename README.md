# 🛡️ DDoS Angriff Visualisierung

Eine interaktive HTML-Visualisierung, die zeigt wie DDoS-Angriffe funktionieren und wie moderne Schutzmaßnahmen diese abwehren.

![DDoS Visualization](https://img.shields.io/badge/Status-Active-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

<a href="https://ibb.co/9kdMKYYx"><img src="https://i.ibb.co/Kp814yyt/Bildschirmfoto-2025-11-21-um-12-58-53.png" alt="Bildschirmfoto-2025-11-21-um-12-58-53" border="0"></a>

## 📋 Übersicht

Diese interaktive Visualisierung zeigt anschaulich:
- Wie verschiedene DDoS-Angriffsarten funktionieren (Booter, C2, Botnet)
- Die Architektur von Botnet-Infrastrukturen mit C2-Servern
- Wie spezialisierte DDoS-Protection-Systeme arbeiten
- Die Effektivität verschiedener Schutzmaßnahmen in Echtzeit

## 🚀 Installation & Nutzung

### Einfache Verwendung
1. Repository klonen oder `ddos-visualisierung-full.html` herunterladen
2. Die HTML-Datei in einem modernen Browser öffnen
3. Keine weiteren Dependencies oder Installation nötig!

### Interaktion
1. **Angriffsart wählen**: Dropdown-Menü zum Auswählen der Traffic-Art
2. **Protokoll wählen**: Dropdown für TCP, UDP oder Mixed
3. **Schutz-Level einstellen**: Buttons zum Aktivieren verschiedener Schutzmaßnahmen
4. **Animation steuern**: Pause/Play und Reset-Buttons
5. **Beobachten**: Server-Health und Live-Stats mit Schwankungen in Echtzeit verfolgen

**Beispiel-Szenarien zum Testen:**
- **Botnet + UDP + Ohne Firewall**: Server geht sofort offline (200-250 Gbit/s!)
- **Botnet + TCP + Voller Schutz**: 98% geblockt, Server bleibt online (120-150 Gbit/s abgewehrt)
- **C2 + UDP + Mit Firewall**: 33% Schutz, Server unter Last (20-25 Gbit/s)
- **C2 + TCP + Mit Firewall**: Mehr Pakete, unterschiedliche Last (50k-70k PPS)
- **Booter + TCP vs UDP**: Unterschied in Paketrate und Bandbreite beobachten
  - TCP: 5-7 Gbit/s mit 4k-6k PPS (blaue Pakete)
  - UDP: 8-10 Gbit/s mit 3k-5k PPS (rote Pakete)
