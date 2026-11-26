# Sicherheit / Security

## Sicherheitslücke melden / Reporting a vulnerability
Bitte **nicht** öffentlich als Issue melden, sondern per E-Mail an **PENSORA@outlook.de** – mit Beschreibung, betroffener Version und, wenn möglich, Schritten zum Nachstellen.
Please do **not** open a public issue. Send an e-mail to **PENSORA@outlook.de** with a description, the affected version and, if possible, steps to reproduce.

PENSORA ist ein privates Freizeitprojekt. Eine Rückmeldung erfolgt nach bestem Bemühen, in der Regel innerhalb von 7 Tagen. / PENSORA is a private spare-time project; responses are best effort, usually within 7 days.

## Unterstützte Versionen / Supported versions
Nur die jeweils neueste Beta-Version erhält Korrekturen. / Only the latest beta release receives fixes.

## Sicherheitsmerkmale / Security features
- Signierte Updates (minisign); unsignierte oder veränderte Installer werden abgelehnt.
- Daten im gemeinsamen Ordner verschlüsselt (Argon2id, XChaCha20-Poly1305), Schlüssel lokal per Windows-DPAPI.
- Keine Telemetrie, kein Server, keine Cloud.
