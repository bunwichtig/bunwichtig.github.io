# bunwichtig.github.io

Startseite mit einer Übersicht meiner Projekte. Eine einzelne `index.html`, kein Build-Schritt.

## Projekt hinzufügen

In `index.html` im Block `PROJECTS` einen Eintrag ergänzen:

```js
{
  title: "Name",
  text: "Kurze Beschreibung",
  emoji: "🌱",
  color: "linear-gradient(135deg,#2f6b45,#7fb6a0)",
  status: "In Arbeit",
  tags: ["Schlagwort"],
  live: "https://bunwichtig.github.io/repo-name/",
  repo: "https://github.com/bunwichtig/repo-name"
}
```

Die Filter-Buttons entstehen automatisch aus den Tags.

## Veröffentlichen

Repo muss exakt `bunwichtig.github.io` heißen. Dann *Settings → Pages → Deploy from a branch → `main` / root*.
