JARVIS v3.0 – Standalone HTML (KEIN API-KEY NÖTIG)
==================================================

1. index.html herunterladen.
2. Datei mit Chrome oder Edge öffnen (Doppelklick genügt).
3. Boot-Sequenz abwarten -> Mikrofon-Freigabe erlauben.
4. FERTIG. Tippen, sprechen oder das Terminal benutzen.

Features v3.0
-------------
- ARC-REAKTOR-Boot-Screen: Ring-Fortschritt lädt sich wie im Film auf,
  10 Magnetspulen-Segmente leuchten nacheinander, Prozent-Readout,
  Ladephasen (Plasma-Injektion, Feldstabilisation, ...) + Spulen-Balken
- Zufällige Telemetrie-Logzeilen beim Boot: pro Start andere Messwerte
  (Gigawatt pro Spule, Plasma-Temp, Magnetfeld, Kuehlung, Schutzwert ...)
- Cinematischer MCU-Boot: 4 drehende Orbit-Ringe, J.A.R.V.I.S.-Logo
  materialisiert sich mit der Ladung, Akronym "JUST A RATHER VERY
  INTELLIGENT SYSTEM" schaltet sich Wort für Wort frei, seitliche
  Hex-Dump-Spalten, Weißblitz beim Online-Gang
- Gesprochene Begrüßung ("Systeme online ...")
- Animierter Reaktor-Kern mit Zustandsfarben
  (CYAN = online, GELB = denkt, GRÜN = spricht, ROT = Fehler)
- ECHTE Audio-Reaktivität: VU-Balken tanzen live zur JARVIS-Stimme
  und zum Mikrofon (WebAudio-Analyse)
- Synthetische JARVIS-Sound-Effekte (Boot, Beeps, Whooshes)
  - komplett per WebAudio synthetisiert, abschaltbar
- HOLO-GLOBUS: rotierendes 3D-Punktgitter im Dashboard
- TERMINAL-KONSOLE: echte Befehle wie status, scan, voices, memory,
  time, clear, restart - plus "ask <frage>" und "speak <text>"
- Typewriter-Effekt: JARVIS-Antworten bauen sich Zeichen für Zeichen auf
- Parallax-Tilt: das gesamte HUD neigt sich mit der Maus
- Glitch-Effekt auf das JARVIS-Logo (Taste F)
- Tastenkürzel: LEERTASTE = Mikrofon, ESC = Stopp, T = Terminal
- Partikel-Hintergrund, Scanlines, Sweep-Licht, Vignette, HUD-Ecken
- Mikrofon-Berechtigungsleiste dauerhaft im Kopf der Seite
- Männerstimme im MCU-Stil (tiefe Tonlage), Sprachauswahl in Settings
- ALLWISSEN-Modus: versteht jedes Thema, jede Sprache, Dialekt,
  Tippfehler; eigene Memory-Einträge fließen in jede Antwort ein
- KI-Engine: Pollinations.AI, kostenlos und ohne API-Key
- STREAMING: Antworten erscheinen Wort für Wort in Echtzeit
  (mit automatischem Fallback auf normale Antwort)
- DEEP MODE (Settings): maximale Denktiefe, sichtbarer
  Gedankenprozess im Chat, Follow-up-Insights, strukturierte
  Mehrschritt-Antworten für komplexe Fragen
- ECHTZEIT-KERN: Mathe (auch Prozent), Uhrzeit und Datum werden
  lokal in 0 Sekunden beantwortet - ohne Wartezeit
- Spracheingabe umschaltbar (DE/EN/TR/FR/ES/AR/IT)
- Chat mit Typing-Indicator, History, Memory, File-Analyse - alles lokal

Tastenkürzel
------------
LEERTASTE ... Mikrofon starten/stoppen
ESC ......... alles stoppen (Mikrofon + Stimme)
T ........... Terminal öffnen
F ........... Glitch-Effekt auslösen

Hinweise
--------
- Internet nötig (KI-Engine + Sprachausgabe sind Free-Services).
- Chat/Memory bleiben lokal im Browser (localStorage).
- Am besten in Chrome oder Edge erleben (Speech Recognition,
  Männerstimmen wie "Microsoft Conrad" / "Google UK English Male").
