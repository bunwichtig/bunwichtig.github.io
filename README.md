# bunwichtig.github.io

Startseite mit einer Übersicht meiner Projekte. Eine einzelne `index.html`, kein Build-Schritt.

## Projekt hinzufügen

In `index.html` im Block `PROJECTS` einen Eintrag ergänzen:

```js
{
  title: "Name",
  text: "Kurze Beschreibung",
  color: "#16a34a",          // Projektfarbe
  art: "leaf",               // Bild in Ansicht „Kalk“: walk | map | cam | leaf
  status: "In Arbeit",
  tags: ["Schlagwort"],
  live: "https://bunwichtig.github.io/repo-name/",
  repo: "https://github.com/bunwichtig/repo-name"
}
```

## Ansichten

Oben gibt es sechs Ansichten zum Umschalten. Die Wahl merkt sich der Browser.

- **Flach:** Feldbuch (Standard), Nacht, Kalk
- **Plastisch:** Moos, Ton, Tiefsee – erhabene Karten mit weichen Schatten

## Reihenfolge

Projekte mit `natur: true` stehen immer oben. Ein Projekt ohne `live`-Link erscheint blass
und ist nicht anklickbar (z. B. Star Trek, solange es noch nicht fertig ist).

## Veröffentlichen

Repo muss exakt `bunwichtig.github.io` heißen. Dann *Settings → Pages → Deploy from a branch → `main` / root*.
