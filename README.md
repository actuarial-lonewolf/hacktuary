# Casualty Actuarial Society Hacktuary Challenge (2022)

*“a contest designed to showcase the actuarial skill set in developing novel risk engineering solutions,
using publicly available data and featuring interactive elements”*

More info: https://www.casact.org/article/casualty-actuarial-society-announces-2022-cas-hacktuary-challenge

This will be my repo for the challenge.


## Important Note: R Packages 

This shiny application was built between April and August 2022.  
While it is normal to have R packages being routinely updated, it appears that two updated packages are breaking some display parameters and icons.

Therefore, until the code is fixed to accomodate for the new packages, please run this shiny application using:

`install_version("fontawesome", version = "0.2.2", repos = "http://cran.us.r-project.org")`
`install_version("flexdashboard", version = "0.5.2", repos = "http://cran.us.r-project.org")`

