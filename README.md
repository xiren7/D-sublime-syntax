D syntax highlighting for Sublime Text 3
----------------------------------------

All the files are taken from official D syntax package: https://github.com/sublimehq/Packages/tree/master/D

I only completely rewrite the D.sublime-syntax file

Installation
------------
1. Clone this repository into your Sublime Text packages folder. You can find where your folder is located by clicking on 'Preferences -> Browse Packages'. Probable places:
    * Linux - `~/.config/sublime-text-3/Packages/`
    * Windows - `sublime-text-3\Data\Packages`
    * Mac OSX - `~/Library/Application Support/Sublime Text 3/Packages`
2. (optional) Disable the built-in D Package: Package Control --> Disable Package --> D
3. Open one of *.d file, select the D2 syntax

Features
--------
- Highlights(correctly) almost everything (tests with Boxy Ocean theme)
    * regex expression
    * format placeholder
    * embedded assembly code (requires installing assembly syntax)
- Displays the signature of function and type (via ctrl+R)

