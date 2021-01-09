# Instruments & panels for Flight Agent


![FA panel](https://img.shields.io/badge/FlightAgent-panel-blue)

## Creating repos for instrument and actons

*"action-"* for actions repositories
*"-panel-"* for panel repositories
*other*, for instruments repositories

See examples.

## Creating your own repo

Include a README.md and a badge

``` md
![FA panel](https://img.shields.io/badge/FlightAgent-panel-blue)
```

Include fodler with panels and instruments.

## Contributing

The panel will be added as an official panel. So every other can use it.

Notify flightagent.pro@gmail.com to be added to the official list

## Actions Repositories

*actions*, if already defined one, prevails the order

A repository can be used por actions

Events can be predefined or not.

Predefined events:
 - start: when the app starts
 - exit: when the app finishes
 - startfs: when a sim starts
 - ...

Actions predefined: (work as predefined events)
 - closefa
 - restartfa
 - closefs
 - osreboot
 - osshutdown
 - setsimvar
 - showtext
 - loadflight
 
 See directories "action-" for examples