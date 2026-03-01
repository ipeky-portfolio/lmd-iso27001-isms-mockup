# Externe Audit-Simulation (Stage 2)
Landesamt für Musterdienste (LMD)
ISO/IEC 27001:2022

Auditdatum: 18.–21.02.2026  
Audittyp: Zertifizierung – Stage 2 (Wirksamkeitsprüfung)  
Auditor: Externer Lead Auditor  

---

# 1. Auditumfang

- Geltungsbereich gemäß ISMS_Scope.md
- Stichprobenprüfung:
  - Risikomanagement
  - Zugriffskontrolle
  - Incident Management
  - Backup & Restore
  - Lieferantenmanagement
  - Awareness & Schulungen
  - Management Review

---

# 2. Zusammenfassung

Das ISMS des LMD ist strukturell vollständig dokumentiert und grundsätzlich implementiert.

Es wurden jedoch mehrere signifikante Abweichungen festgestellt, die vor einer Zertifizierung behoben werden müssen.

Feststellungen:

- 1 Hauptabweichung (Major Nonconformity)
- 3 Nebenabweichungen (Minor Nonconformities)
- 5 Verbesserungspotenziale (Observations)

---

# 3. Hauptabweichung (Major Nonconformity)

## NC-M-01 – Unzureichende Wirksamkeitsprüfung der Risikobehandlung

Bezug: Kapitel 6.1.3 & 9.1 ISO 27001

Feststellung:

Für die im Risikobehandlungsplan definierten Maßnahmen (z. B. EDR-Einführung, DDoS-Schutz) existiert kein dokumentierter Nachweis zur systematischen Wirksamkeitsprüfung.

Beispiel:
- Kein dokumentierter Test des DDoS-Schutzes
- Kein Nachweis zur Wirksamkeitskontrolle der Phishing-Schulungen (keine KPI-Auswertung)

Risiko:

Es kann nicht nachgewiesen werden, dass implementierte Maßnahmen das Risiko tatsächlich reduzieren.

Einstufung: Hauptabweichung  
Zertifizierung aktuell nicht möglich.

# 4. Nebenabweichungen (Minor Nonconformities)

## NC-01 – Unvollständige Lieferantenbewertung

Bezug: Annex A 5.19 / 5.20

Für zwei IT-Dienstleister lag keine aktuelle Sicherheitsbewertung vor.
Die letzte dokumentierte Bewertung war älter als 24 Monate.

---

## NC-02 – Awareness-Nachweise lückenhaft

Bezug: Kapitel 7.2 Kompetenz

Stichprobe: 10 Mitarbeitende  
2 Mitarbeitende hatten keinen dokumentierten Schulungsnachweis für 2026.

---

## NC-03 – Restore-Test nicht vollständig dokumentiert

Bezug: Annex A 8.13 Backup

Ein monatlicher Restore-Test wurde laut Interview durchgeführt, jedoch nicht formell dokumentiert.

---

# 5. Beobachtungen (Opportunities for Improvement)

OFI-01:
KPIs sind definiert, jedoch fehlen Zielwerte für Incident-Response-Zeiten.

OFI-02:
Management Review sehr formal – strategische Ableitungen könnten stärker dokumentiert werden.

OFI-03:
Kein formalisierter Prozess für Lessons Learned nach Sicherheitsvorfällen.

OFI-04:
Penetrationstests erfolgen unregelmäßig.

OFI-05:
Dokumentenlenkung teilweise manuell – Automatisierung empfohlen.

# 6. Positiv hervorzuheben

- Sehr klar definierter Scope
- Strukturierte Risikomethodik
- Gutes Rollenmodell
- Technische Sicherheitsbasis solide
- Hohe Management-Beteiligung

---

# 7. Auditbewertung

Status: Nicht zertifizierungsfähig aufgrund Major Nonconformity.

Voraussetzung für Zertifizierung:

- Nachweis der Wirksamkeitsprüfung aller Hochrisiko-Maßnahmen
- Dokumentierte Korrekturmaßnahmen
- Re-Audit innerhalb 90 Tage
