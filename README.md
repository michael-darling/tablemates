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
- Download the graph as an image to share.

## How hours are estimated

Each play uses its logged duration when there is one. Otherwise it uses the average logged duration for that game, and failing that, the midpoint of the game's BoardGameGeek play-time range.

## Host it with GitHub Pages

In the repo settings, open Pages, pick the `main` branch and the root folder, and save. The whole tool is one static file, so there's nothing to build.

## Privacy

Everything runs client-side. Names are anonymized to initials by default; check the setting before you share an image.

## Not affiliated

tablemates is an independent project and isn't affiliated with BG Stats.
