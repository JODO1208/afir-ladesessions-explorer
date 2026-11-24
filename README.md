# Ladesession-Explorer

Interaktive Karte aller rund 214.000 öffentlichen Ladepunkte in Deutschland mit
Ladeplatz-Prognose, Versorgungslücken, Betreiber-Vergleich und Regel-Labor.

**Live:** https://jodo1208.github.io/afir-ladesessions-explorer/

> **Hinweis:** Die Standorte sind echt, die **Belegung ist simuliert**. Es handelt sich um einen
> Prototyp zur Rekonstruktion von Ladesessions aus AFIR-Echtzeitdaten; echte Statusdaten der
> Mobilithek sind noch nicht angebunden.

Diese Seite wird automatisch aus einem separaten Projekt erzeugt (`python -m afir_sessions explore`)
und enthält nur die fertige HTML-Datei.

## Quellen und Lizenzen

* Standorte: Ladesäulenregister der Bundesnetzagentur, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/),
  Namensnennung „Bundesnetzagentur.de“
* Kartenkacheln: © [OpenStreetMap](https://www.openstreetmap.org/copyright)-Mitwirkende
  (Nutzung gemäß [Tile Usage Policy](https://operations.osmfoundation.org/policies/tiles/))
* Übersichtskarte: [Natural Earth](https://www.naturalearthdata.com) (gemeinfrei)
