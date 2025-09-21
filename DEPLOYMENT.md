# 🚀 Deployment-Dokumentation – PriceCube

## 1. CI/CD-Plattform
- GitLab CI/CD ist vollständig eingerichtet.
- Runner: Shared Runner + interner Testserver.
- Secrets: verwaltet über `.env` und GitLab Vault.

## 2. Branch-Strategie
- `main`: stabil, releasefähig.
- `dev`: Integration, Feature-Merges.
- `feature/*`: neue Funktionen.
- Merge via Merge-Request mit Reviewpflicht.

## 3. Pipeline-Phasen
- `build`: Restore, Compile mit .NET 8.
- `test`: xUnit-Tests, Coverage-Analyse.
- `lint`: StyleCop, Roslyn-Analyser.
- `deploy`: automatisiertes Deployment auf Testserver via SSH.

## 4. Monitoring & Logging
- Serilog: File-Logging + Seq-Integration.
- Prometheus: Metriken für Performance und Health.
- Alerts via Grafana (optional konfigurierbar).

## 5. Rollback-Strategie
- GitLab Tags + Docker Image Versionierung.
- Manuelles Rollback über GitLab UI oder Shell-Skript.

## 6. Besonderheiten
- ERP-Testdaten via Mock-Service.
- Excel-Upload wird vor Deployment validiert.
- SignalR-Dashboard wird nach erfolgreichem Build aktualisiert.

## 7. Review
- CI/CD wurde im Backend-Review dokumentiert.
- Selbstbewertung anhand Stabilität, Wartbarkeit und Deployment-Zeit.
