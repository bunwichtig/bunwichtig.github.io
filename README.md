# bunwichtig.github.io

Startseite mit einer Übersicht meiner Projekte. Eine einzelne `index.html`, kein Build-Schritt.

## Projekt hinzufügen

In `index.html` im Block `PROJECTS` einen Eintrag ergänzen:

```js
{
  title: "Name",
  em: "me",                  // optional: kursiver Teil des Namens
  text: "Kurze Beschreibung",
  color: "#16a34a",          // Projektfarbe
  art: "leaf",               // Bild: walk | map | cam | signal | leaf | game
  status: "In Arbeit",
  tags: ["Schlagwort"],
  size: "wide",              // optional: "big" = Hauptprojekt, "wide" = im Bento doppelt breit
  live: "https://bunwichtig.github.io/repo-name/",
  repo: "https://github.com/bunwichtig/repo-name"
}
```

## Reihenfolge

Projekte mit `gross: true` stehen ganz vorne, danach die mit `natur: true`, sonst gilt die
Reihenfolge der Liste. Das Projekt mit `size: "big"` ist in jeder Optik das Hauptprojekt
(zurzeit BombRe). Ein Projekt ohne `live`-Link erscheint blass und ist nicht anklickbar.

## Optiken und Farben

Unten rechts sitzt ein kleiner runder Knopf. Darüber lässt sich die Optik wählen, der Browser merkt sich die Wahl.

| Optik | Art |
|---|---|
| Bento (Standard) | Kachel-Raster, Hauptprojekt groß |
| Bühne | großer Auftritt fürs Hauptprojekt, darunter eine Reihe Karten |
| Feldbuch | nummerierte Liste wie die frühere Startseite |
| Neon-Arcade | dunkel, Neonleuchten, Pixelschrift (eigene Farben) |
| Magazin | Titelblatt mit Titelgeschichte (eigene Schrift) |
| Terminal | Projekte als Kommandozeile (eigene Farben) |
| Pinnwand | Zettel auf Kork (eigene Farben) |

Bento, Bühne, Feldbuch und Magazin lassen sich zusätzlich mit sechs Farben kombinieren:
Feldbuch, Nacht, Kalk (flach) sowie Moos, Ton, Tiefsee (plastisch, mit weichen Schatten).

Direkt verlinken geht auch: `?optik=neon` oder `?optik=bento&farbe=tiefsee`.

## Veröffentlichen

Repo muss exakt `bunwichtig.github.io` heißen. Dann *Settings → Pages → Deploy from a branch → `main` / root*.
