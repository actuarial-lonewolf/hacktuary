# Casualty Actuarial Society Hacktuary Challenge (2022)

*“a contest designed to showcase the actuarial skill set in developing novel risk engineering solutions,
using publicly available data and featuring interactive elements”*

More info: https://www.casact.org/article/casualty-actuarial-society-announces-2022-cas-hacktuary-challenge

This will be my repo for the challenge.


## Note:  
  
The Map section in the app requires an active internet connection as it pulls data from OSRM and/or Google.  
For a better user experience, please provide a Google Maps API key in the upper section of the code.
A Google Maps API key will provide auto-complete feature and better search results.  
  
The file lgb.fit.MODELv6.txt.7z needs to be decompressed into lgb.fit.MODELv6.txt.  


## Important Note: R Packages 

This shiny application was built between April and August 2022.  
While it is normal to have R packages being routinely updated, it appears that two updated packages are breaking some display parameters and icons.

The code has been fixed to accomodate for the new packages.

[Icons modification:](https://fontawesome.com/docs/web/setup/upgrade/whats-changed#icons-renamed-in-version-6)  

| Old Name  | New Name |
| ------------- | ------------- |
| male  | person  |
| female  | person-dress  |
| car-crash  | car-burst  |
| ambulance | truck-medical  |
| parking  | square-parking  |
| info-circle  | circle-info  |
| calendar-alt  | calendar-days  |
| directions | diamond-turn-right |
| map-signs | signs-post |
| map-marked-alt | map-location-dot |
| map-marker-alt | location-dot |
| globe-americas | earth-americas |
| coffee | mug-saucer |
| tachometer-alt | gauge |
| walking | person-walking |
| atlas	| book-atlas |
| sync | arrows-rotate |
| exchange-alt | right-left |
| long-arrow-alt-right | right-long |
| compress-alt | down-left-and-up-right-to-center |
| random | shuffle |
| redo | arrow-rotate-right |
  
2) We need to add the following code in the CSS style section.
  
  ` .value-box{ color:inherit; }`
