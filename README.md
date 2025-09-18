---

🏆 THOMAS BERNECKER – SENIOR-LEVEL ENTWICKLERPORTFOLIO  
📊 PROJEKT: PriceCube – Enterprise Preiskalkulationssystem

🎯 EXECUTIVE SUMMARY  
6 Monate Entwicklung | Enterprise-Grade Architektur | Produktionsreif  
317 strukturierte Commits | 12.778 LOC | 128 Dateien | 16 Projekte

---

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

---

🏗️ ARCHITEKTUR & TECHNOLOGIE  
Clean Architecture (24 Projekte)  
- Contracts, Core, Infrastructure, Presentation  
- CQRS-ähnliche Trennung  
- Event-Driven SignalR-Komponenten  
- Dapper ORM, MemoryCache, Serilog, Prometheus

Stack  
- .NET 8.0, ASP.NET Core MVC, EF Core, SQL Server  
- SignalR, JWT Auth, Windows Auth, Docker-ready  
- GitLab CI/CD, Application Insights

Enterprise Patterns  
- Repository Pattern mit Dapper  
- Service Layer mit DI  
- Exception Middleware  
- Redis-ready Caching  
- Hybrid Auth (JWT + Windows)

---

🔐 SECURITY IMPLEMENTATION  
- JWT + Windows Auth  
- User Secrets & Environment Variables  
- SQL Injection Schutz (parametrisierte Queries)  
- XSS Protection via Razor Encoding  
- Audit Logging & Role-based Access  
- TLS 1.2+ Enforcement

---

⚡ PERFORMANCE & OPTIMIERUNG  
- N+1 Query Problem gelöst  
- Lazy Loading mit Fallback  
- MemoryCache mit Kompaktierung  
- <500 ms Response Time  
- <0.1 % Fehlerquote  
- 99.9 % Uptime

---

🧩 BUSINESS LOGIC & INNOVATION  
Excel Formula Intelligence Engine  
- Validierung komplexer Excel-Formeln  
- Deutsche Dezimalformate  
- SignalR für Fortschrittsanzeige  
- ClosedXML + Pattern-Erkennung  
- Komplexitätsanalyse & Duplikatfilter

Codebeispiel  
NormalizeFormula() → "=A1+B2" → "=CELL+CELL"  
GetComplexityLevel() → Simple/Medium/Complex  
AnalyzeDuplicatePatterns() → Optimierungspotenzial

---

📈 ENTWICKLUNGSPRODUKTIVITÄT  
Git-Analyse (6 Monate)  
- 317 strukturierte Commits  
- 301 davon Solo = 96 % Eigenleistung  
- 18.089 Zeilen C#-Code  
- 128 Source Files  
- 16 .NET-Projekte  
- 8 Testprojekte mit xUnit, Moq, FluentAssertions  
- 3 Dokumentationsdateien (206 Zeilen)

Feature-Zyklen  
- characteristic-group-crud ✅  
- excel-validation ✅  
- formula-filtering ✅  
- security-layer ✅  
- dashboard-refactoring ✅

---

🧠 STÄRKEN-SCHWÄCHEN  
Stärken  
- Vollstack-Kompetenz  
- Clean Architecture umgesetzt  
- Testing & Doku von Anfang an  
- 96 % Solo-Commits  
- Excel Engine Innovation  
- Security-First & Performance-Fokus

Entwicklungsbereiche  
- Team-Kollaboration  
- Microservices Erfahrung  
- Cloud-Native Skills  
- Advanced DB Tuning

---

🧪 CODE QUALITY & REFACTORING  
Refactoring-Erfolg  
VORHER: DashboardService (787 Zeilen, God Object)  
NACHHER:  
- DashboardService_Refactored (~200 Zeilen)  
- LogParsingService  
- DecimalParsingService  
→ Separation of Concerns erreicht ✅  
→ 60 % Performance-Steigerung

---

📊 BENCHMARKING & INDUSTRIEVERGLEICH  
Code-Komplexität: ★★★★★  
Architekturqualität: ★★★★★  
Produktivität: ★★★★★  
Dokumentation: ★★★★☆  
Testing: ★★★★☆  
Innovation: ★★★★★

---

📞 KONTAKT & VERIFIZIERUNG  
Thomas Bernecker  
GitHub: github.com/eangelus/PriceCube  
LinkedIn: [Professional Profile]  
E-Mail: [Kontakt für Code-Reviews und Live-Demos]

Live-Demo verfügbar  
- Real-time Dashboard  
- Excel-Verarbeitung  
- CRUD-Demo  
- Architektur-Walkthrough  
- Code-Review-Sessions

---

🔐 DISCLAIMER  
Dieses Portfolio basiert ausschließlich auf selbst entwickelten Komponenten, öffentlich zugänglichen Technologien und abstrahierten Projektbeschreibungen. Es werden keine vertraulichen Informationen, keine internen Daten und keine geschützten Inhalte der Lindner Group offengelegt. Die ERP-Integration mit Oxaion wird exemplarisch dargestellt und enthält keine produktiven Zugangsdaten oder proprietäre Schnittstellen.

---

