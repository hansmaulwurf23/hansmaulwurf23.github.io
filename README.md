# hansmaulwurf23.github.io

Startseite unter <https://hansmaulwurf23.github.io/> für die Lern-Apps
[Lesen](https://github.com/hansmaulwurf23/blitzlesen) und
[Zahlen](https://github.com/hansmaulwurf23/kopfrechnen).

Eine statische Seite (`index.html`), veröffentlicht direkt aus `main` über GitHub Pages. Die
Projektseiten der anderen Repos (`/blitzlesen/`, `/qwixx/`, …) bleiben davon unberührt.

Absichtlich ohne JavaScript, Service Worker und localStorage: Die Seite teilt sich die Domain mit den
Web-Apps und soll deren Speicher nie berühren.

Die Vorschaubilder sind verkleinerte `docs/screenshots/01-start.png` der beiden Repos:

```sh
convert ../lesen/docs/screenshots/01-start.png -resize 400x -strip -quality 80 bilder/lesen.jpg
```
