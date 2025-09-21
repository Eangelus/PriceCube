# 💼 PriceCube – Enterprise Preiskalkulationssystem

## 🧭 Projektüberblick

PriceCube ist ein lokal ausführbares Preiskalkulationssystem mit ERP-Integration, entwickelt in 6 Monaten.  
Die Architektur folgt Clean Architecture Prinzipien und wurde peer-reviewed.  
Der Projektname wurde im Zuge der Portfolio-Optimierung geändert.

📄 Hinweis zur Modellnutzung & Datenschutz: [DISCLAIMER.md](./DISCLAIMER.md)

---

## ⚙️ Technologie-Stack

- .NET 8.0 (C#), ASP.NET Core MVC  
- SQL Server, Dapper ORM  
- Serilog, Prometheus, Application Insights  
- GitLab CI/CD, Docker, PowerShell  
- JWT, OIDC (Keycloak), Windows Authentication  
- ClosedXML für Excel-Integration  
- xUnit, Moq für Testing

---

## 🧠 Architekturprinzipien

- Clean Architecture mit klarer Layer-Trennung  
- SOLID-Prinzipien durchgängig umgesetzt  
- Modularer Aufbau: Controller → Service → Repository → Entity  
- Security: Multi-Layer Auth, Secrets Management  
- Performance: Async-Optimierung, Caching, <500 ms Response Time

👉 Architekturdetails: [ARCHITECTURE.md](./ARCHITECTURE.md)

---

## 📈 Business Impact

| Kennzahl | Ergebnis |
|----------|----------|
| Kalkulationszeit | Reduziert von 2–3 Stunden auf 5–10 Minuten |
| Fehlerquote | Reduziert um >95 % |
| Kosteneinsparung | >50.000 € pro Jahr |
| Systemverfügbarkeit | 99.9 % Uptime, <500 ms Response Time, <500 MB RAM |
| Nutzerkapazität | 100+ gleichzeitige Nutzer |

---

## 📂 Repository-Inhalte

- `ARCHITECTURE.md`: Modulstruktur & Layer-Design  
- `DEVELOPER.md`: Entwicklerprofil & Marktwert-Matrix  
- `backend-review.pdf`: Zwischenstand nach 4 Monaten  
- `DISCLAIMER.md`: Hinweise zu Datenschutz & Modellnutzung

---
## 📂 Repository-Inhalte

- `ARCHITECTURE.md`: Modulstruktur & Layer-Design  
- `DEVELOPER.md`: Entwicklerprofil & Marktwert-Matrix  
- `backend-review.pdf`: Peer Review nach 4 Monaten  
- `DISCLAIMER.md`: Hinweise zu Datenschutz & Modellnutzung

---
## 🧩 Hinweis zur Modellnutzung

Während der Entwicklung wurden lokale KI-Modelle zur Analyse und Refactoring-Unterstützung verwendet.  
Externe Modelle wie GPT oder Claude wurden punktuell getestet, aber nicht produktiv eingebunden.

---

## 🗂️ Lizenz & Nutzung

Dieses Repository dient ausschließlich der technischen Dokumentation und Portfolio-Präsentation.  
Die produktive Lösung ist nicht öffentlich zugänglich.

---

> Letzte Aktualisierung: September 2025
