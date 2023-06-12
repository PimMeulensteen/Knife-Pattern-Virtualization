# Knife Pattern Virtualization
This repository contains the code for the thesis "Cutting edge research: virtualization of knife
striation patterns". 


## Installation
The code is written in Python 3.9. The required packages are listed in the requirements.txt file.
To install the packages, run the following command in the terminal:
```
pip install -r requirements.txt
```

## Usage
The code can be run by executing the main.py file.
```
python3 main.py [options] <knife> <knife angle> <sample1> <sample1 angle> <sample2> <sample2 angle> <desired angle> <output>
```
The arguments are:
- knife: the path to the knife image
- knife angle: the angle of the knife in degrees
- sample1: the path to the first sample image
- sample1 angle: the angle of the first sample in degrees
- sample2: the path to the second sample image
- sample2 angle: the angle of the second sample in degrees
- desired angle: the angle of the desired virtual sample in degrees
- output: the path to the output image


The options are:
- -h, --help: show the help message and exit
- -v, --verbose: show the progress of the program
- --no-cache (default: False): do not use the cache
- --cores [CORES] (default: 4): the number of cores to use
- --res [RES] (default: 20): the resolution to fit the knife
- --iter [ITER] (default: 3): the number of iterations to fit of the knife
