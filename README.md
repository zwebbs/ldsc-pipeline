# ldsc-pipeline

## Table of Contents

1. [Preparing the compute environment](#compute_env)


<a name="compute_env"/>
## Preparing the compute environment

We make use of distinct virtual environments in the ldsc pipeline for the purposes of reproducible analyses on the Gardner CRI cluster at the University of Chicago. Python versions for each envirionment can be found in the comment header of the `requirements.txt` file in each environment directory. To prepare each virtual environment, you can follow the steps below:


1. Preparing the ldsc virtual environment

```bash
cd env/ldsc/
python2 -m virtualenv .
pip install -r requirements.txt
```

2.  Downloading ldsc

```
git clone https://github.com/bulik/ldsc.git <your/path/to/software/>ldsc/
export PATH=$PATH:<your/path/to/software/>/ldsc

# test it out
./ldsc.py 

```
