# OH2-BasicUI-Icons
Use icons as button labels instead of plain text.

Currently you can use Font-awesome and Material Icons as button labels.

## Installation
1. Place the icons.html file inside the Openhab2 HTMl folder
2. Add to your .sitemap `Webview url="/static/icons.html"`

## Usage
Currently only Font-awesome and Material Icons are supported
Icons can be defined as "[$vender $iconClass]"

Vendors are:
* fa (Font-Awesome)
* md (Material Icons)

#### &nbsp;&nbsp;&nbsp;Example:
  ##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Normally
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ```Switch item=PlayPause mappins=[PLAY="Play", PAUSE="Pause"]```
  ##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Font-Awesome
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ```Switch item=PlayPayse mappings=[PLAY="[fa fa-play]", PAUSE="[fa fa-pause]"]```
  ##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Material Icons
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;```Switch item=PlayPayse mappings=[PLAY="[md play_arrow]", PAUSE="[md pause]"]```
