# V51 – EP und zwei unabhängige Teams

- Gesamt-EP, Level und EP-Zuwachs separat eingeben und bestätigen.
- Pokémon-EP-Kurve Mittel-langsam als Standard: 1.059.860 EP bei Level 100, 32.757 EP für 99 → 100.
- Optionale weitere Wachstumskurven über `growthRate`/`expGroup` im Pokémon-Katalog.
- Level wird aus EP berechnet, Levelwahl setzt EP auf den Minimalwert des Levels.
- Beim Levelaufstieg werden alle Level-Up-Attacken der übersprungenen Level angezeigt; das Ersetzen von Attacken bleibt eine bewusste Spielerentscheidung.
- KP und Kampfwerte werden beim Levelwechsel aktualisiert, der vorher fehlende KP-Betrag bleibt erhalten.
- Team 1 und Team 2 haben unabhängige Speicherung für Team, KP und Statusstufen; beide teilen den Pokédex.
- Browser-PWA-Manifest und Service Worker ergänzt.
