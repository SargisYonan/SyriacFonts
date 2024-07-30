# The Nohadra Syriac Fonts Collection

![CI Status](https://github.com/SargisYonan/NohadraSyriacFonts/actions/workflows/fontbakery.yml/badge.svg)

Nohadra fonts are a bold, geometric, and monospaced Syriac typeface.
<p align="center">
  <img src="samples/NohadraSyriac-Sapna-nohadra-sample.png" alt="" width="300"/> <img src="samples/NohadraSyriac-Amedia-nohadra-sample.png" alt="" width="300"/>
</p>

## Introduction

The Nohadra Syriac Font family includes Syriac typefaces with square, block-like characters and uniform line thickness. This font offers a modern and minimalistic design and feel. 

## Samples

### Nohadra - Sapna
<p align="center">
  <img src="samples/NohadraSyriac-Sapna-nohadra-sapna-text.png" alt="" width="400"/>
</p>

Sapna is a monospaced and minimal block style Syriac typeface. [View sample text](samples/index-sapna.html)


<p align="center">
  <img src="samples/NohadraSyriac-Sapna.png" alt="" width="3000"/>
</p>

### Nohadra - Amedia
<p align="center">
  <img src="samples/NohadraSyriac-Amedia-nohadra-amedia-text.png" alt="" width="400"/>
</p>

Amedia offers the same look and feel as Sapna, but with rounder edges. [View sample text](samples/index-amedia.html)

<p align="center">
  <img src="samples/NohadraSyriac-Amedia.png" alt="" width="3000"/>
</p>

### More to come

## Installation
To install the Nohadra Syriac Font on your system, simply install the desired OTF font files from the `fonts/` directory, or follow the instructions below.

First begin by downloading or cloning this repository, and navigate to the directory containing this project.

### macOS/Linux/Windows Instructions

4. Run the script:
```sh
./install_fonts.sh
```

## Contributing

Contributions to the Nohadra Syriac Font project are welcome. To contribute, feel free to put up a pull request with a detailed description of your change. Note, the Makefile includes a proofing target that should be run before pull requests are posted. Currently, there is no CLI method for export font files. They must be exported by Glyphs.app. Font kerning is also verifies manually currently. Pay close attention to diacritic placement in the samples to note any changes made. The `make` command should be run for all changes as it will export the Glyphs.app fonts, proof them, and create new samples.
