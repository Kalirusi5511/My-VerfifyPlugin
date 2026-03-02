<img width="926" height="204" alt="Screenshot 2026-03-02 1115124" src="https://github.com/user-attachments/assets/5a4e4c8c-011b-415c-9cae-92aae3b8d83f" />
<img width="926" height="204" alt="Screenshot 2026-03-02 1115124" src="https://github.com/user-attachments/assets/5a4e4c8c-011b-415c-9cae-92aae3b8d83f" />
# My-VerfifyPlugin
My-VerifyPlugin ist noch nicht ganz Fertig.

Verify Plugin

Ein Minecraft-Bukkit-Plugin zur Erhöhung der Serversicherheit durch Verifizierung kritischer Befehle.
Features

    Zufällige Key-Generierung:
    Erstellt alle 2 Stunden einen neuen 8-stelligen Verifizierungsschlüssel.

    Verifizierungssystem:
    Spieler müssen den aktuellen Schlüssel mit /verify <Key> eingeben, um kritische Befehle nutzen zu können.

    Kritische Befehlsblockade:
    Blockiert Befehle wie /ban, /kick, /op, /stop u. a., bis der Spieler verifiziert ist.

    OP-Benachrichtigung:
    OP-Spieler erhalten bei jedem neuen Schlüssel eine Nachricht mit dem aktuellen Key.

    Permanente Speicherung:
    Verifizierte Spieler werden in einer Datei gespeichert und müssen sich nicht erneut verifizieren.

    Allowlist-Integration:
    Verifizierte Spieler werden automatisch zur Allowlist (allowlist.json) hinzugefügt.

Installation

    Laden Sie die .jar-Datei herunter.
    Fügen Sie sie in den plugins-Ordner Ihres Servers ein.
    Starten Sie den Server neu.

Konfiguration

Das Plugin erstellt automatisch die folgenden Dateien im plugins/VerifyPlugin-Ordner:

    key.yml: Speichert den aktuellen Verifizierungsschlüssel.
    verifiedPlayers.yml: Speichert die UUIDs verifizierter Spieler.
<img width="1055" height="287" alt="Screenshot 2026-03-02 110944" src="https://github.com/user-attachments/assets/fff0ec8f-5e10-42bf-967a-0640ab0b04e0" />
<img width="926" height="204" alt="Screenshot 2026-03-02 111124" src="https://github.com/user-attachments/assets/7f598d3f-4e99-4756-9851-142c266bb309" />
