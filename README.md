# Join-Validator

## How to Use?
* Compile the validator using   
```
g++ main.cpp
```
* Run the validator using 
```
./a.out inputR inputS outputFile
```
* For comparing output files use
```
comm < (sort -u outputFile) < (sort -u yourOutput)
```

## Command line arguments
* inputR - Path to file containing relation R
* inputS - Path to file containing relation S
* outputFile - Path to output file

