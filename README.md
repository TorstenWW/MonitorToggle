# MonitorToggle <sup>Beta</sup>

**Monitore an der Dockingstation per Klick an- und abschalten – ohne Kabelziehen.**
*Toggle docked monitors on and off with one click – no unplugging.*

![MonitorToggle](AppIcon-1024.png)

## Was die App kann / Features

- 🖥️ Einzelne Monitore deaktivieren und wieder aktivieren, während das Kabel
  eingesteckt bleibt — ideal, wenn ein Monitor zeitweise per HDMI an einem anderen
  Gerät hängt. / Disable and re-enable individual displays while they stay plugged in.
- 📋 **Profile pro Arbeitsplatz** (z. B. Büro und Zuhause, erkannt an den
  angeschlossenen Monitoren): merken sich Monitor-Zustände und Fensterpositionen
  deiner Apps und stellen beides beim Andocken automatisch her — nicht laufende
  Apps werden dabei gestartet. / Per-workplace profiles that restore monitor states
  and window layouts automatically when you dock, launching missing apps.
- ✏️ Monitore frei benennbar („Home links“ statt „XG349C“). / Custom monitor names.
- 🌍 Dreisprachig: Deutsch, English, Español (folgt der Systemsprache, umschaltbar).
- 🔄 Automatische Updates. / Automatic updates.

## Download

MonitorToggle ist während der Beta-Phase **kostenlos**. / Free of charge during
the beta phase.

**➡️ [Neueste Version herunterladen / Download latest version](../../releases/latest)**

Dort die `.dmg`-Datei laden — die App ist von Apple notarisiert und installiert
sich ohne Sicherheitswarnungen. / Download the `.dmg` — the app is notarized by
Apple and installs without security warnings.

## Systemvoraussetzungen / Requirements

- macOS 13 (Ventura) oder neuer / or later
- Mac mit Apple-Chip (M1 oder neuer) / Apple silicon Mac

## Installation

DMG öffnen, App in den Programme-Ordner ziehen, starten. Für die automatische
Fensteranordnung fragt macOS einmalig nach der Bedienungshilfen-Berechtigung. /
Open the DMG, drag the app to Applications, launch. macOS will ask once for
Accessibility permission (used to arrange windows).

## Kommandozeile / Command line

Für Skripte und Kurzbefehle lässt sich die App auch ohne Menü steuern. /
For scripts and Shortcuts the app can also be driven without the menu.

```
/Applications/MonitorToggle.app/Contents/MacOS/MonitorToggle list
/Applications/MonitorToggle.app/Contents/MacOS/MonitorToggle profiles
/Applications/MonitorToggle.app/Contents/MacOS/MonitorToggle apply Büro
/Applications/MonitorToggle.app/Contents/MacOS/MonitorToggle off 4
```

`apply` protokolliert jeden Schritt (welche App gestartet, welches Fenster
angeordnet wurde) – praktisch zur Fehlersuche. / `apply` logs every step, handy
for troubleshooting.

## Beta-Hinweis / Beta note

Die App ist voll funktionsfähig, wird aber aktiv weiterentwickelt. Feedback und
Fehlerberichte gern über die [Issues](../../issues). / Fully functional, under
active development — feedback and bug reports welcome via Issues.

## Technischer Hinweis / Technical note

Das Abschalten der Monitore nutzt dieselbe Systemtechnik wie vergleichbare
Display-Tools; nach einem Neustart oder erneutem Andocken kann ein deaktivierter
Monitor wieder aktiv sein und wird dann einfach erneut abgeschaltet (bzw. vom
Profil automatisch). / Display disabling uses the same system technique as
comparable display tools; after a reboot or re-dock a disabled monitor may come
back and can simply be disabled again (or automatically by a profile).
