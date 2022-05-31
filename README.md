# install github test package: myCal
## step 1. copy code link, eg:
 Click icon and copy link by "code" -> Clone : HTTPs 
 In terminal:
 git clone https://github.com/mingyi2013/myCal.git
 unzip file by: tar -xvf myCal/myCal.tar.gz

## step 2. install file.
in parent path of myCal:
R CMD INSTALL myCal/

## step 3. test package
library(myCal)
my_calc(1:10, mean) # test
