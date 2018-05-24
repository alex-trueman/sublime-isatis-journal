# Sublime Text 3 Customizations for Isatis Journals

These customizations add a colour scheme and commenting support to Sublime Text 3 for Isatis journals.

## Installation

Use `Package Control` to install the latest version:

1. Press Ctrl + ⇧ + P to open the command palette.
2. Type `Package Control: Install Package` and press enter. Then search for `Isatis Journal`.

Once installed open an Isatis journal file with the '.ijnl' extension. Go to the `View->Syntax->Open all with current extension as...` menu and select `ijnl`.

## Syntax definition

The macro language syntax highlighting definition allows special highlighting of process names and their parameters, variables, and comments in Isatis journals. Certain errors are also highlighted in code.

I have tested this scheme with the Material Colour Scheme, other colour schemes may not work as well.

## Commenting support

With commenting support when you select lines in a journal and type Ctrl + / the lines will be commented with '#'. If the lines are already commented they will be un-commented.

![Comment lines](fig/comment-lines.gif)