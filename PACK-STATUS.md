# Prüfstand 2026.11.08.2: Weather Glass + Cozy Companion

Die sichtbare Nachkontrolle wurde nach dem Entsperren des PCs durchgeführt. **Regen unter Vulkan, Schneefall unter beiden Backends und Frost/Beschlag unter OpenGL sichtbar; beide Launcher-Updateartikel samt Bildern geprüft.** Die vollständig entwickelte Vulkan-Frostschicht ist noch nicht abschließend sichtbar abgenommen. Die zwei korrigierten 180-Sekunden-Schneeläufe endeten regulär. Ein weiterer Vulkan-Start wurde unerwartet beendet; eine Ursache ist nicht nachgewiesen. Der Bestand ist damit nicht allgemein als absturzfrei freigegeben.

[Vollständige Sichtprüfung, Testkorrektur, Einzelresultate und Grenzen](docs/WEATHER-GLASS-ABNAHME.md).

Die ursprünglichen 165-Sekunden-Läufe belegten noch keinen Schnee, weil der damalige Test-Biombereich vom Spiel abgelehnt worden war. Die neue Bewertung verwendet ausschließlich die korrigierten Läufe und die dazugehörigen Beobachtungen.

Datei-, Abhängigkeits-, Index-, Export-, Wiederherstellungs- und öffentliche Downloadprüfungen des Updates bleiben bestanden. Das lokale Cozy-Rezept stimmt in allen 468 Archiv-Einträgen mit der Nutzerdatei überein; bestehende eigene Shaderkopien und sonstige Mod-Einstellungen werden erhalten.

## Bisheriger Prüfstand

# Prüfstand 2026.11.08.1

67 Mods, 29 Ressourcenpacks und 19 Shaderarchive. Minecraft 26.3, Fabric 0.20.1, Java 25. Tests ausschließlich in einer separaten Singleplayer-Welt; keine produktiven Welten oder Server verändert.

## Gemeinsame Einstellungen

133 gemeinsam benannte Einstellungsdateien wurden gegen die veröffentlichte Vulkan-Vorlage abgeglichen. Unterschiede gibt es nur in `options.txt` (Backend und Shader-Tastennamen), `config/minecraft-keybinds.json` (Iris-Tastennamen) und `config/iris.properties` (Shaderaktivierung). Alle übrigen gemeinsam benannten Dateien sind bytegleich, einschließlich der sieben HUD-Felder, Jade und Xaero.

Die gemeinsame Mod-Basis ist identisch. OpenGL ergänzt Iris, Nvidium und OBE als rendererbezogene Komponenten; Vulkan ergänzt Vitrail und VIRIS. Voxy und der Kartenclient entsprechen demselben gepinnten Archiv. Vorhandene zusätzliche OpenGL-Shader bleiben verfügbar, die vier gemeinsamen Shader sind identisch gepinnt.

Die Wiederherstellung wurde mit vorhandenen abweichenden Werten und drei alten HUD-Dateien geprüft: Sicherung vor Änderung, Übernahme, Entfernung der alten HUD-Dateien aus dem aktiven Ordner und wiederholter Aufruf ohne erneuten Reset. Ein normales Launcher-Update bewahrt persönliche Werte; für vollständige Angleichung einmal [Einstellungen übernehmen](SETTINGS.md).

## Protokollierte Teilprüfungen

| Lauf | 60 Sekunden mit Hand | Größenfehler | Ergebniscode |
| --- | --- | --- | --- |
| unpatched80 | Nein | Ja | 15 |
| patched80 | Nein | Nein | 3221225477 |
| patched80-repeat | Ja | Nein | 0 |
| patched100 | Nein | Nein | 3221225477 |
| patched100-repeat | Ja | Nein | 0 |
| patched-photon80 | Ja | Nein | 0 |
| opengl-parity | Ja | Nein | 0 |

Eine Messung der FPS-Steigerung war nicht Gegenstand dieses Fehlers; es wird kein FPS-Gewinn behauptet.
