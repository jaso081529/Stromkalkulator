# HP67 Strom & Trim Ultra – v4.3 Full Fix

**Fixes**
- Tabs oben sind jetzt per **Hash-Routing** (#calc, #geräte, …) verdrahtet – klick/tap funktioniert immer.
- Header hat hohen z-index & pointer-events aktiv → nichts blockiert die Leiste.
- Alle Eingabefelder in Tabellen sind echte Inputs/Selects (volle Breite, touch-optimiert).
- Alle alten Bereiche wieder drin: Geräte, Materialien, Verbindungen, Anbieter, Vorlagen, Historie, Einstellungen.

**Inhalt**
- `index.html` – komplette App.
- `hp67_devices.json` – Startgeräte (für Import).
- `hp67_connections.json` – Nebenlasten-Profile (für Import).
- `hp67_materials.json` – Beispiele Material (für Import).

**Deployment**
1. `index.html` ins Webroot (z. B. GitHub Pages).
2. Seite mit Safari öffnen → **Zum Home-Bildschirm** (Icon wie App).
3. Optional: JSONs importieren (Tabs → Import).

Viel Spaß! 🔥
