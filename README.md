# bunwichtig.github.io

Startseite mit einer Übersicht meiner Projekte. Eine einzelne `index.html`, kein Build-Schritt.

## Projekt hinzufügen

In `index.html` im Block `PROJECTS` einen Eintrag ergänzen:

```js
{
  title: "Name",
  text: "Kurze Beschreibung",
  color: "#16a34a",          // Projektfarbe
  art: "leaf",               // Bildmotiv: walk | map | cam | leaf
  status: "In Arbeit",
  tags: ["Schlagwort"],
  live: "https://bunwichtig.github.io/repo-name/",
  repo: "https://github.com/bunwichtig/repo-name"
}
```

## Designs

Oben rechts gibt es drei Designs zum Umschalten: **Feldbuch** (Standard), **Neon** und **Bunt**.
Die Wahl merkt sich der Browser. Alle drei nutzen dieselbe Projektliste.

## Veröffentlichen

Repo muss exakt `bunwichtig.github.io` heißen. Dann *Settings → Pages → Deploy from a branch → `main` / root*.
