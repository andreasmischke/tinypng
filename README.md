# tinypng

Python3 commandline client for [tinypng.com](https://tinypng.com/)

## Installation

You need to install [python3](https://wiki.python.org/moin/BeginnersGuide/Download)
and [requests](http://docs.python-requests.org/en/master/user/install/#install) first.

Then clone this repository or download just the tinypng file.

[Get an API Key from tinypng.com](https://tinypng.com/developers) and enter it in the tinypng file:

```python
#!/usr/bin/env python3
import argparse
import requests
import sys

API_KEY = '<YOUR KEY GOES HERE>'

...
```

Add the file to your PATH environment variable and use it!

## Usage

```bash
usage: tinypng [-h] [-o OUTPUT] inputfile

positional arguments:
  inputfile             The file to be tinified. May be JPG or PNG

optional arguments:
  -h, --help            show this help message and exit
  -o OUTPUT, --output OUTPUT
                        Filename where the tinified output should be stored.
                        Defaults to inputfile with ".tiny" inserted before the
                        file type extension
```

## License

See the LICENSE file for license rights and limitations (MIT).
