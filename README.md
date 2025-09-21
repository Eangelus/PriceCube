# PriceCube – Enterprise Preiskalkulationssystem

📄 Hinweis: Das Projekt wurde ursprünglich unter anderem Namen entwickelt. Details siehe [DISCLAIMER.md](./DISCLAIMER.md).
## 🧭 Überblick

PriceCube ist ein lokal ausführbares Preiskalkulationssystem mit ERP-Integration, entwickelt in 6 Monaten.  
Die Architektur folgt Clean Architecture Prinzipien und wurde peer-reviewed.

👉 Architekturdetails: [ARCHITECTURE.md](./ARCHITECTURE.md)

## ⚙️ Stack & Architektur

- .NET 8.0, ASP.NET Core MVC  
- SQL Server, Dapper ORM  
- JWT, OIDC, Windows Auth  
- Serilog, Prometheus, Application Insights  
- GitLab CI/CD, ClosedXML, SignalR

## 🔐 Sicherheit & Performance

- TLS 1.2+, Secrets Management  
- <500 ms Response Time, <500 MB RAM  
- 99.9 % Uptime, 100+ gleichzeitige Nutzer

## 📈 Business Impact

- 80 % Zeitersparnis  
- >95 % Fehlerreduktion  
- >50.000 € ROI pro Jahr

## 📂 Inhalte

- `ARCHITECTURE.md`: Modulstruktur  
- `DEVELOPER.md`: Entwicklerprofil  
- `backend-review.pdf`: Zwischenstand  
- `DISCLAIMER.md`: Modellnutzung & Datenschutz

## 🧩 Modellnutzung

Zum Entwicklungszeitpunkt wurde ein lokal eingebundenes GPT-Modell verwendet.  
Externe Modelle wie Claude wurden später getestet, aber nicht produktiv eingebunden.

## 🗂️ Lizenz

Nur zur Dokumentation und Portfolio-Zwecken. Produktive Lösung ist nicht öffentlich.