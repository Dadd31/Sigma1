---
marp: true
theme: gradient
class: blue
---

<style>
section {
    font-size: 32px;
}
section h1 {
    font-size: 1.6em;
}
</style>

# Präsentation über Passwort-Manager

von Robert

---

# Inhaltsverzeichnis

 Wir besprechen was ein Passwort-Manager ist,wie man einen benutzt und 
---

# Was ist ein Passwort-Manager?

Eine Software, die deine Passwörter und Benutzernamen speichert, verwaltet und verschlüsselt an einem zentralen Ort aufbewahrt.

- Alles liegt in einem verschlüsselten **Tresor (Vault)**
- Gespeichert werden Zugangsdaten, Notizen, Kreditkarten und teils 2FA-Codes
- Entsperrt wird der Tresor mit **einem** Master-Passwort
- Mit eingebautem Passwort-Generator und Auto-Ausfüllen

---

<style scoped>
section {
    font-size: 29px;
}
</style>

# Warum braucht man einen Passwort-Manager?

Viele Menschen verwenden bei mehreren Konten dasselbe Passwort. Dadurch haben Kriminelle leichtes Spiel, auf alle Accounts zuzugreifen (**Credential Stuffing**).

- **Credential Stuffing:** Angreifer probieren gestohlene Kombinationen aus E-Mail und Passwort automatisiert bei vielen anderen Diensten aus.
- **Ein Datenleck reicht:** Wird ein kleiner Online-Shop gehackt, sind plötzlich auch E-Mail, Online-Banking und Social Media in Gefahr.
- **Das Gedächtnis stößt an Grenzen:** Dutzende zufällige Passwörter kann sich niemand merken.
- **Lösung:** Für jedes Konto ein eigenes, zufälliges Passwort.

---

<style scoped>
section {
    font-size: 27px;
}
</style>

# Welche Passwort-Manager sind am sichersten?

- **Zero-Knowledge-Architektur:** Nur du besitzt den Schlüssel (Master-Passwort) zur Entschlüsselung. Die Verschlüsselung passiert auf deinem Gerät, nicht einmal der Anbieter kann deine Daten lesen.
- **Starke Verschlüsselung:** Nutzung von Standards wie AES-256. Das Master-Passwort wird mit Verfahren wie Argon2 oder PBKDF2 in einen Schlüssel umgerechnet, was Erraten extrem aufwendig macht.
- **Open-Source-Software:** Der Quellcode ist öffentlich einsehbar und von Experten geprüft (z. B. Bitwarden, KeePassXC).
- **Zwei-Faktor-Authentifizierung (2FA):** Zusätzlicher Schutz vor unbefugtem Zugriff, z. B. per Authenticator-App oder Hardware-Schlüssel.

---

<style scoped>
section {
    font-size: 28px;
}
</style>

# Wie benutzt man einen Passwort-Manager sicher?

### 1. Sichere Passwörter generieren

- Völlig zufällige Passwörter (meist 16–64 Zeichen) mit Groß- und Kleinbuchstaben, Zahlen und Sonderzeichen
- Für **jedes** Konto ein eigenes Passwort
- *Beispiele:* `H:7ESKf)FyCrzuSE` oder `N!LM{AC!x4Qh#WF=tDJU<Q2§jQ+3?8cHDy`
- Alternative: Passphrase aus 5–6 zufälligen Wörtern, leichter zu tippen

---

<style scoped>
section {
    font-size: 27px;
}
</style>

# Wie benutzt man einen Passwort-Manager sicher?

### 2. Master-Passwort & Hardware-Schlüssel

- Ein extrem starkes Master-Passwort schützt die gesamte Datenbank:
  - lang (mindestens 16 Zeichen), einzigartig und nirgends sonst verwendet
  - gut merkbar als Passphrase aus mehreren zufälligen Wörtern
  - niemals digital im Klartext speichern
- Optional: Hardware-Tokens (z. B. YubiKey, OnlyKey), die zusätzlich per lokaler PIN freigeschaltet werden
  - Schutz auch dann, wenn das Master-Passwort gestohlen wird
  - Am besten einen zweiten Schlüssel als Backup besitzen

---

<style scoped>
section {
    font-size: 27px;
}
</style>

# Wann braucht man einen Passwort-Manager?

5 typische Anzeichen, dass du sofort einen Passwort-Manager brauchst:

1. Du benutzt bei vielen Konten das **gleiche Passwort**.
2. Du schreibst dir deine Passwörter auf **Zettel oder in ungeschützte Notizen**.
3. Du nutzt einfache, leicht erratbare Passwörter (z. B. „Sommer2026!").
4. Du vergisst ständig deine Zugangsdaten und musst sie **zurücksetzen**.
5. Du verwendest **keine Zwei-Faktor-Authentifizierung (2FA)**.

---

<style scoped>
section {
    font-size: 27px;
}
</style>

# Welche Arten von Passwort-Managern gibt es? (1/2)

### 1. Cloud-basiert (online)
Bitwarden (Open-Source), 1Password

-   Synchronisierung über alle Geräte, einfache Bedienung
-   Daten liegen auf Servern des Anbieters (verschlüsselt)

### 2. Lokal (offline)
KeePassXC, Enpass

-  Datenbank bleibt auf deinem Gerät, volle Kontrolle
-  Synchronisierung und Backups musst du selbst organisieren

---

<style scoped>
section {
    font-size: 27px;
}
</style>

# Welche Arten von Passwort-Managern gibt es? (2/2)

### 3. Browser-basiert
Google Passwortmanager, Apple iCloud-Schlüsselbund

-  Bereits eingebaut und sofort nutzbar
-   An Browser bzw. Ökosystem gebunden, oft weniger Funktionen

### 4. Self-Hosted
Bitwarden (Self-Hosted), Vaultwarden

-   Eigener Server, Daten bleiben komplett bei dir
-   Einrichtung, Wartung und Updates liegen in deiner Verantwortung

---

<style scoped>
section {
    font-size: 28px;
}
</style>

# Welchen Nutzen bringt ein Passwort-Manager im Alltag?

- **Zeitersparnis:** Automatisches Ausfüllen von Anmeldedaten und Formularen, kein Zurücksetzen vergessener Passwörter mehr.
- **Geräteübergreifend:** Synchronisierung zwischen Smartphone, Tablet und PC.
- **Schutz vor Phishing:** Die Software erkennt gefälschte Websites und füllt Zugangsdaten nur auf echten Domains aus.
- **Entlastung:** Du musst dir nur noch ein einziges Master-Passwort merken.

---

<style scoped>
section {
    font-size: 28px;
}
</style>

# Fazit: So gelingt der Einstieg

1. Einen Passwort-Manager auswählen (z. B. Bitwarden oder KeePassXC)
2. Ein starkes Master-Passwort festlegen
3. 2FA für den Tresor aktivieren
4. Wichtige Konten zuerst umstellen: E-Mail, Online-Banking, Shopping
5. Schwache und doppelte Passwörter durch generierte ersetzen

---

# Zum Schluss : Meine Auswahl

1. Wenn ich Geld hab
 - Ich hätte ein Hardware Passwort-Manager wie YubiKey oder OnlyKey

 2. Wenn ich kein Geld hab.
 - Ich hätte Persönlich ein Open-Source kostenlosen Passwort-Manager wie Bitwarden benutzt.

