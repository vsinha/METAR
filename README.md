## METAR.sh

`$ ./metar.sh [airportcode]`

Simple shell script to get METAR readings on your command line!

- cURLs weather.noaa.gov to get the forecast
- defaults to KRNT (my home airport) if no arguments are specified
- desgined to work with [TextBar](http://www.richsomerfield.com/apps/) to put METAR into your osx menubar

### How to read a metar

[Wunderground METAR tutorial](http://www.wunderground.com/metarFAQ.asp?MR=1)
[METAR wiki page](https://en.wikipedia.org/wiki/METAR)
[METAR decoder tool](http://heras-gilsanz.com/manuel/METAR-Decoder.html)
[METAR mysteries](http://www.cfidarren.com/r-metarmystery.htm) (explains some of the acronyms and history)

*Example:*
```
KRNT 161553Z 12007KT 10SM -RA OVC036 07/06 A2965 RMK AO2 SLP046 P0003 T00720061

Location: KRNT
Day of month: 16
Time: 15:53 UTC
Wind:  True direction = 120 degrees, Speed: 7 knots
Visibility: 10 Statute Miles
Weather: Light Rain 
Clouds: Overcast sky , at 3600 feet above aerodrome level
Temperature: 07 degrees Celsius
Dewpoint: 06 degrees Celsius
QNH: 29.65 inHg
```
