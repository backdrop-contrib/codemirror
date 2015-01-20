# Codemirror Widget

The codemirror widget project allows you to add [CodeMirror](http://codemirror.net/) 
functionality to your text fields in Backdrop.

## Installation

1. Install this module using the official Backdrop CMS instructions at https://backdropcms.org/guide/modules
2. Download the CodeMirror JavaScript library from http://codemirror.net/ (currently tested with v4.11).
3. Extract the CodeMirror archive you just downladed to the `/libraries/` directory in the root of your Backdrop installation.
4. Rename the expanded folder (most likely codemirror-4.11) to `codemirror`. 
5. Make sure the full path is `[backdrop installation]/libraries/codemirror`.
6. Enable the module at `[your web address]/admin/modules/list` under "Other".
7. You can now configure any existing text field at `[you web address]/admin/structure/types/manage/[your content type]/fields` to use the CodeMirror widget.
8. Configure your widget at `[your web address]/admin/structure/types/manage/[your content type]/fields/[your field]`.

## License
This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.

## Current Maintainers

* Jerad Bitner (http://github.com/sirkitree)

## Credits

This module was originally written for Drupal by Darren Mothersele (https://www.drupal.org/u/darrenmothersele), based on  Marijn Haverbeke CodeMirror project (http://codemirror.com/).
