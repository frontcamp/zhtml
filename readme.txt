

ZHTML CSS Framework
===================


DESCRIPTION
-----------


ZHTML is a CSS framework for rapid startup prototyping and simple HTML/CSS coding of single pages. It takes over some routine tasks (e.g., basic typography and grids). It helps organize and standardize the coding workflow. It supports component-based development and allows easy integration of third-party solutions.

**ZHTML Principles**

+ Configuration-first via CSS variables
+ Baseline markup, minimal core utilities
+ Deep styling via components
+ Simplified styling for basic elements and info-content
+ Specific styling via plugins (see zhtml.*.css)
+ Predictability and readability over “magic”


ONLINE DEMOS
------------


Online mirror of the /demo directory from this repository:
https://folio.frontcamp.com/demo/zhtml/


FILE STRUCTURE
--------------


/demo               - HTML demos (use files from /starter)
/docs               - framework documentation
/starter            - ready-to-copy files:
    /web                - static files
        /f              - fonts
            /open-sans  - Open Sans font (example)
        /i              - images
            /zhtml      - framework assets (e.g., list bullets)
        /s              - scripts & styles
            global.css  - global CSS template (example)
            mobile.css  - mobile CSS template (example)
            reset.css   - CSS reset
            zhtml.css   - CSS framework
            global.js   - global JavaScript template (example)
    index.html          - starter HTML template (example)
changelog.txt       - version history
license.txt         - MIT license
readme.txt          - this file


QUICK START
-----------


1. Copy the contents of /starter into your project.
2. See /starter/index.html for linking styles and structuring markup.
3. Configure the CSS variables to fit your needs.
4. For full usage, open the HTML docs in /docs.


LIMITATIONS
-----------

RTL & vertical layouts are not supported in current version.

