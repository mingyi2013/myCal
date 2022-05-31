# install github test package: myCal

## step 1. copy code link, eg:
 https://github.com/mingyi2013/myCal
 copy "code" -> Clone : HTTPs 
 in terminal: R_myPackage1 mingy/
 git clone https://github.com/mingyi2013/myCal.git

## step 2. install file.
in parent path of myCal:
R CMD INSTALL myCal/

------
installing to library ‘/Users/mingyi/Library/R/4.0/library’
installing *source* package ‘myCal’ ...
using staged installation
R
byte-compile and prepare package for lazy loading
help
installing help indices
building package indices
testing if installed package can be loaded from temporary location
testing if installed package can be loaded from final location
testing if installed package keeps a record of temporary installation path
DONE (myCal)
--------

## step 3. test package
library(myCal)
my_calc(1:10, mean) # test
