# 🔐 Security-Audit – PriceCube

## 1. OWASP Top 10 Mapping

| Risiko                         | Maßnahme im Projekt                          |
|-------------------------------|-----------------------------------------------|
| A01: Injection                | Dapper mit Parametrisierung                   |
| A02: Broken Authentication    | JWT via Keycloak, OIDC                        |
| A03: Sensitive Data Exposure  | TLS 1.2 enforced, Secrets via GitLab Vault    |
| A05: Security Misconfiguration| HTTPS, Logging, strukturierte Configs         |
| A06: Vulnerable Components    | NuGet Audit, manuelle Prüfung                 |
| A09: Logging & Monitoring     | Serilog, Prometheus, Audit-Log                |

## 2. Vorgaben
- Security-Strategie wurde vollständig durch die Firma vorgegeben.
- Authentifizierung, Token-Handling und TLS waren technisch vorbereitet.
- Fokus lag auf korrekter Integration und Schnittstellen-Mapping.

## 3. Umsetzung
- Keine Eigenentwicklung im Security-Bereich.
- OWASP-konforme Umsetzung durch Einhaltung interner Standards.
- Dokumentation erfolgt im Architektur-Review und README.

## 4. Review
- Selbstbewertung anhand OWASP-Kriterien.
- Peer-Review optional möglich.
