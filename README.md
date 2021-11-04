# Spitbol and SNOBOL4 TextMate Grammar Highlighting

A .tmLanguage extension for the Spitbol and SNOBOL4 programming languages- for usage in Sublime, VsCode, etc!

There is definitely some rooms for improvement, but far as I know this is the only tmLanguage extension for the language.

## Features

* Contains all the functions and keywords that are found in Spitbol (as extracted from the CATSPAW, Inc. Spitbol manual).
* Contains all the functions and keywords that are found in SNOBOL4 (as extracted from "The Green Book" SNOBOL manual by Ralph Griswold).  

_As Spitbol is essentially a superset of SNOBOL4; I feel it is reasonable to classify this grammar as compatible with both programming languages._

## IRO

This tmLanguage file was generated by using the excellent tool "IRO".  I have included the configuration file that was used (iro_snobol_format.txt).

https://eeyo.io/iro/
https://medium.com/@model_train/creating-universal-syntax-highlighters-with-iro-549501698fd2


## Requirements

File extensions .sno or .sbl

## Known Issues

Incorrect spacing on '=' statements can cause some highlighting confusion when used with keywords.

### 1.0.0

Initial release.
