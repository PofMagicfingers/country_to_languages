# Country to Languages

This document translates ISO3166 Country Codes to official and widely spoken languages in corresponding countries in ISO639-1. At the moment, the list only include ISO639-1 languages (2 letters code).

Most of the source is Wikipedia, so it might not be perfect. Feel free to fork, pull request etc to correct the list.

A ruby gem will be done, when I'll have the time to do it right. Do it before me if you want :-)

Until then, the document is available in the following format :
* ruby : an Hash, and the only format including country names in english as comments
* csv : First column, country code, second column, all languages separated with spaces
* json : Object containing arrays of languages
* Excel, Numbers : Original working document ( contains a formula to translate content to ruby hash )

## Licence

MIT
