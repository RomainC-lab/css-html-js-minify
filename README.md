# css-html-js-minify

- **StandAlone Async single-file cross-platform no-dependencies Unicode-ready Python3-ready Minifier for the Web.**


```bash
juan@z:~/$ python css-html-js-minify.py --help

usage: css-html-js-minify.py [-h] [--version] [-w WRAP] [--quiet] fullpath

CSS-HTML-JS-Minify - StandAlone Async single-file cross-platform 
no-dependencies Unicode-ready Python3-ready Minifier for the Web.

positional arguments:
  fullpath              Full path to local CSS file or folder with CSS.

optional arguments:
  -h, --help            show this help message and exit
  --version             show program's version number and exit
  -w WRAP, --wrap WRAP  Wrap Output to N chars per line, CSS Only.
  --quiet               Quiet, force disable all Logging.

CSS-HTML-JS-Minify: 
Takes a file or folder full path string and process all CSS/HTML/JS found. 
If argument is not a file or folder it will fail and raise errors. 
StdIn to StdOut is deprecated since may fail with unicode characters.
```


# Try it !:

```
wget -O - https://raw.githubusercontent.com/juancarlospaco/css-html-js-minify/master/css-html-js-minify.py | python3
```

# Install permanently on the system:

```
sudo wget -O /usr/bin/css-html-js-minify https://raw.githubusercontent.com/juancarlospaco/css-html-js-minify/master/css-html-js-minify.py
sudo chmod +x /usr/bin/css-html-js-minify
css-html-js-minify
```


# Requisites:

- [Python 3.x](https://www.python.org "Python Homepage") *(or Python 2.x)*


Donate, Charityware :
---------------------

- [Charityware](https://en.wikipedia.org/wiki/Donationware) is a licensing model that supplies fully operational unrestricted software to the user and requests an optional donation be paid to a third-party beneficiary non-profit. The amount of donation may be left to the discretion of the user. Its GPL-compatible and Enterprise ready.
- If you want to Donate please [click here](http://www.icrc.org/eng/donations/index.jsp) or [click here](http://www.atheistalliance.org/support-aai/donate) or [click here](http://www.msf.org/donate) or [click here](http://richarddawkins.net/) or [click here](http://www.supportunicef.org/) or [click here](http://www.amnesty.org/en/donate)
