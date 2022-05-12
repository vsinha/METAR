# METAR.sh

Simple shell script to get METAR readings on your command line!

- cURLs weather.noaa.gov to get the forecast
- defaults to EDDK (my home airport) if no arguments are specified

## Usage

Just call the script with the ICAO code of the airport you want to query. It's as simple as follows:

```
$ ./metar EDDK
EDDK 120850Z AUTO 23006KT 200V290 9999 SCT036 BKN049 17/08 Q1020 NOSIG
```

You could also automate this and print the output in a text file, so you can use this everywhere you like.

## Installation

### Manual installation
1. Clone the repo using ```git clone https://github.com/flymia/METAR.git```
2. cd into the directory ```cd METAR```
3. Run the command

You could add a symlink to a folder, that is in your path. For example, I have ```$HOME/bin``` in my ```$PATH``` variable. So I do the following:

````bash
cd ~/bin
ln -s ~/git/METAR/metar . 
````

Now I can call the script from anywhere.

# Other stuff
## How to read a METAR

- [Wunderground METAR tutorial](http://www.wunderground.com/metarFAQ.asp?MR=1)
- [METAR wiki page](https://en.wikipedia.org/wiki/METAR)
- [METAR decoder tool](http://heras-gilsanz.com/manuel/METAR-Decoder.html)
- [METAR mysteries](http://www.cfidarren.com/r-metarmystery.htm) (explains some of the acronyms and history)


