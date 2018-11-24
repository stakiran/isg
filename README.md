# isg
Incremental searchable glossary system.

## Demo
See GitHub Pages.

- (1) Before: [glossary.md](glossary.md)
- (2) Build with `python builder.py -i glossary.md`...
- (3) After: [index.html](index.html)

## Overview
- (1) Write your glossary to a markdown file with list grammer.
- (2) Build.

And the html file is generated. This file contains the incremental search, so useful for your reading and studying.

## Requirement
- Python 3.6+

## How to build
See [build.bat](build.bat), this is a build script for Windows.

```bat
python builder.py -i glossary.md -o index.html -t template.html
```

## License
[MIT License](LICENSE)

But about [jquery.min.js](jquery.min.js), see also [jquery.org/license](https://jquery.org/license/).

## Author
[stakiran](https://github.com/stakiran)
