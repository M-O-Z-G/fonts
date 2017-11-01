Powerline fonts
===============

This repository contains pre-patched and adjusted fonts for usage with
the [Powerline](https://github.com/powerline/powerline) statusline plugin.

Why this fork was made?
===============
Unfortunately, there're not too many fonts with Cyrillic support and works with no distortion. Here I have collected some samples of Powerline fonts with Cyrillic support and fine looks. Hope it will be helpful for someone else)

#### **Fira Mono for Powerline**
![Fira Mono for Powerline](https://steemitimages.com/DQmRJj4fTdaZL1JSeEj7jN8hTY82ko3X6YWsV23QbbRmtfh/A1509550472d2c121687-f7ea-4fd9-a022-4db3406a9d35%5B1%5D.png)

<hr>

#### **Anonymice Powerline**
![Anonymice Powerline](https://steemitimages.com/DQmQo4fGN5boGcPbYCXWykobcoBvtCgNccSBjBn2LRgwpXS/9355f80f84f98d43f0fd%5B1%5D.png)
<hr>

#### **DejaVu Sans Mono for Powerline**
![DejaVu Sans Mono for Powerline](https://steemitimages.com/DQmQJuMChJxoL6h8GvV5gRTZJVka1fjBCgV4Ju9LFMzXXeJ/1ab565519914ec57f904%5B1%5D.png)
<hr>

#### **Source Code Pro for Powerline**
![Source Code Pro for Powerline](https://steemitimages.com/DQmZDNWGAs4AS1wz8iWDNGymJ4jUCx4b3i32BSircor3zHx/bf67c884f85cb0f65a2f%5B1%5D.png)

<hr>

#### **Ubuntu Mono derivative Powerlin**
![Ubuntu Mono derivative Powerlin](https://steemitimages.com/DQmRwpqfCGTP3ivufPCFS5SqqUJsqTLH4RhUffPvaK45WFv/f612940ea5b554fb177a%5B1%5D.png)


Installation
------------

Run `./install.sh` to install all Powerline Fonts or see the [documentation](https://powerline.readthedocs.org/en/latest/installation/linux.html#fonts-installation) for details.

Quick installation
------------------

You can copy and paste the commands to your terminal. Comments are fine too.

<pre>
# clone
git clone https://github.com/powerline/fonts.git --depth=1
# install
cd fonts
./install.sh
# clean-up a bit
cd ..
rm -rf fonts
</pre>


Font Families
-------------

|Powerline Font Family                 | Formerly Known As       | Cyrillic + Windows Support | License                           | 
|--------------------------------------|-------------------------|----------------------------|-----------------------------------|
|3270                                  | 3270                    | N/A                        | BSD/CCAS 3.0|
|Anonymice Powerline                   | Anonymous Pro           | Fine Rendering             | SIL Open Font License, Version 1.1|
|Arimo Powerline                       | Arimo                   | N/A                        | Apache License, Version 2.0|
|Cousine Powerline                     | Cousine                 | N/A                        | Apache License, Version 2.0|
|D2Coding for Powerline                | D2Coding                | N/A                        | SIL Open Font License, Version 1.1|
|DejaVu Sans Mono for Powerline        | DejaVu Sans Mono        | Fine Rendering             | DejaVu Fonts License, Version 1.0|
|Droid Sans Mono for Powerline         | Droid Sans Mono         | N/A                        | Apache License, Version 2.0|
|Droid Sans Mono Dotted for Powerline  | Droid Sans Mono Dotted  | N/A                        | Apache License, Version 2.0|
|Droid Sans Mono Slashed for Powerline | Droid Sans Mono Slashed | N/A                        | Apache License, Version 2.0|
|Fira Mono Powerline                   | Fira Mono               | Fine Rendering             | SIL OPEN FONT LICENSE Version 1.1|
|Go Mono for Powerline                 | Go Mono                 | N/A                        | Go's License|
|Hack                                  | Hack                    | N/A                        | SIL OFL, v1.1 + Bitstream License|
|Inconsolata for Powerline             | Inconsolata             | N/A                        | SIL Open Font License, Version 1.0|
|Inconsolata-dz for Powerline          | Inconsolata-dz          | N/A                        | SIL Open Font License, Version 1.0|
|Inconsolata-g for Powerline           | Inconsolata-g           | N/A                        | SIL Open Font License, Version 1.0|
|Input Mono                            | Input Mono              | N/A                        | [Input's license](http://input.font|bureau.com/license)
|Liberation Mono Powerline             | Liberation Mono         | N/A                        | SIL Open Font License, Version 1.1|
|ProFontWindows                        | ProFont for Powerline   | N/A                        | MIT License|
|Meslo for Powerline                   | Meslo                   | N/A                        | Apache License, Version 2.0|
|Source Code Pro for Powerline         | Source Code Pro         | Fine Rendering             | SIL Open Font License, Version 1.1|
|Meslo Dotted for Powerline            | Meslo Dotted            | N/A                        | Apache License, Version 2.0|
|Meslo Slashed for Powerline           | Meslo Dotted            | N/A                        | Apache License, Version 2.0|
|Monofur for Powerline                 | Monofur                 | N/A                        | Freeware|
|Noto Mono for Powerline               | Noto Mono               | N/A                        | SIL Open Font License, Version 1.1|
|Roboto Mono for Powerline             | Roboto Mono             | N/A                        | Apache License, Version 2.0|
|Symbol Neu Powerline                  | Symbol Neu              | N/A                        | Apache License, Version 2.0|
|Terminess Powerline                   | Terminus                | N/A                        | SIL Open Font License, Version 1.1|
|Tinos Powerline                       | Tinos                   | N/A                        | Apache License, Version 2.0|
|Ubuntu Mono derivative Powerline      | Ubuntu Mono             | Fine Rendering             | Ubuntu Font License, Version 1.0|
|Space Mono for Powerline              | Space Mono              | N/A                        | SIL Open Font License, Version 1.1|

iTerm2 users need to set both the Regular font and the Non-ASCII Font in
"iTerm > Preferences > Profiles > Text" to use a patched font (per [this issue](https://github.com/Lokaltog/powerline-fonts/issues/44)).

Fontconfig
---

In some distributions, Terminess Powerline is ignored by default and must be
explicitly allowed. A fontconfig file is provided which enables it. Copy this
file from the fontconfig directory to your home folder under
`~/.config/fontconfig/conf.d` (create it if it doesn't exist) and re-run
`fc-cache -vf`.
