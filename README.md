# NEXA

NEXA ist ein Windows-FPS auf Unreal Engine 5 mit eigenem Launcher und lokalen Free-for-All-Partien gegen neun Bots. Aktueller veröffentlichter Release: **0.3.5**.

[**Aktuelles NEXA-Setup herunterladen**](https://github.com/nexawepseite/NEXA/releases/latest/download/NEXA-Launcher-Setup.exe) · [Release und Prüfsummen](https://github.com/nexawepseite/NEXA/releases/tag/v0.3.5)

Für Discord den dauerhaften Setup-Link oben verwenden: Jeder neue Download erhält das neueste veröffentlichte Setup. Eine bereits gespeicherte ältere Setup-Datei bleibt ihr damaliges Paket. Der Launcher prüft signierte Updates; ein neuer Launcher wird nach Bestätigung installiert. Die Update-Anzeige bleibt mindestens fünf Sekunden lesbar und erscheint beim Start nur bei einem tatsächlich neueren Launcher. Vor PLAY wird das Spiel geprüft und bei Bedarf aktualisiert.

0.3.5 repariert die Verarbeitung des Launcher-Laufzeitarchivs und das Weiterlaufen des neuen Launchers nach dem Update-Helfer. Abgewiesene Updates stellen den vorherigen geprüften Stand wieder her. Der Start verwendet Launcher-Grau und explizite volle Fensterdeckkraft ohne zusätzliche Wartezeit oder Fade; bestehende Renderer-Animationen bleiben erhalten.

Neu sind ein Butterfly-Messer auf **Q / Xbox LB**, etwas schnelleres Laufen mit gezogenem Messer und Waffeninspektion auf **V / D-Pad unten**. Controller-Deadzones, präzise Zielkurve, Trigger und Menünavigation wurden verfeinert. Sniper-/Pump-Läufe, Zielausrichtung und Waffenaktionen beim Ego-Zuschauen sind überarbeitet. Slides während des Nachladens bleiben möglich.

Die Lobby bietet bewegliche Tabs, verfeinerte Menükanten und zwei kompakte NEWS-Überschriften passend zur Version. Der Battle Pass zeigt die verbleibende Saisonzeit in Tagen, Stunden und Minuten. Saison 1 dauert 80 Tage und endet am **16. Januar 2027 um 19:00 UTC**; Neustarts oder Updates setzen sie nicht zurück. Das bestehende 120-FPS-Lobbyziel garantiert keine erreichte Bildrate und ändert die Monitorfrequenz nicht.

Bei geöffnetem Seitenmenü läuft die Partie weiter; der lebende Charakter ist dabei geschützt. LEAVE MATCH führt direkt zur Lobby. Nach dem Tod beobachtest du den tatsächlichen Angreifer fünf Sekunden in der Egoansicht. Gesundheit regeneriert sich nach fünf schadensfreien Spielsekunden mit 25 HP pro Sekunde. Der Locker zeigt eigene freigeschaltete Skins, Waffenfinishes und Emotes.

Die Top-10-Seite im Launcher liest authentifizierte, vertrauenswürdige Serverergebnisse für Kills und Siege. Es ist derzeit kein öffentlicher autoritativer Gameplay-Server bereitgestellt: Lokale Bot-Partien füllen deshalb keine globalen Ränge; leere Ranglisten zeigen keine erfundenen Spieler. Die bestehende Discord-Konto-/Inventar-API ist davon getrennt. Discord Rich Presence und der zusätzliche große Animations-/Audioauftrag stehen noch aus.

Partien vergeben keine automatischen Coins. Coin-Pakete öffnen den konfigurierten [Discord-Support](https://discord.gg/DqKpphhSTH); dabei findet weder eine Zahlung noch eine Gutschrift statt. Echte Zahlungen sind nicht eingerichtet. Die Ping-Vorschau ist als DEMO markiert; NA ist als SOON gekennzeichnet. AVEX prüft lokale Sitzung und signierte Paketintegrität. Öffentliche authentifizierte Multiplayer-Server und unabhängige Online-Anti-Cheat-Attestation sind nicht bereitgestellt.

Die Downloads enthalten Laufzeitpakete und keine separaten Unreal-Entwicklungsprojekte, Buildskripte, Tests oder privaten Schlüssel. Die vom Electron-Launcher benötigten Laufzeitdateien in `app.asar` sind technisch extrahierbar. Vollständige AAA-Produktion, pixelgleiche Referenztreue und garantierte Bildraten werden nicht behauptet.