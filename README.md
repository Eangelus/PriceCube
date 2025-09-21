# PriceCube – Produktives Preiskalkulationssystem

## 🧭 Projektüberblick

PriceCube ist ein lokal ausführbares Preiskalkulationssystem, das in nur sechs Monaten aus einem Prototyp zu einem produktiven Backend weiterentwickelt wurde. Die Lösung wurde strukturiert, dokumentiert und ist wartbar aufgebaut – mit Fokus auf Datenschutz, Effizienz und technischer Klarheit.

> 📄 Die ursprüngliche Entwicklerin bestätigte in einer internen Beurteilung die Qualität und Produktivität der Lösung.

## ⚙️ Technologie-Stack

- .NET (C#)
- Docker (lokale Ausführung)
- PowerShell & Python (für KI-nahe Tools und Videoverarbeitung)
- Markdown-basierte Dokumentation
- GitHub als öffentliches Portfolio (ohne produktiven Code)

## 🧠 Architekturprinzipien

- Modularer Aufbau mit klaren Service-Grenzen  
- Trennung von UI, Business Logic und Datenhaltung  
- Keine Cloud-Abhängigkeit im produktiven System  
- KI-Modelle wurden lokal getestet, externe Modelle wie Claude kamen erst später zum Einsatz und wurden nicht produktiv eingebunden

👉 Details zur Architektur: [ARCHITECTURE.md](./ARCHITECTURE.md)

## 🔐 Datenschutz & Sicherheit

- Keine sensiblen Daten im öffentlichen Repository  
- Produktive Lösung läuft lokal, ohne externe API-Abhängigkeiten  
- Dokumentation enthält keine internen Geschäftslogiken oder vertrauliche Inhalte

## 📈 Business Impact

- Produktives System in 6 Monaten  
- Peer Review durch die ursprüngliche Entwicklerin  
- Strukturierte Dokumentation für Wartung und Skalierung  
- GitHub-Metriken: >12.000 Zeilen C#, 317 Commits, 16 Projekte

## 📂 Repository-Inhalte

- `ARCHITECTURE.md`: Technische Struktur und Modulübersicht  
- `DISCLAIMER.md`: Hinweise zur Datenvermeidung und Compliance  
- `backend-review.pdf`: Zwischenstand nach 4 Monaten  
- Keine produktiven Daten oder Geschäftslogik enthalten

## 🧩 Hinweis zur Modellnutzung

Zum Zeitpunkt der Entwicklung war Claude nicht verfügbar. Ein lokal eingebundenes GPT-Modell wurde verwendet. Externe Modelle wurden später punktuell getestet, aber nicht produktiv eingebunden.

## 🗂️ Lizenz & Nutzung

Dieses Repository dient ausschließlich der technischen Dokumentation und Portfolio-Präsentation.  
Die produktive Lösung ist nicht öffentlich zugänglich.
