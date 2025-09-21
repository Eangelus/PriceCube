# 🔐 SECURITY_AUDIT.md – PriceCube

## 1. Authentifizierung

- JWT-basierte Authentifizierung für externe Nutzer  
- Windows Authentication für interne Nutzer  
- OIDC via Keycloak (optional)

## 2. Autorisierung

- Rollenbasierte Zugriffskontrolle  
- Claims-basierte Validierung  
- Zugriff auf sensible Endpunkte nur für berechtigte Rollen

## 3. Input Validation

- Serverseitige Validierung aller Formulareingaben  
- Schutz vor SQL Injection durch Dapper + Parameterisierung  
- Schutz vor XSS durch HTML-Encoding und Whitelisting

## 4. Transport-Sicherheit

- HTTPS Enforcement  
- TLS 1.2+  
- Keine unverschlüsselte Kommunikation

## 5. Secrets Management

- Zugriffstoken und API-Keys in `.env` oder GitLab Secrets  
- Keine sensiblen Daten im Repository

## 6. Audit & Logging

- Serilog mit strukturierter Log-Ausgabe  
- Audit Trails für sicherheitsrelevante Aktionen  
- Monitoring via Prometheus

> Letzte Aktualisierung: September 2025
