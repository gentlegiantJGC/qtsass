# qtsass
Compile SCSS files to valid Qt stylesheets.

SASS brings countless amazing features to CSS.
Besides being used in web development, CSS is also the way to stylize a Qt desktop application.
However, Qt's CSS has a few variations that prevent the direct use of SASS compiler.

The purpose of this tool is to fill the gap between SASS and Qt-CSS by handling those variations.

## Qt's CSS specificities
WIP 

"!" in selectors

qlineargradient

qrgba


## Executable usage
To compile your Qt-SASS stylesheets:
qtsass style.scss -o style.css