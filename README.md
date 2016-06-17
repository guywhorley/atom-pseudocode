# atom-pseudocode

## Overview

This project is my stab at creating an atom theme and language package.

The theme/language combination is meant to highlight a range of pseudocode keywords, along with associated color syntax.

Currently, neither the language nor theme packages conform to the Atom package standards required  for inclusion into the online package repository.

## package: <q>pseudocode-syntax</q>

Pseudocode-syntax is a dark-themed set of styles for atom. I have not attempted to modify the full range of Atom elements. Rather, I have set styles for the pseudocode package, along with css, scss files.

## To Install

1. Place the folder 'pseudocode-syntax' into the \{ATOM_ROOT_DIR\}/packages directory.
2. Place the folder 'language-pseudocode' into the \{ATOM_ROOT_DIR\}/packages directory.
3. In the Atom Editor > Packages > Settings View > Manage Themes: set "Syntax Theme" = Pseudocode.

## package: <q>language-pseudocode</q>

The pseudocode language package has been configured to recogined three different 'pseudocode' file extensions:<br>
1. .pc (i.e. 'pseudocode')<br>
2. .sdo (i.e. 'pseudo')<br>
3. .ptx (i.e. 'pseudocode text file')<br>

*Pseudocode Keywords*

The following screenshots show the range of 'pseudocode' keywords and thematic style:

![Image of pseudocode keywords](https://github.com/guywhorley/atom-pseudocode/blob/master/assets/atom1.PNG)

![Image of pseudocode keywords](https://github.com/guywhorley/atom-pseudocode/blob/master/assets/atom2.PNG)
