# PriceCube – Lokales Preiskalkulationssystem mit dokumentierter Architektur

## 🧭 Projektüberblick

PriceCube ist ein lokal ausführbares Preiskalkulationssystem, entwickelt mit Fokus auf Clean Architecture, Sicherheit und Wartbarkeit.  
Die Lösung wurde in 6 Monaten produktiv umgesetzt und dokumentiert – inklusive Peer Review und modularer Struktur.

👉 Architekturdetails: [ARCHITECTURE.md](./ARCHITECTURE.md)

## ⚙️ Technologie-Stack

- .NET 8.0 (C#)
- SQL Server + Dapper ORM
- Serilog + Prometheus Monitoring
- GitLab CI/CD Pipeline
- Excel-Integration mit ClosedXML
- JWT + Windows Authentication

## 🧠 Architekturprinzipien

- Clean Architecture mit klarer Layer-Trennung  
- SOLID-Prinzipien durchgängig umgesetzt  
- Modularer Aufbau: Services, Repositories, Controller  
- Keine Cloud-Abhängigkeit im produktiven System  
- Lokale KI-Tools wurden punktuell verwendet, aber nicht produktiv eingebunden

## 🔐 Sicherheit & Datenschutz

- Multi-Layer Authentication  
- Input Validation & Exception Handling  
- Keine sensiblen Daten im Repository  
- Lokale Ausführung ohne externe API-Abhängigkeiten

## 📈 Projektmetriken

- 317 Commits  
- >12.000 Zeilen C#  
- 16 Projekte (.NET)  
- 8 Test-Projekte mit xUnit/Moq  
- Peer Review durch ursprüngliche Entwicklerin bestätigt

## 📂 Repository-Inhalte

- `ARCHITECTURE.md`: Modulstruktur und Layer-Übersicht  
- `DEVELOPER.md`: Entwicklerprofil und Arbeitsanalyse  
- `backend-review.pdf`: Zwischenstand nach 4 Monaten  
- `DISCLAIMER.md`: Hinweise zu Datenvermeidung und Modellnutzung

## 🧩 Hinweis zur Modellnutzung

Zum Entwicklungszeitpunkt wurde ein lokal eingebundenes GPT-Modell verwendet.  
Externe Modelle wie Claude wurden später getestet, aber nicht produktiv eingebunden.

## 🗂️ Lizenz & Nutzung

Dieses Repository dient ausschließlich der technischen Dokumentation und Portfolio-Präsentation.  
Die produktive Lösung ist nicht öffentlich zugänglich.