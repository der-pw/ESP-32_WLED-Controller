# ESP-32_WLED-Controller_addon  [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

[deutsche Version unten ->](#Deutsch)

![PCB-top_addon](images/addon.jpg)

This addon board allows you to expand the ESP-32_WLED-Controller with the Sound Reactive feature https://github.com/atuline/WLED. The board is practically stacked on top of the controller using 2.54mm pin and socket headers.

## Settings
![Settings](images/sr_config.jpg)

WLED Sound Reactive comes with an additional configuration menu.
For Squelch and Gain, you'll need to configure your own settings.
Microphone type is **Generic Analog**.
The Analog Input Pin is on `GPIO36`.

## Case
![case](case/case.jpg)

There is also a simple case available for connecting the 3.5mm audio jack.
The STEP file for further modifications is also located in the "case" folder.

## Gerber Data

Even though I believe this tiny thing can be hand-soldered, there are also fabrication data available. However, the assembly is double-sided, as the audio jack is mounted on the underside for space reasons.
The audio jack is named PJ230D. I found it inexpensively at https://de.aliexpress.com/item/4000661908135.html.

---
## Deutsch

![PCB-top_addon](images/addon.jpg)

Mit dieser Addon-Platine lässt sich der ESP-32_WLED-Controller um das Sound Reactive Feature erweitern https://github.com/atuline/WLED. Die Platine wird praktisch im "Huckepack" auf den Controller gesteckt.
Dazu lassen sich 2.54mm Stift- und Buchsenleisten verwenden.

## Einstellungen
![Einstellungen](images/sr_config.jpg)

WLED Soundreactive hat ein weiteres Konfigurationsmenü.
Für Squelch und Gain muss man seine eigenen Einstellungen fingen.
Micropone type ist **Generic Analog**.  
Der Analog Input Pin liegt auf `GPIO36`.

## Gehäuse
![case](case/case.jpg)

Es gibt auch ein einfaches Gehäuse, damit man den 3,5mm Klinkenstecker anschließen kann.
Die STEP-Datei für weitere Modifikationen befindet sich auch in dem Ordner "case" 

## Gerberdaten

Auch wenn ich der Meinung bin, dass man das kleine Teil von Hand löten kann, gibt es auch hierzu Fertigungsdaten. Die Bestückung ist allerdings zweiseitig, da aus Platzgründen die Klinkenbuchse auf der Unterseite montiert wird.
Die Klinkenbuchse heißt PJ230D. Diese habe ich günstig unter https://de.aliexpress.com/item/4000661908135.html gefunden.