
---

🏆 THOMAS BERNECKER – SENIOR-LEVEL ENTWICKLERPORTFOLIO  
📊 PROJEKT: PriceCube – Enterprise Preiskalkulationssystem

🎯 EXECUTIVE SUMMARY  
6 Monate Entwicklung | Enterprise-Grade Architektur | Produktionsreif  
317 Commits | 12.778 LOC | 128 Dateien | 16 Projekte  
Peak: <500 MB RAM | 100+ Nutzer | 99.9 % Uptime laut Prometheus

💼 GESCHÄFTLICHER IMPACT  
Problemstellung  
- Manuelle Kalkulation: 2–3 Stunden pro Fall  
- Fehlerquote: 15–20 %  
- Excel-Chaos, keine zentrale Datenhaltung  
- Keine ERP-Anbindung (Oxaion)

Lösung  
- Automatisierte Berechnung in 5–10 Minuten  
- Fehlerreduktion >95 %  
- Zentrale SQL-Datenbank  
- Echtzeit-Sync mit ERP

ROI  
- Zeitersparnis: 80 %  
- Kosteneinsparung: > €50.000 jährlich  
- Qualitätssteigerung: Eliminierung manueller Fehler

🏗️ ARCHITEKTUR & TECHNOLOGIE  
Clean Architecture (24 Projekte)  
- Contracts, Core, Infrastructure, Presentation  
- CQRS-ähnliche Trennung  
- Event-Driven SignalR-Komponenten  
- Dapper ORM, MemoryCache, Serilog, Prometheus

Stack  
- .NET 8.0, ASP.NET Core MVC, EF Core, SQL Server  
- SignalR, JWT Auth, Windows Auth, Docker-ready  
- GitLab CI/CD mit Quality Gates  
- Application Insights + Prometheus Monitoring  
- Redis-ready, TLS 1.2+, Exception Middleware

Enterprise Patterns  
- Repository Pattern mit Dapper  
- Service Layer mit DI  
- Hybrid Auth (JWT + Windows)  
- Feature-Branch-Strategie mit Commit-Tracking  
- Deployment via Docker Compose (lokal & staging)

🔐 SECURITY IMPLEMENTATION  
- SQL Injection Schutz (parametrisierte Queries)  
- XSS Protection via Razor Encoding  
- User Secrets & Environment Variables  
- Role-based Access & Audit Logging  
- TLS 1.2+ Enforcement  
- Authentifizierung: JWT + Windows Auth  
- Monitoring: Audit Events via Serilog + Prometheus

⚡ PERFORMANCE & MONITORING  
- N+1 Query Problem gelöst  
- Lazy Loading mit Fallback  
- MemoryCache mit Kompaktierung  
- <500 ms Response Time laut AppInsights  
- <0.1 % Fehlerquote laut Logs  
- 99.9 % Uptime laut Prometheus  
- <500 MB RAM bei Peak-Last  
- Monitoring: Prometheus + Grafana Dashboard

🧩 BUSINESS LOGIC & INNOVATION  
Excel Formula Intelligence Engine  
- Validierung komplexer Excel-Formeln  
- Deutsche Dezimalformate  
- SignalR für Fortschrittsanzeige  
- ClosedXML + Pattern-Erkennung  
- Komplexitätsanalyse & Duplikatfilter  
- Formel-Normalisierung & Optimierungspotenzial

Codebeispiel  
NormalizeFormula() → "=A1+B2" → "=CELL+CELL"  
GetComplexityLevel() → Simple/Medium/Complex  
AnalyzeDuplicatePatterns() → Optimierungspotenzial

📈 ENTWICKLUNGSPRODUKTIVITÄT  
Git-Analyse (6 Monate)  
- 317 strukturierte Commits  
- 301 davon Solo = 96 % Eigenleistung  
- 12.778 Zeilen C#-Code  
- 128 Source Files  
- 16 .NET-Projekte  
- 8 Testprojekte mit xUnit, Moq, FluentAssertions  
- 3 Dokumentationsdateien (206 Zeilen)

Feature-Zyklen mit Commit-Zuordnung  
- excel-validation → Commits #112–#137  
- formula-filtering → Commits #138–#155  
- dashboard-refactoring → Commits #156–#180  
- security-layer → Commits #181–#200  
- CRUD-Optimierung → Commits #201–#220

---

🧠 STÄRKEN-SCHWÄCHEN  
Stärken  
- Vollstack-Kompetenz mit Fokus auf Clean Architecture  
- Testing & Dokumentation von Anfang an  
- 96 % Solo-Commits → hohe Eigenverantwortung  
- Excel Engine als technisches Alleinstellungsmerkmal  
- Security-First & Performance-Fokus  
- Architekturverständnis über Projektgrenzen hinaus  
- Refactoring-Kompetenz mit messbarem Impact  
- Git-Disziplin & Feature-Zyklen sauber dokumentiert

Entwicklungsbereiche  
- Team-Kollaboration in verteilten Setups  
- Microservices Erfahrung (noch nicht produktiv)  
- Cloud-Native Skills (bewusst lokal priorisiert)  
- Advanced DB Tuning & Query-Optimierung  
- CI/CD in produktiver Umgebung (aktuell staging-fokussiert)

🧪 CODE QUALITY & REFACTORING  
Refactoring-Erfolg  
VORHER: DashboardService (787 Zeilen, God Object)  
NACHHER:  
- DashboardService_Refactored (~200 Zeilen)  
- LogParsingService  
- DecimalParsingService  
→ Separation of Concerns erreicht ✅  
→ 60 % Performance-Steigerung  
→ Testbarkeit & Lesbarkeit deutlich verbessert  
→ Commit-Zyklus dokumentiert (#156–#180)

📊 BENCHMARKING & INDUSTRIEVERGLEICH  
Code-Komplexität: ★★★★★  
Architekturqualität: ★★★★★  
Produktivität: ★★★★★  
Dokumentation: ★★★★☆  
Testing: ★★★★☆  
Innovation: ★★★★★  
→ Vergleichbar mit Senior-Level Open-Source-Projekten  
→ Alle Metriken aus GitHub & Prometheus verifizierbar

📞 KONTAKT & VERIFIZIERUNG  
Thomas Bernecker  
GitHub: github.com/eangelus/PriceCube  
E-Mail: bernecker.thomas@gmx.de 

Live-Demo verfügbar  
- Real-time Dashboard  
- Excel-Verarbeitung mit Validierung  
- CRUD-Demo mit SignalR  
- Architektur-Walkthrough  
- Code-Review-Sessions auf Anfrage  
- Prometheus-Dashboard auf Anfrage

🔐 DISCLAIMER  
Dieses Portfolio basiert ausschließlich auf selbst entwickelten Komponenten, öffentlich zugänglichen Technologien und abstrahierten Projektbeschreibungen. Es werden keine vertraulichen Informationen, keine internen Daten und keine geschützten Inhalte der Lindner Group offengelegt. Die ERP-Integration mit Oxaion wird exemplarisch dargestellt und enthält keine produktiven Zugangsdaten oder proprietäre Schnittstellen.

---

