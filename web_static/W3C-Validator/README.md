# W3C validator for Holberton School

For HTML and CSS files.

Based on 2 APIs:
- https://validator.w3.org/nu/
- https:jigsaw.w3.org/css-validator/validator

## Installation
1. Clone this repository
'''sh
git clone https://github.com/holbertonscholl/W3c-Validator.git
'''

2. Run shell script (see example in [usage] (#usage) section below)
## Usage:

Simple file:

'''sh
./w3c_validator.py index.html
'''

Multiple files:

'''sh
./w3c_validator.py index.html header.html styles/common.css
'''

All errors are printed in 'STDERR'; Exit status = # of errors (0 on success)


## References
https://developer.mozzilla.org/en-US/
