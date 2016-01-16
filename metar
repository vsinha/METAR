#!/bin/sh

# use KRNT as default airport unless something else is specified on cli args
if [ -z "$1" ]; then
  AIRPORT="KRNT"
else
  AIRPORT="$1"
fi

CURLURL="http://weather.noaa.gov/pub/data/observations/metar/stations/"
CURLURL+=$AIRPORT
CURLURL+=".TXT"

curl --silent $CURLURL | grep $AIRPORT

