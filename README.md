# Switchy HDMI

[![Build Status](https://travis-ci.com/nbeguier/Switchy_HDMI.svg?branch=master)](https://travis-ci.com/nbeguier/Switchy_HDMI) [![License](https://img.shields.io/github/license/nbeguier/Switchy_HDMI?color=blue)](https://github.com/nbeguier/Switchy_HDMI/blob/master/LICENSE)

Draft of a script that switch video and audio to TV.

## Usage

```bash
$ ./switchy_hdmi 
Usage: switchy_hdmi [-hvl] [-a OPTION] [-o output_card]

switchy_hdmi -a 0            # Désactive le HDMI.
switchy_hdmi -a 1            # Active seulement le HDMI.
switchy_hdmi -a 2            # Laisse le PC en master.
switchy_hdmi -a 3            # Image identique
switchy_hdmi -a 1 -o 'HDMI2' # Active seulement le HDMI, et force l'interface de sortie.
switchy_hdmi -l              # Affiche les informations des cartes.
```

# License
Licensed under the [Apache License](https://github.com/nbeguier/Switchy_HDMI/blob/master/LICENSE), Version 2.0 (the "License").

# Copyright
Copyright 2015-2021 Nicolas Béguier; ([nbeguier](https://beguier.eu/nicolas/) - nicolas_beguier[at]hotmail[dot]com)
