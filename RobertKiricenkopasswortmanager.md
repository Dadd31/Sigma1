---
marp: true
theme: gradient
class: blue
---

# Präsentation über Passwort-Manager

von Robert und Ward

---

# Inhaltsverzeichnis

- Was ist ein Passwort-Manager?
- Warum braucht man einen Passwort-Manager?
- Welche Passwort-Manager sind am sichersten?
- Wie benutzt man einen Passwort-Manager sicher?
- Wann braucht man einen Passwort-Manager?
- Welche Arten von Passwort-Managern gibt es?
- Welchen Nutzen bringt ein Passwort-Manager im Alltag?

---

# Was ist ein Passwort-Manager?

Eine Software, die deine Passwörter und Benutzernamen speichert, verwaltet und verschlüsselt an einem zentralen Ort aufbewahrt.

---

# Warum braucht man einen Passwort-Manager?

Viele Menschen neigen dazu, bei mehreren Konten dasselbe Passwort zu verwenden. Dadurch haben Kriminelle leichtes Spiel, auf alle Accounts zuzugreifen (Credential Stuffing).

---

# Welche Passwort-Manager sind am sichersten?

- **Zero-Knowledge-Architektur:** Nur du besitzt den Schlüssel (Master-Passwort) zur Entschlüsselung.
- **Starke Verschlüsselung:** Nutzung von Standards wie AES-256.
- **Open-Source-Software:** Der Quellcode ist öffentlich einsehbar und von Experten geprüft (z. B. Bitwarden, KeePassXC).
- **Zwei-Faktor-Authentifizierung (2FA):** Zusätzlicher Schutz vor unbefugtem Zugriff.

---

# Wie benutzt man einen Passwort-Manager sicher?

1. **Sichere Passwörter generieren:**
   - Erstellung völlig zufälliger Passwörter (meist 16–64 Zeichen).
   - *Beispiel:* `H:7ESKf)FyCrzuSE` oder `N!LM{AC!x4Qh#WF=tDJU<Q2§jQ+3?8cHDy`

2. **Master-Passwort & Hardware-Schlüssel:**
   - Ein extrem starkes Master-Passwort schützt die gesamte Datenbank.
   - Optional: Nutzung von Hardware-Tokens (z. B. YubiKey, OnlyKey), die zusätzlich per lokaler PIN freigeschaltet werden.

---

# Wann braucht man einen Passwort-Manager?

5 typische Anzeichen, dass du sofort einen Passwort-Manager brauchst:

1. Du benutzt bei vielen Konten das gleiche Passwort.
2. Du schreibst dir deine Passwörter auf Zettel oder in ungeschützte Notizen.
3. Du nutzt einfache, leicht erratbare Passwörter (z. B. „Sommer2026!").
4. Du vergisst ständig deine Zugangsdaten und musst sie zurücksetzen.
5. Du verwendest keine Zwei-Faktor-Authentifizierung (2FA).

---

# Welche Arten von Passwort-Managern gibt es?

1. **Cloud-basierte Passwort-Manager (online):**
   - Bitwarden (Open-Source)
   - 1Password
2. **Lokale Passwort-Manager (offline):**
   - KeePassXC
   - Enpass
3. **Browser-basierte Passwort-Manager:**
   - Google Passwortmanager
   - Apple iCloud-Schlüsselbund
4. **Self-Hosted Passwort-Manager:**
   - Bitwarden (Self-Hosted)
   - Vaultwarden

---

# Welchen Nutzen bringt ein Passwort-Manager im Alltag?

- **Zeitersparnis:** Automatisches Ausfüllen von Anmeldedaten und Formularen.
- **Geräteübergreifend:** Synchronisierung zwischen Smartphone, Tablet und PC.
- **Schutz vor Phishing:** Die Software erkennt gefälschte Websites und füllt Zugangsdaten nur auf echten Domains aus.
- **Entlastung:** Du musst dir nur noch ein einziges Master-Passwort merken.
