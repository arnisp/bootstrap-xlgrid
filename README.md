# bootstrap-xlgrid

Bootstrap 3 XL CSS Grid addition for big and retina screens coverage.

## Extends Bootstrap v3 by:
* Adding col-xl (1600+), col-xxl (1920+), col-xxxl (2560+) classes with all related options: pull, push, offset
* Adding visible and hidden options for all three
* Optionally limiting visible-lg, hidden-lg (1200+) classes to max 1600px
* Optionally increasing container fixed width for all three screen sizes

## Installation
### Basic
Simply include bootstrap-xlgrid.min.css file in header, after bootstrap.css and before your own CSS styles.

### Remove fixed width increase for big screens
Delete block from beginning of css file which says "Set containers fixed sizes...".
Note: You can still use 'col' classes full with containers '.container-fluid'.

### Remove fixing/limiting of visible-lg and hidden-lg classes
Delete block from beginning of css file which says "Fix visible-lg and hidden-lg...".
Note: Bootstrap default behaviour is that '-lg' works for all screens 1200+. This sets maximum of 1600 and for bigger you have to use 'visible-xxl' etc.

## Other
* MIT license, so use, modify and improve as you wish
* Fork & Pull requests are welcome
* Will be glad to hear about projects you have used this on
* Enjoy
