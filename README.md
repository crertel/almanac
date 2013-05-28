#almanac#

A small, handy collection of simple text files that are useful to devs.


#Purpose#
Every so often it's handy to have a list of easily-parsable data items, especially for one-off hacks.

/usr/share/dict is one such example. This is an attempt to provide a more useful basic set of info for developers.


#Layout#
There are many types of information that we'd like to have as developers--common names, lists of states, lorem ipsum text, etc.

## Miscellanous info ##

Information that doesn't fit cleanly into other structures goes into the __/misc/__ folder.

* __/misc/lorem_ipsum__ is several lines of the familiar lorem ipsum text.

## Geographic information ##

Information about countries can also be very useful.

* __/geography/country_codes__ is a list of the ISO316601 alpha 2 codes and the countries they represent. These codes are used to index the rest of the directory.
* __/geography/<COUNTRY CODE>/states__ is a list of the states/provinces in that country.
* __/geography/<COUNTRY CODE>/territories__ is a list of territories in that country.
