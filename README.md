<p align="center">
 <img src="https://github.com/iamtheblackunicorn/language-chromos/raw/master/assets/banner.png"/>
</p>

# CHROMOS GRAMMAR :rainbow: :scroll:

*A grammar for the Chromos language for Atom.* :rainbow: :scroll:

## About :books:

This repository contains a grammar for the Chromos language for the Atom editor. This means that when you write Chromos code, this theme will make syntax-higlighting possible inside the Atom editor. You can find out more about the Atom editor [here](https://atom.io) and the Chromos language [here](https://github.com/iamtheblackunicorn/Chromos).

## Features

- simple, discernible colors
- easy to use
- easy to install

## Installation :inbox_tray:

- 1.) Make sure that Atom is installed.
- 2.) Download this repository.
- 3.) Move the downloaded repository to your system's `.atom` directory.
- 4.) If Atom is open, close it. If not, start it and write some *Chromos* code.
- 5.) Enjoy!

## Example :computer:

```text
// hello.chr

prog start

  // Prints out "HELLO WORLD".
  
  message start => "01"
    000008
    000005
    00000C
    00000C
    00000F
  message end => "01"
  
  message start => "02"
    000017
    00000F
    000012
    00000C
    000004
  message end => "02"
  
prog end
```

## Changelog :black_nib:

### Version 0.1.0: Black Bird

- upload to GitHub
- polished entity names

## Note :scroll:

- *Chromos Grammar :rainbow: :scroll:* by Alexander Abraham, *"The Black Unicorn"*
- Licensed under the MIT license.
