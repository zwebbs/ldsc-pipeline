# ldsc-pipeline


# Preparing compute environments
We make use of distinct virtual environments in the ldsc pipeline for the purposes of reproducible analyses on the Gardner CRI cluster at the University of Chicago. Python versions for each envirionment can be found in the comment header of the `requirements.txt` file in each environment directory. To prepare each virtual environment, you can follow the steps below:
```bash
cd env/ldsc/
python2 -m virtualenv .
pip install -r requirements.txt
```
