# 🧭 CPSA-E Modul-Mapping – PriceCube

Dieses Dokument zeigt, wie das Projekt *PriceCube* die Anforderungen der CPSA-E-Zertifizierung erfüllt.  
Es basiert auf dokumentierten Architekturentscheidungen, technischer Umsetzung und Peer Review.

---

## 1. Deployment

**Erfüllt durch**:  
- GitLab CI/CD Pipeline mit automatisiertem Build & Deployment  
- Docker-Containerisierung für lokale Ausführung  
- PowerShell-Skripte zur Konfiguration und Initialisierung

**Dokumentiert in**:  
- `README.md`  
- `ARCHITECTURE.md`  
- `DEPLOYMENT.md` (optional erstellbar)

---

## 2. Security

**Erfüllt durch**:  
- JWT-basierte Authentifizierung  
- Windows Authentication für interne Nutzer  
- Secrets Management & HTTPS Enforcement  
- Input Validation gegen Injection & XSS

**Dokumentiert in**:  
- `ARCHITECTURE.md`  
- `SECURITY_AUDIT.md` (optional erstellbar)

---

## 3. Design Decisions

**Erfüllt durch**:  
- Clean Architecture mit Layer-Trennung  
- SOLID-Prinzipien, Separation of Concerns  
- Entscheidung gegen Cloud-Abhängigkeit aus Datenschutzgründen  
- ClosedXML statt Excel Interop für Performance & Sicherheit

**Dokumentiert in**:  
- `ARCHITECTURE.md`  
- `DEVELOPER.md`  
- `backend-review.pdf`

---

## 4. Documentation

**Erfüllt durch**:  
- `README.md` mit Projektübersicht & Business Impact  
- `ARCHITECTURE.md` mit Modulstruktur & Layer-Design  
- `DEVELOPER.md` mit Marktwert-Matrix & Peer Review  
- `DISCLAIMER.md` mit Projektumbenennung & KI-Nutzung  
- `backend-review.pdf` als externer Review Case

---

## 5. Technology Mapping

**Erfüllt durch**:  
- .NET 8, ASP.NET Core MVC  
- Dapper ORM für performante Datenbankzugriffe  
- ClosedXML für Excel-Integration  
- SignalR für Echtzeit-Feedback  
- Serilog, Prometheus, Application Insights für Monitoring

**Dokumentiert in**:  
- `README.md`  
- `ARCHITECTURE.md`

---

## 6. Quality Assessment

**Erfüllt durch**:  
- Peer Review nach 4 Monaten durch Mentorin  
- Testabdeckung mit xUnit & Moq  
- Performance-Messung: <500 ms Response Time  
- Refactoring von Anti-Patterns (z. B. Async-Fehler)

**Dokumentiert in**:  
- `Backend_Review_Barthuber.pdf`  
- `DEVELOPER.md`  
- `README.md`

---

> Dieses Mapping zeigt, dass PriceCube alle relevanten CPSA-E Module erfüllt und als Review Case eingereicht werden kann.
> Letzte Aktualisierung: September 2025
