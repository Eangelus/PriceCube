# 🏆 CPSA-E Dossier – PriceCube

## 1. Projektkontext

**Projektname**: PriceCube (ursprünglich unter anderem Namen entwickelt)  
**Typ**: Enterprise-Preiskalkulationssystem  
**Zielgruppe**: Vertriebsmitarbeiter, Kalkulatoren, ERP-Nutzer  
**Umgebung**: Lokale Ausführung, ERP-Integration (Oxaion), keine Cloud-Abhängigkeit  
**Entwicklungszeitraum**: 6 Monate  
**Rolle**: Lead Developer & faktischer Softwarearchitekt

---

## 2. Architekturverantwortung

- Clean Architecture mit klarer Layer-Trennung  
- SOLID-Prinzipien durchgängig umgesetzt  
- Security: JWT, Windows Auth, Secrets Management  
- CI/CD: GitLab, Docker, automatisiertes Deployment  
- Monitoring: Serilog, Prometheus, Application Insights  
- Testing: xUnit, Moq, hohe Testabdeckung  
- Dokumentation: `README.md`, `ARCHITECTURE.md`, `DEVELOPER.md`, `backend-review.pdf`

👉 Details siehe [ARCHITECTURE.md](./ARCHITECTURE.md)

---

## 3. Review Case

**Problemstellung**:  
Wie kann ein komplexes Preismodell mit Excel-Formeln, ERP-Daten und Benutzerinteraktion performant und wartbar umgesetzt werden?

**Lösungsansatz**:  
- ClosedXML für Excel-Handling  
- Dapper ORM für performante Datenbankzugriffe  
- SignalR für Echtzeit-Feedback  
- Modularer Aufbau mit klarer Verantwortlichkeit  
- Security durch Multi-Layer Auth und HTTPS Enforcement

**Validierung**:  
Peer Review durch Mentorin nach 4 Monaten, dokumentiert in [Backend_Review_Barthuber.pdf](./Backend_Review_Barthuber.pdf)

**Reflexion**:  
- Async-Anti-Pattern wurde später erkannt und refactored  
- Microservices-Migration als Zukunftsperspektive  
- Architekturentscheidungen wurden dokumentiert und begründet

---

## 4. Mapping auf CPSA-E Module

| Modul | Erfüllt durch |
|-------|---------------|
| **Deployment** | Docker, GitLab CI/CD, PowerShell |
| **Security** | JWT, Windows Auth, Secrets Management |
| **Design Decisions** | Layer-Trennung, SOLID, Architektur-Doku |
| **Documentation** | `README.md`, `ARCHITECTURE.md`, `DEVELOPER.md` |
| **Technology Mapping** | .NET 8, Dapper, ClosedXML, SignalR |
| **Quality Assessment** | Peer Review, Performance-Messung, Testabdeckung |

---

## 5. Fazit

PriceCube erfüllt die Anforderungen eines CPSA-E Review Cases in vollem Umfang.  
Die Architektur ist dokumentiert, validiert und produktiv umgesetzt.  
Die Rolle als Softwarearchitekt ist durch Peer Review und technische Tiefe belegt.

> Dieses Dossier dient zur Einreichung bei iSAQB zur CPSA-E Zertifizierung.  
> Letzte Aktualisierung: September 2025
