yuidoc-bootstrap-theme
======================

A revamped yuidoc theme with bootstrap.

Grab from npm via:
     
     npm install yuidoc-lucid-theme
     
https://www.npmjs.org/package/yuidoc-lucid-theme

When running yuidoc from command line:
    -t : themedir
    -H : helper js file

Ex.

    yuidoc -t _location_/yuidoc-lucid-theme -H _location_/yuidoc-bootstrap-theme/helpers/helpers.js

When running with grunt it is best to use this as a submodule.

Then under yuidoc.json options add:

    "themedir" : _location_/yuidoc-lucid-theme,
    "helpers" : [ _location_/yuidoc-lucid-theme/helpers/helpers.js ]

Ex.

    {
        "name": "Example",
        "url": "www.example.com",
        "version": "0.1.0",
        "options": {
            "paths": "_location to parse_",
            "outdir": "build/docs",
            "exclude": "lib,docs,build",
            "themedir": "_location_/yuidoc-lucid-theme",
            "helpers": ["_location_/yuidoc-lucid-theme/helpers/helpers.js"]
        }
    }

