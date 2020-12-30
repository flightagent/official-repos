# Instruments & panels for Flight Agent


![FA panel](https://img.shields.io/badge/FlightAgent-panel-blue)

## Panels in this repo

- M20 panel for a custom cockpit, consist of two panels:
  - m20-panel-main
  - m20-panel-radio

## Contributing or creating your own repo

Include a README.md and a badge

``` md
![FA panel](https://img.shields.io/badge/FlightAgent-panel-blue)
```

Include fodler with panels and instruments.

Notify flightagent.pro@gmail.com or create PR on this project changing file repos.yml

## repos.yaml

The repos.yaml file is the list of official and notified repositories for panels

## Creating gauges

Use Flight Agent yaml format to define gauge and generate svg from there. Only: ![FlightAgent PRO version](https://img.shields.io/badge/FlightAgent-PRO-orange)

* Cutting "windows" can be done with [Inkscape][inkscape], selecting paths (not groups), and selecting "Path > Difference"
* Some changes like moving texts can be done on [Inkscape][inkscape].
* Exporting to .png can be done from [Inkscape][inkscape], selection "BEST Quality" in advanced mode and watch on resolution.
* Final shadows or specific backgrounds can be add with [Gimp][gimp] over the png.
* Using [Tinypng](https://tinypng.com/) or another, the size of the image can be greatly reduced.

[gimp]: https://www.gimp.org/
[inkscape]: https://inkscape.org/