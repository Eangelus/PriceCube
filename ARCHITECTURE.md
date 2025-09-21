# Architektur-Dokumentation: PriceCube

## 1. Einleitung
PriceCube ist ein lokal ausgeführtes Preiskalkulationssystem für komplexe Produktstrukturen. Es wurde in nur sechs Monaten entwickelt und produktiv eingesetzt. Ziel ist maximale Effizienz, Datenschutz und Wartbarkeit – ohne Cloud-Abhängigkeit.

## 2. Kontextabgrenzung
- **Interne Stakeholder**: Vertrieb, Controlling, technische Leitung
- **Externe Systeme**: Optionale MES-Anbindung, ERP (SAP), keine Cloud
- **Entwicklungsumgebung**: Windows, C#, PowerShell, Docker, GitHub

## 3. Qualitätsziele
| Ziel              | Priorität | Umsetzung                             |
|------------------|-----------|----------------------------------------|
| Datenschutz      | Hoch      | Lokale Inferenz, keine Cloud, kein Ollama |
| Wartbarkeit      | Hoch      | Modularer Aufbau, Markdown-Doku       |
| Performance      | Mittel    | Schnelle Preisberechnung, optimierte Abläufe |
| Transparenz      | Hoch      | GitHub-Metriken, README mit Disclaimer |
| Portabilität     | Mittel    | Keine komplexen Pfade, direkt ausführbar |

## 4. Lösungsstrategie
- **Technologie-Stack**: C#, PowerShell, Python für KI-Module
- **Architekturprinzipien**: Trennung von Logik, UI und Datenzugriff
- **Dokumentation**: Markdown, mobil kopierbar, GitHub-kompatibel
- **Deployment**: lokal, containerfähig, keine Cloud-Services

## 5. Bausteinsicht
- **Core**: Preislogik mit regelbasierter Kalkulation
- **Import**: Datenaufnahme aus Excel, CSV, JSON
- **Export**: Ausgabe für ERP oder Reporting
- **UI**: optionales Frontend, CLI-first
- **KI-Modul**: lokale Inferenz, z. B. für Formelinterpretation

## 6. Laufzeitsicht
```plaintext
[User] → [UI/CLI] → [Preislogik] → [Exportmodul]
                      ↓
## 7. Schnittstellen
- **REST-API**: für externe Anbindung (ERP, MES)
- **Datei-API**: lokale Verarbeitung von Excel/CSV
- **GitHub**: für Metriken, Versionierung, Dokumentation

## 8. Architekturentscheidungen
- ❌ **Gegen Cloud**: Datenschutz, Kontrolle, Compliance
- ✅ **Für Markdown**: Lesbarkeit, mobile Kopierbarkeit
- ✅ **Für modulare Struktur**: Wartbarkeit, Erweiterbarkeit
- ❌ **Gegen komplexe Pfade**: direkte Ausführbarkeit im Hauptverzeichnis

## 9. Risiken
- Fehlende offizielle Anerkennung der Architekturrolle
- Interne Bewertungskriterien unklar
- MES-Anbindung könnte Anforderungen verändern

## 10. Glossar
- **MES**: Manufacturing Execution System – Bindeglied zwischen Shopfloor und ERP
- **OPC UA**: Protokoll für Maschinenkommunikation
- **REST**: Webschnittstelle für externe Systeme
- **PriceCube**: dein System zur Preiskalkulation
