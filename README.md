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

Oben rechts gibt es drei Ansichten zum Umschalten: **Papier** (Standard), **Nacht** und **Kalk**.
Sie unterscheiden sich nur in Farben und Schrift; die Wahl merkt sich der Browser.

## Veröffentlichen

Repo muss exakt `bunwichtig.github.io` heißen. Dann *Settings → Pages → Deploy from a branch → `main` / root*.
