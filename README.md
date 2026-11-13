# hansmaulwurf23.github.io

Startseite unter <https://hansmaulwurf23.github.io/> für die Lern-Apps
[Lesen](https://github.com/hansmaulwurf23/blitzlesen),
[Zahlen](https://github.com/hansmaulwurf23/kopfrechnen) und
[Dingsbums](https://github.com/hansmaulwurf23/dingsbums). Eine zweite Seite `alltag.html` stellt die
Apps für Erwachsene vor, [Pacor](https://github.com/hansmaulwurf23/pacor),
[Focus](https://github.com/hansmaulwurf23/focus) und [Dill](https://github.com/hansmaulwurf23/dill);
die Kinderseite verlinkt sie unten im Fußbereich.

Statische Seiten (`index.html`, `alltag.html`), veröffentlicht direkt aus `main` über GitHub Pages. Die
Projektseiten der anderen Repos (`/blitzlesen/`, `/qwixx/`, …) bleiben davon unberührt.

Absichtlich ohne JavaScript, Service Worker und localStorage: Die Seite teilt sich die Domain mit den
Web-Apps und soll deren Speicher nie berühren.

Die Vorschaubilder sind verkleinerte `docs/screenshots/01-start.png` der Repos, bei Dingsbums
`06-spielfeld.png` (das leere Startfeld sagt wenig):

```sh
convert ../lesen/docs/screenshots/01-start.png -resize 400x -strip -quality 80 bilder/lesen.jpg
convert ../dingsbums/docs/screenshots/06-spielfeld.png -resize 400x -strip -quality 80 bilder/dingsbums.jpg
convert ../pacor/docs/screenshots/02-halbmarathon.png -resize 400x -strip -quality 80 bilder/pacor.jpg
convert ../focus/docs/screenshots/02-laeuft.png -resize 400x -strip -quality 80 bilder/focus.jpg
convert ../dill/docs/screenshots/01-liste.png -resize 400x -strip -quality 80 bilder/dill.jpg
```

Die Icons in `icons/` sind die Launcher-Icons der Apps (Vektor-Drawables), von Hand nach SVG übertragen.
