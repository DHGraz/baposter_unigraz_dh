# A template for UniGraz-DH posters

This template is based on the `baposter` class written by Brian Amberg and now maintained by Pieter van Oostrum:

## Philosophy

The `baposter` class is a self-contained LaTeX class for presentation slides:
+ It is almost pure TeX/LaTeX, i.e. largely self-contained, with no need for sophisticated packages or theme stylesheets (I'm looking at you, `beamer`)
+ The layout relies on a grid---it can be made visible in the design phase---, on which `box` elements are placed. The layout scheme is flat, with no hierarchical relationship between blocks. Positioning use either row/col coordinates or relative locations between boxes.
+ The template is easy to customize, with a sufficient range of options for the background, the box shapes etc. 
+ Use the LaTeX PDF engine of your choice: `pdflatex`, `lualatex`, ...

$\rightarrow$ a good choice when transitioning from MS or Google software.

## How to use

Linux shell:

```
# with the baposter.cls file in the same directory
$ pdflatex poster
```

Overleaf:

1. Download this repo as a ZIP file
2. Upload to your Overleaf project


![Poster example](poster_example_sm.png)

## Credits

Licence GPL
(c) 2007-2011 Brian Amberg and Reinhold Kainhofer
(c) 2022 Pieter van Oostrum

The original source can be found at:
![http://www.brian-amberg.de/uni/poster/](http://www.brian-amberg.de/uni/poster/)

Download the more recent class file from 
![https://github.com/pietvo/baposter](https://github.com/pietvo/baposter)

