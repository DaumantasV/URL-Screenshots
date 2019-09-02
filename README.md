# URL-Screenshots

Based on https://medium.com/@0xdjangox0/simple-screenshot-script-using-python-selenium-b872c19e5471

Before using this make sure you have selenium installed in your python environment:

`pip install selenium`

The script screenshots.py accepts a list of URLs as an argument and returns screenshots of the following URLs. It can be run by using the following bash command:

`for x in $(cat list.txt) ; do python screenshots.py --url  $x --output ${x//[^A-Za-z0-9._-]/_}.png ; done`



