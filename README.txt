Projekt: GTA GISA (Browser-Spiel)

Ziel:
Ein schnelles Reaktionsspiel im GTA-Stil.

Gameplay:
- Figuren erscheinen mit Sprechblasen
- Spieler wählt das richtige Werkzeug:
  - Kommunikation (Cupcake)
  - Technik Fix
  - Patch
  - Aufräumen
- Meldungen werden schneller
- Figuren + Sprechblasen erscheinen zusammen

Besonderheiten:
- Figuren sind freigestellte PNGs
- Hintergrund ist statisch
- Sprechblasen müssen pixelgenau am Mund sitzen
- Reihenfolge der Figuren ist zufällig
- Keine Wiederholung bevor alle einmal dran waren

Multiplayer:
- Lobby erstellen mit Code
- Spieler können beitreten
- Supabase wird verwendet

Probleme aktuell:
- Lobby wird nicht erstellt / Code wird nicht angezeigt
- JavaScript läuft auf Mobile nicht zuverlässig
- Supabase funktioniert im Debug grundsätzlich
- Eventuell Probleme mit local file execution

Ziel für Codex:
1. Lobby stabil zum Laufen bringen
2. Fehler analysieren (Supabase / Browser / Permissions)
3. Multiplayer funktional machen
4. Spiel sauber strukturieren

Technik:
- HTML + CSS + JavaScript
- Supabase JS SDK

Wichtig:
- Muss im Browser funktionieren (auch mobil)
- Keine externen Build-Tools nötig
- Alles möglichst einfach halten