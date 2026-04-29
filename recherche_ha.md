# Recherche Home Assistant

## Neueste Entwicklungen (Web-Recherche, Stand: 29.04.2026)

### 1) Core-Release 2026.4: Infrarot und Automatisierung im Fokus
- **Native Infrarot-Unterstuetzung** wurde als neue Plattform eingefuehrt. Damit koennen auch aeltere Geraete (z. B. TV, Klimageraete, Soundbars) ueber IR-Proxys in Home Assistant eingebunden werden.
- Mit **LG Infrared** gibt es bereits eine erste konkrete Integration auf der neuen IR-Basis.
- Die **purpose-specific Trigger/Conditions** wurden deutlich erweitert (inkl. domain-uebergreifender Trigger/Conditions, weiterhin als Labs-Feature).
- Neu ist zudem ein **Matter Lock Manager** zur Verwaltung von Nutzern und PIN-Codes direkt in Home Assistant.

### 2) Core-Release 2026.3: Praktische Alltagsfeatures
- Neue **"clean area"**-Aktion fuer Saugroboter (u. a. Matter, Ecovacs, Roborock), mit Mapping auf Home-Assistant-Bereiche.
- **Energy Dashboard** erhielt Verbesserungen (u. a. Echtzeit-Badges und Wasser-Sankey).
- Im Automation-Editor ist **"Continue on error"** nun auch in der UI verfuegbar (nicht mehr nur per YAML).
- Android Companion App unterstuetzt experimentell **lokale Wake-Word-Erkennung** (microWakeWord).

### 3) Core-Release 2026.2 und 2026.1: UX, Auffindbarkeit, Datenbasis
- Der **Home Dashboard**-Ansatz wurde als Standard fuer neue Installationen ausgebaut (inkl. Verbesserungen fuer Mobile, Areas und Device-Ansichten).
- **Add-ons wurden in "Apps" umbenannt**, um den Einstieg fuer neue Nutzer klarer zu machen.
- Die **Quick Search** wurde neu gestaltet und als zentrale Kommando-/Navigationssuche ausgebaut.
- Die Open Home Foundation treibt eine **community-basierte Device-Datenbank** voran (opt-in, anonymisiert).
- In 2026.1 kamen weitere Grundlagen fuer "human-friendly" Automationen sowie bessere Navigation zu Protokoll-Dashboards (z. B. Zigbee, Z-Wave) hinzu.

### 4) Nabu Casa / Cloud-Oekosystem (2026)
- Nabu Casa hebt fuer Home Assistant Cloud u. a. folgende Punkte hervor:
  - **5 GB Offsite-Backup-Speicher** (3-2-1-Backup-Strategie),
  - **Performantere Cloud-Knoten** fuer schnellere Remote-Verbindungen,
  - **Ausbau von Sprach-/Voice-Funktionen** (mehr Stimmen/Sprachvarianten),
  - fortlaufende **Hardware-Updates** im Voice- und Connect-Umfeld.

### Kurzfazit
Die juengsten Entwicklungen zeigen drei klare Richtungen:  
1. **Mehr Geraeteabdeckung** (z. B. durch IR und neue Integrationen),  
2. **Niedrigere Bedienhuerden** (natuerlichere Automationen, bessere Suche, klarere UI-Begriffe),  
3. **Staerkere Local-first + Privacy-Positionierung** bei gleichzeitiger Cloud-Ergaenzung (Backups, Voice, Remote-Zugriff).

### Quellen
1. Home Assistant 2026.4 Release Notes: https://www.home-assistant.io/blog/2026/04/01/release-20264/
2. Home Assistant 2026.3 Release Notes: https://www.home-assistant.io/blog/2026/03/04/release-20263/
3. Home Assistant 2026.2 Release Notes: https://www.home-assistant.io/blog/2026/02/04/release-20262/
4. Home Assistant 2026.1 Release Notes: https://www.home-assistant.io/blog/2026/01/07/release-20261
5. Nabu Casa Produktupdate 2026: https://www.nabucasa.com/news/2026-01-06-product-update/
