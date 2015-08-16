## Upcoming Changes (unreleased)
- Added method ```valid_country``` for returning country for parsed phone just in case phone number was valid
- Changed behavior of method ```country```, now it returns main country for international code in case there is such country, or first country from array

## 0.4.9 - July 28, 2015

- Parsing of phone may return type ```:fixed_or_mobile``` even when patterns are different but valid for both ```:mobile``` and ```:fixed_line```. Previously it could be only when patterns match
- Added changelog

## 0.4.8 - July 27, 2015

- Updated data and added test for TT phone