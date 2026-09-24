# Moodle ViMiPad Plugin-Familie

Willkommen im zentralen Repository der **Moodle ViMiPad Plugin-Familie**. Dieses Repository dient als übergeordnete Dokumentations- und Einstiegsseite (Landingpage) für alle zugehörigen Komponenten sowie als zentraler Anlaufpunkt für Fehlerberichte (Issues) und Feature-Requests.

## Über die ViMiPad-Familie

Die ViMiPad-Erweiterungen bieten eine integrierte Lösung für Moodle, um kollaborative und interaktive Medien- und Notizfunktionen bereitzustellen. Die Familie besteht aus mehreren eigenständigen Plugins, die optimal aufeinander abgestimmt sind.

## Enthaltene Plugins

Die Plugin-Familie teilt sich in folgende eigenständige Repositories auf:

*   **[ViMiPad Aktivitätsmodul (mod_vimipad)](https://github.com/ralferlebach/moodle-mod_vimipad)** – Das Haupt-Aktivitätsmodul für Moodle-Kurse.
*   **[ViMiPad Fragetyp (qtype_vimipad)](https://github.com/ralferlebach/moodle-qtype_vimipad)** – Erweitert das Moodle-Testsystem um spezifische ViMiPad-Fragetypen.
*   **[ViMiPad Datenbank-Datenfeld (datafield_vimipad)](https://github.com/ralferlebach/moodle-datafield_vimipad)** – Erlaubt die Nutzung von ViMiPad-Feldern innerhalb der Moodle-Datenbank-Aktivität.
*   **[ViMiGallery Aktivitätsmodul (mod_vimigallery)](https://github.com/ralferlebach/moodle-mod_vimigallery)** – Ein ergänzendes Galerie-Modul zur Visualisierung und Strukturierung der Medieninhalte.

## Installation

Um den vollen Funktionsumfang zu nutzen, wird empfohlen, die Plugins in die entsprechenden Verzeichnisse deiner Moodle-Installation zu installieren:

1. `mod_vimipad` nach `/mod/vimipad`
2. `qtype_vimipad` nach `/question/type/vimipad`
3. `datafield_vimipad` nach `/mod/datafield/vimipad` (bzw. in den entsprechenden `user-datafield`-Ordner)
4. `mod_vimigallery` nach `/mod/vimigallery`

Führe anschließend das Moodle-Upgrade über die Administrationsoberfläche oder die Kommandozeile (`php admin/cli/upgrade.php`) aus.

## Fehlerberichte & Feature-Requests

Bitte nutze den zentralen Issue-Tracker dieses Dach-Repositories oder das verknüpfte GitHub-Projekt, um Fehler zu melden oder neue Funktionen vorzuschlagen. Dies erleichtert uns die pluginübergreifende Koordination und Entwicklung.

---
Projekt-Maintainer: [ralferlebach](https://github.com/ralferlebach)
