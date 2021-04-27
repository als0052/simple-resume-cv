# simple-resume-cv

Template for a simple resume or curriculum vitae (CV), in XeLaTeX.

* **Created by:** Zach Scrivena
* **Created on:** 11-09-2014
* **Updated by:** als0052
* **Updated on:** 04-27-2021
* **Website:**<br>
  * [This repo - als0052](https://github.com/als0052/simple-resume-cv)
  * [Original repo - Zach Scrivena](https://github.com/zachscrivena/simple-resume-cv)
* **Lead author:**<br>
  * als0052
  * Zach Scrivena

## Compiled sample document
* Compiled sample document is found at ``/Examples/CV.pdf``
* [CV.pdf](https://github.com/als0052/simple-resume-cv/blob/master/Examples/CV.pdf)

## Main Features
- Simple template that can be further customized or extended.
- Template document contains numerous examples.
- Direct support for TrueType (TTF) and OpenType (OTF) fonts.
- Direct support for multilingual Unicode characters, with the appropriate fonts.
- Hyperlinks can be included in generated PDF.

## Overview

The main XeLaTeX source file is ``CV.tex``; the compiled document is ``CV.pdf``.

### Compilation Instructions
Instructions for compiling the document (TeX &rarr;(XeLaTeX)&rarr; PDF):

#### Method 1 ``latexmk``
- Use ``latexmk`` for fully automated document generation:
- ```latexmk -xelatex "CV.tex"```
- (add the `-pvc` switch to automatically recompile on changes)

#### Method 2 ``XeLaTeX`` directly
- Use ``XeLaTeX`` directly:
- ```xelatex "CV.tex"```
- (run multiple times to resolve cross-references if needed)

#### Method 3 TexMaker
- Settings file for TexMaker is found at ``/Miscellaneous/texmaker_settings_04-27-2021.ini``
- TODO: TexMaker compilation instructions

## License

This is free and unencumbered software released into the public domain.
For more information, please see the file `LICENSE` or refer to <http://unlicense.org>.

## Recent Major Changes

- Release v3.0
  - *Forked from master to https://github.com/als0052/simple-resume-cv*
  - Provides better support for other packages (e.g., biblatex) by removing the use of the longtable package for layout.
  - Note that this release introduces breaking changes; documents created using earlier releases of this template will need some minor changes to compile successfully.
