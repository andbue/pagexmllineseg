# pagexmllineseg
Some python functions to write text lines into LAREX PageXML files

Opens PageXML file, converts to newest pagexml version 2017, segments the text regions and writes xml to file.
Output is written to input file if no output file is given.

How to use:
```python
from pagexmllineseg import pagexmllineseg
pagexmllineseg("larexoutput.xml")
```

Most lines in the file are taken from https://github.com/mittagessen/kraken/blob/master/kraken/pageseg.py
