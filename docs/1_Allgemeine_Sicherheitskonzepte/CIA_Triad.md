# Das CIA-Triad in der IT-Sicherheit

Dieses Dokument fasst die Kernkonzepte und wichtigsten Fakten zum CIA-Triad zusammen – einem fundamentalen Modell in der IT-Sicherheit, das die drei wichtigsten Schutzziele adressiert: **Vertraulichkeit**, **Integrität** und **Verfügbarkeit**.

---

## 1. Überblick über das CIA-Triad

Das CIA-Triad (auch als AIC-Triad bekannt) ist ein leicht einprägsames Modell zur Beschreibung der Grundpfeiler der Informationssicherheit:

- **C**: Confidentiality (Vertraulichkeit)
- **I**: Integrity (Integrität)
- **A**: Availability (Verfügbarkeit)

> Hinweis: Obwohl die Bezeichnung „CIA“ an die Central Intelligence Agency erinnert, steht sie in diesem Kontext ausschließlich für die drei genannten Sicherheitsziele.

Das Modell wird häufig als gleichseitiges Dreieck dargestellt, um die Gleichwertigkeit und Wechselbeziehung der drei Aspekte zu symbolisieren.

---

## 2. Vertraulichkeit (Confidentiality)

Vertraulichkeit bedeutet, dass nur autorisierte Personen Zugriff auf bestimmte Daten erhalten. Ziel ist der Schutz vor unbefugtem Zugriff.

**Beispiele und Methoden zur Gewährleistung:**

- **Verschlüsselung (Encryption):**  
  Daten werden in ein unlesbares Format umgewandelt und können nur von autorisierten Empfängern entschlüsselt werden.

- **Zugriffskontrollen (Access Controls):**  
  Definition, wer auf welche Daten zugreifen darf (z. B. per Rollenmodell).

- **Mehrfaktor-Authentifizierung (MFA):**  
  Kombination mehrerer Authentifizierungsmerkmale (z. B. Passwort + Token) zum Schutz von Konten.

---

## 3. Integrität (Integrity)

Integrität stellt sicher, dass Daten während der Übertragung oder Speicherung nicht unbemerkt verändert werden.

**Schlüsseltechniken zur Sicherstellung:**

- **Hashing:**  
  Erzeugt einen eindeutigen Fingerabdruck der Daten. Jede Änderung der Daten führt zu einem anderen Hash-Wert.

- **Digitale Signaturen:**  
  Kombinieren Hashing mit asymmetrischer Verschlüsselung, um sowohl Integrität als auch Authentizität zu gewährleisten.

- **Zertifikate:**  
  Stellen die Identität von Geräten oder Benutzern sicher, besonders im Kontext verschlüsselter Kommunikation.

- **Unbestreitbarkeit (Non-repudiation):**  
  Der Absender kann nicht abstreiten, die Daten gesendet zu haben – ein rechtlich und technisch wichtiger Aspekt.

---

## 4. Verfügbarkeit (Availability)

Verfügbarkeit garantiert, dass autorisierte Benutzer jederzeit Zugriff auf Systeme und Daten haben.

**Maßnahmen zur Sicherstellung der Verfügbarkeit:**

- **Systemdesign mit hoher Verfügbarkeit:**  
  Nutzung von Redundanzen, Lastverteilung und Hochverfügbarkeitsclustern.

- **Fehlertoleranz:**  
  Systeme können den Ausfall einzelner Komponenten kompensieren, z. B. durch RAID oder Failover-Systeme.

- **Patching und Wartung:**  
  Regelmäßige Updates beugen Ausfällen durch Sicherheitslücken oder Softwarefehler vor.

---

## Fazit

Das **CIA-Triad** bildet das konzeptionelle Rückgrat jeder Sicherheitsstrategie:

- **Vertraulichkeit** schützt Daten vor unbefugtem Zugriff.
- **Integrität** stellt sicher, dass Daten korrekt und unverändert bleiben.
- **Verfügbarkeit** sorgt dafür, dass Systeme und Informationen dann bereitstehen, wenn sie gebraucht werden.

Diese drei Prinzipien sind miteinander verknüpft und müssen in der Praxis **ausbalanciert** werden. Sicherheitslösungen sollten nie eines der Ziele bevorzugen, ohne die anderen zu berücksichtigen – ein stabiles Sicherheitskonzept berücksichtigt alle drei gleichgewichtig.

---

> Tipp für CompTIA Security+ Prüfung (SY0-701):  
Die Begriffe Confidentiality, Integrity und Availability gehören zu den grundlegenden Konzepten in **Domain 1.0: General Security Concepts** und sollten **sicher beherrscht** werden.
