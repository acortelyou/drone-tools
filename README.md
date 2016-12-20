drone-tools
======

dji2papywizard.py
-------

Extracts DJI image metadata into a Papywizard panohead data file for use with stitching software

```
usage: dji2papywizard.py [-h] [-t TITLE] [-c COMMENT] [-o OUTPUT] [--no-bracket] INPUT [INPUT ...]

arguments:
  -h, --help    show this help message and exit
  -t TITLE      title for panohead file (default: Untitled Panorama)
  -c COMMENT    comment for panohead file (default: Generated by dji2papywizard.py)
  -o OUTPUT     filename for output (default: pano.xml)
  --no-bracket  ignore hdr bracketing information (default: False)
  INPUT         image files to process
```
