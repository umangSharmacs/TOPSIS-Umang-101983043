# TOPSIS-Umang-101983043

TOPSIS-Umang-101983043 is a python module for implementing Multiple Criteria Decision Making using TOPSIS. 

## Description

The module is essentially a function in which you enter a CSV file containing the models you wish to choose from, as well as the weights and impacts. 
The module will output your csv file, along with 2 more columns, one being the TOPSIS score, and the other being the rank of each model. 

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install TOPSIS-Umang-101983043
```

## Usage

```python

module_name=__import__('TOPSIS-Umang-101983043')
from module_name import topsis

topsis(file_name,weights,impacts,resultant_filename)
```
The first attribute is the CSV file you wish to upload which will contain all the models. 
Requirements for CSV file:
1. It should have more than 3 columns
2. First column is the object/variable name
3. From 2nd to last columns contain numeric values only

The second attribute is a string containing comma seperated weights.
Example: "1,1,1,1" 
The third attribute is a string containing comma seperated impacts. Impacts can only be '+' or '-'. 
Example: "+,-,-,+"

NUMBER OF WEIGHTS AND IMPACTS MUST EQUAL THE NUMBER OF COLUMNS IN THE INPUT FILE  (from 2nd to last columns).

Impacts must be either +ve or -ve.

Impacts and weights must be separated by ‘,’ (comma).

## Authors
Umang Sharma

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)
