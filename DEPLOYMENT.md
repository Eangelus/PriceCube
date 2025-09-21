# 🚀 DEPLOYMENT.md – PriceCube

## 1. Zielsystem

- Lokale Ausführung auf Windows-Servern  
- Keine Cloud-Abhängigkeit  
- ERP-Anbindung über REST-API (Oxaion)

## 2. CI/CD Pipeline

- GitLab CI mit automatisierten Build-, Test- und Deploy-Stages  
- Docker-Containerisierung für lokale Testumgebung  
- PowerShell-Skripte zur Initialisierung und Konfiguration

## 3. Deployment-Schritte

1. Code Push → GitLab Trigger  
2. Build mit .NET 8 SDK  
3. Unit Tests via xUnit  
4. Docker Image Build  
5. Deployment auf Zielsystem  
6. Konfiguration via `appsettings.json` + Secrets

## 4. Monitoring & Logging

- Serilog für strukturierte Logs  
- Prometheus für Metriken  
- Application Insights für Telemetrie

## 5. Besonderheiten

- Excel-Upload via ClosedXML  
- Echtzeit-Feedback via SignalR  
- ERP-Sync mit resilientem Retry-Mechanismus

> Letzte Aktualisierung: September 2025
