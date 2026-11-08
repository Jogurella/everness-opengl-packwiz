## [2026.11.08.2] - 2026-11-08
### Neu
- **Weather Glass 0.6.0 für Fabric 26.3:** Regen auf Glas sowie Schnee und Frost. Einstellbar über Mods → Weather Glass → Konfigurieren; rein clientseitig.
- **Cozy Companion r3** mit den Profilen **Cozy - Normal** und **Cozy - Pixelated**. Die kleine Start-Hilfe erzeugt die lokale Variante automatisch aus dem bereits enthaltenen offiziellen Complementary Unbound r5.9.3; das Original bleibt erhalten. Die vom Nutzer gelieferte r3-ZIP und die erzeugte Fassung stimmen in allen 468 Einträgen überein.
- Eigenes Updatebild für Everness OpenGL und zugehöriger Newsartikel.
### Geändert
- Fabric Loader auf **0.20.1** angeglichen; dieser Stand wurde mit der neuen Start-Hilfe getestet.
- Weather Glass startet mit normalen Regen-/Schneemengen und **16x**-Details. Der zusätzliche Glas-Weichzeichner und die Beta-Staub-/Windfunktionen sind zunächst aus.
- Einstellungs-Vorlage, Prism-Starter, Downloadliste und Prüfsummen auf den neuen Stand gebracht. Vorhandene Hotkeys, HUD-Positionen, FOV, Vollbild, Sichtweite und aktive Shaderauswahl wurden in der Vorlage nicht verändert.
### Hinweise für Spieler
- Pack im Everness Launcher aktualisieren und Minecraft neu starten. **Cozy-Companion-r3** steht anschließend in der Shaderauswahl; das gewünschte Cozy-Profil wird in dessen Shader-Einstellungen gewählt. Vorhandene eigene Cozy-Dateien werden erhalten, niemals still ersetzt.
- Laufzeitprüfung: vollständiges OpenGL-Pack mit geladenem Cozy-Shader und Weather Glass, normale/gefärbte/getönte Glasblöcke und Scheiben in einer separaten Regen-/Schnee-Testwelt; 165 Sekunden und reguläres Beenden. Kein Multiplayer-Server wurde betreten und kein FPS-Gewinn gemessen.
- **Sichtprüfung noch offen:** Windows verweigerte die Fenstersteuerung. Der Laufzeitnachweis ist keine Freigabe gegen alle Glas-, Textur- oder Shaderfehler. Die Autorenseite nennt weiterhin mögliche Fehler bei Scheiben in Vierergruppen sowie noch ungetestetes Nvidium. Die vollständige Shader-/Dimensionswechsel-Matrix ist nicht geprüft; frühere unregelmäßige native Abbrüche bleiben als bekannte Grenze dokumentiert.

## [2026.11.08.1] - 2026-11-08
### Behoben
- HUD-Positionen und Skalierungen einschließlich Kompass, FPS, Rüstung, Spielerbild, Koordinaten, Jade und Minimap aus dem veröffentlichten Vulkan-Profil übernommen.
- Fehlende AutoSwitch-Erweiterung mit Alt+B, Item-Ausschlüssen und bisherigen Shulker-/AutoTotem-Einstellungen ergänzt.
### Geändert
- Gemeinsame Spiel- und Mod-Einstellungen, FOV, Vollbild, Tasten, aktive Punchy-Auswahl und Ressourcenpack-Reihenfolge entsprechen der Vulkan-Vorlage. Shader-Tasten sind auf die entsprechenden Iris-Funktionen abgebildet.
- Gemeinsamer offizieller Voxy-Build, Kartenclient und Tobias-Pixel-Profilsyntax angeglichen. OpenGL verwendet weiterhin Iris und seine Renderer-Erweiterungen; zusätzliche vorhandene OpenGL-Shader bleiben verfügbar.
### Hinweise für Spieler
- Für vorhandene Installationen die neue Einstellungs-Vorlage einmal mit Sicherung übernehmen: [SETTINGS.md](SETTINGS.md). Ein normales Pack-Update bewahrt persönliche Einstellungen.
- Alt+B: AutoSwitch; Ziffernblock *: Shader umschalten; Ziffernblock +: Shader neu laden; O: Shaderauswahl.

# 2026.11.07.2

- Fehlende Einstellungsdateien und versteckte Punchy-Profilwahl ergänzt.
- Aktuelle Tasten, HUD-, Mod-, Xaero-, Shader- und Totemwerte je Ausgangsprofil abgeglichen.
- Minecraft-Optionen im Starter vor dem ersten Start enthalten; Fenster-/RAM-/JVM-Werte übernommen.
- Prüfsummenmanifest und einmalige Wiederherstellung mit Sicherung für bestehende Installationen.
- Mod-, Ressourcenpack- und Shaderarchive unverändert; keine Grafikwerte zur Leistungssteigerung abgesenkt.
