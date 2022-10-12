# Casualty Actuarial Society Hacktuary Challenge (2022)

*“a contest designed to showcase the actuarial skill set in developing novel risk engineering solutions,
using publicly available data and featuring interactive elements”*

More info: https://www.casact.org/article/casualty-actuarial-society-announces-2022-cas-hacktuary-challenge

This will be my repo for the challenge.


## Important Note: R Packages 

This shiny application was built between April and August 2022.  
While it is normal to have R packages being routinely updated, it appears that two updated packages are breaking some display parameters and icons.

Therefore, until the code is fixed to accomodate for the new packages, please run this shiny application using:   

`install.packages("https://cran.r-project.org/src/contrib/Archive/fontawesome/fontawesome_0.2.2.tar.gz", repos=NULL, type="source")`  
`install.packages("https://cran.r-project.org/src/contrib/Archive/flexdashboard/flexdashboard_0.5.2.tar.gz", repos=NULL, type="source")`

-OR- proceed with fixes...  

1) We need to modify icon names as seen below:  

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
