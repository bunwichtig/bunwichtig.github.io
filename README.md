# bunwichtig.github.io

Startseite mit einer Übersicht meiner Projekte. Eine einzelne `index.html`, kein Build-Schritt.

## Projekt hinzufügen

In `index.html` im Block `PROJECTS` einen Eintrag ergänzen:

```js
{
  title: "Name",
  kat: "spiele",             // Kategorie: "spiele" oder "daten"
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

## Kategorien

Oben in der Mitte sitzt ein Umschalter **Alle · Spiele · Daten** mit der Zahl der Projekte. Jedes Projekt
bekommt mit `kat` eine Kategorie. Die Auswahl steckt in der Adresse, direkt verlinken geht also auch:
`bunwichtig.github.io/#spiele` oder `#daten`. Das klappt in jedem Design.

## Reihenfolge

Projekte mit `gross: true` stehen ganz vorne, danach die mit `natur: true`, sonst gilt die
Reihenfolge der Liste. Das Projekt mit `size: "big"` ist in jedem Design das Hauptprojekt
(zurzeit Funkenfeld). Ein Projekt ohne `live`-Link erscheint blass und ist nicht anklickbar.

## Designs 1–6

Oben rechts stehen die Knöpfe **1 2 3 4 5 6** (am Rechner gehen auch die Tasten 1–6).
Der Browser merkt sich die Wahl.

| Nr. | Design | Art |
|---|---|---|
| 1 | Bento (Standard) | hell und klar, Kachel-Raster, Hauptprojekt groß |
| 2 | Aurora | dunkel, Farbverlauf-Leuchten, Glas-Karten |
| 3 | Brutal | kräftige Farben, dicke Rahmen, harte Schatten |
| 4 | Swiss | große Schrift, nummerierte Liste, eine Akzentfarbe |
| 5 | Glas | Pastell-Verläufe, mattes Glas, Zahlen auf einen Blick |
| 6 | Bühne | dunkel, Hauptprojekt in seiner Farbe, Karten zum Wischen |

Direkt verlinken geht auch: `?design=4` oder `?design=2#spiele`.

## Veröffentlichen

Repo muss exakt `bunwichtig.github.io` heißen. Dann *Settings → Pages → Deploy from a branch → `main` / root*.
