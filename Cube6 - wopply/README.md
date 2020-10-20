# CTF2020 - Cube Apocalypse Quali: wopply

![date](https://img.shields.io/badge/date-14.10.2020-brightgreen.svg)  
![solved in time of CTF Qualification](https://img.shields.io/badge/solved-in%20time%20of%20CTF%20%20Qualification-brightgreen.svg)  
![misc category](https://img.shields.io/badge/category-misc-lightgrey.svg)

## Description
![desc](desc.png)

## Attached files
- 

## Flag
```
cyber_h0m0gr4phsAreR34l
```

## Detailed solution
The link in the description lead to a page that was showing a cute picture of a cat. Nothing of interest elsewhere, but the url!

![wopply](wopply.png)



The url contained some [Punycode](https://en.wikipedia.org/wiki/Punycode ) that made it look like 'wopply' even if it wasn't.

Correcting that by replacing the punycode with an actual 'w' lead to a page with the flag hex encoded.

![result](result.png)

