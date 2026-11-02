# tablemates

See who plays with whom most often, using your own board game stats.

Pick your BG Stats export file and tablemates draws an interactive network graph in your browser. Nothing is uploaded: the file is read locally and never leaves your device.

## Use it

1. Export your data from BG Stats as a JSON file (`BGStatsExport.json`).
2. Open `index.html` in a browser, or visit the GitHub Pages site for this repo.
3. Choose your file.

## What you can do

- Switch between shared plays and estimated shared hours.
- Show names as initials (the default), first names, or full names.
- Include or hide the owner, who is in nearly every play and tends to tie the graph into one knot.
- Filter out weak links with the minimum slider.
- Tap a person to see their top play partners.
- Share or download the graph as an image.
- Copy a link that reopens this same view. The link carries only the names on screen and the links you’re looking at, so check the name setting first. Very large graphs should be sent as an image.

## How hours are estimated

Each play uses its logged duration when there is one. Otherwise it uses the average logged duration for that game, and failing that, the midpoint of the game's BoardGameGeek play-time range.

## Host it with GitHub Pages

In the repo settings, open Pages, pick the `main` branch and the root folder, and save. The whole tool is one static file, so there's nothing to build.

## Privacy

Everything runs client-side. A copied link stores the graph in the address itself (the part after `#`), which the browser does not send to the server. Names are initials by default, and the link includes only the names currently shown.

## Not affiliated

tablemates is an independent project and isn't affiliated with BG Stats.
