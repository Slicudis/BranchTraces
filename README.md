# BranchTraces
This repository contains lots of trace files that can be used for benchmarking branch predictors. NOTE that different groups of files can have different formats.

# Formats

### GROUP 1: 
0x[HEX BRANCH ADDRESS] [Taken = 1, Not-taken = 0] \
```Example: 0xff0014 1``` 
### GROUP 2: 
0x[HEX BRANCH ADDRESS] [Taken = T, Not-taken = NT] 0x[HEX DESTINATION ADDRESS] \
```Example: 0x422af5 NT 0x423ca5``` 
### GROUP 3: 
[HEX BRANCH ADDRESS] [Taken = t, Not-taken = n] \
```Example: 2362e4 t``` 
