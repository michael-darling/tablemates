# tablemates

See who plays with whom most often, using your own board game stats.

Pick your BG Stats export file and tablemates draws an interactive network graph in your browser. The file is read locally and stays on your device.

## Use it

1. Export your data from BG Stats as a JSON file (`BGStatsExport.json`).
2. Open `index.html` in a browser, or visit the GitHub Pages site for this repo.
3. Choose your file.

## What you can do

- Switch between shared plays and estimated shared hours.
- Limit the graph to a range of years. The full span is the whole file, including plays with no date.
- Show names as initials (the default), first names, or full names.
- Include or hide the person with the most plays. That is usually whoever logs the games: they sit in every session and tie together people who never played each other. The export does not say who that is.
- Filter out weak links with the minimum slider.
- Tap a person to see their top play partners.
- Share or download the graph as an image.
- Copy a link that reopens this view. It carries the names on screen, the year range, and the links you’re looking at, so check the name setting first. The address stays on your device. A very large view keeps the strongest links so the address stays short enough to send. A picture is the better share when the graph is huge.
- Shorten that link when you want to text it. Shorten link sends the address to [is.gd](https://is.gd), which stores it and hands back a short link.

## How hours are estimated

Each play uses its logged duration when there is one. Otherwise it uses the average logged duration for that game, and failing that, the midpoint of the game's BoardGameGeek play-time range.

## Host it with GitHub Pages

In the repo settings, open Pages, pick the `main` branch and the root folder, and save. The whole tool is one static file, so there's nothing to build.

## Privacy

The graph is built in the browser. The file stays on your device. A copied link stores the graph in the address itself (the part after `#`), which the browser does not send to the server. Shorten link sends that address to is.gd, which stores it. Names are initials by default, and both links include only the names and year range currently shown.

## Not affiliated

tablemates is an independent project and isn't affiliated with BG Stats.
