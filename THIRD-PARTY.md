# Herkunft, lokale Änderungen und Lizenzen

Die Modrinth-Einträge verwenden weiterhin die exakt erfassten Autoren-Downloads. Die bisher nicht eingebundenen Archivstände aus der bestehenden lokalen Installation werden auf ausdrücklichen Wunsch des Pack-Inhabers unverändert als versionierte Release-Dateien bereitgestellt. Die Archive behalten ihre enthaltenen Originaltexte, Credits und Lizenzdateien. Lokale Änderungen werden nicht als offizielle Autorenversionen ausgegeben.

## Bestehende lokale Mod-Änderungen

Camera Utils enthält den Superzoom; My Totem Doll die vorhandenen Render-/GUI-Korrekturen; Punchy die vorhandene Kreativflug-Korrektur; das OpenGL-Voxy die bisherige Kompatibilitätsfassung. Die bereits veröffentlichten HUD-, DH- und Vitrail-Änderungsquellen stehen unter `patches/`. Die Kartenmod ist der vorhandene Forever-Everness-Client; die Vulkan-Fassung enthält dessen PBO-Kompatibilitätskorrektur.

## Drittanbieterbedingungen bleiben bestehen

Dieses Repository erteilt keine zusätzlichen Rechte an fremden Mods, Ressourcenpacks oder Shadern. Einige Komponenten führen weitergehende Beschränkungen in ihren eigenen Lizenzen auf. Die MIT-Lizenz im Stamm gilt ausschließlich für die neu erstellten Manifest-, Dokumentations- und Wartungsdateien, nicht für fremde Inhalte oder die unter GPL/LGPL stehenden Änderungen.

Beispiele: EvergreenHUD GPL-3.0; Distant Horizons und Vitrail LGPL-3.0; My Totem Doll CC BY-ND 4.0 laut beiliegender Lizenz; Punchy mit eigener Custom License; Camera Utils und Voxy mit den jeweiligen Rechtevorbehalten; SEUS mit seiner beiliegenden SEUS-Lizenz. Die Lizenzhinweise werden durch diese Zusammenstellung nicht ersetzt.

Upstream-Quellen der schon dokumentierten Änderungen: https://github.com/Polyfrost/EvergreenHUD, https://gitlab.com/distant-horizons-team/distant-horizons/ und https://github.com/avpbynf/Vitrail-Shaders.

## 2026.11.08.2: Weather Glass und Cozy Companion

Weather Glass 0.6.0 ist von DuffoPuffo, PolyForm Shield License 1.0.0. Die unveränderte JAR wird direkt vom offiziellen CurseForge-CDN geladen; [Projekt und Autor](https://www.curseforge.com/minecraft/mc-mods/weather-glass), [Lizenzkopie](licenses/Weather-Glass-PolyForm-Shield-1.0.0.txt).

Cozy Companion r3 basiert auf [Complementary Unbound r5.9.3 von Complementary Development](https://www.complementary.dev/), Complementary License Agreement 1.7. Es wird keine vollständige geänderte Shader-ZIP öffentlich rehostet. Das offizielle Original wird unverändert über Modrinth geladen. Die eigene MIT-Start-Hilfe und die beiden Settings-Rezepte liegen unter [patches/cozy-companion-setup](patches/cozy-companion-setup); sie rekonstruieren die lokale Nutzerfassung und erhalten alle Original-Lizenztexte. Die Helper-MIT-Lizenz erteilt keine zusätzlichen Rechte an Complementary.

## 2026.11.08.3: SIRIS / Pixelated-Migration

Pixelated wird ausschließlich lokal über den eigenen Patch-Helfer aus dem offiziellen Complementary Unbound r5.9.3 rekonstruiert, nicht als vollständige veränderte ZIP neu rehostet. Original und Patchmaterial stammen von [Complementary Development](https://www.complementary.dev/) und [Euphoria Patches](https://www.euphoriapatches.com/). Für diese Zusammenstellung ist Everness verantwortlich. Die unveränderten Lizenzdateien liegen unter `licenses/` und bleiben im lokalen Shader enthalten. [Quellen/Notice](patches/pixelated-setup).

OpenGL verwendet weiterhin die bisherige Purescale-Ausgabe; SIRIS wird nicht installiert.
