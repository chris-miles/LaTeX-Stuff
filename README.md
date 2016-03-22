# LaTeX-Stuff
various tidbits of possibly useful LaTeX code


## gif-example
provides a minimal example (`gif_latex.tex`) utilizing the `animate` package to animate GIFs in a LaTeX document (beamer presentation) 

the file `generate_gif_plot.py` also provides an example of how to generate animations using `matplotlib` 


## hw-template
a package providing the formatting for a template of homework submissions. to use, call:

```latex
\usepackage{homework}
```

it can also be called with the option sansfont to switch the font to something a little more aesthetically pleasing:

```latex
\usepackage[sansfont]{homework}
```

both provide the environment to write problems in, using the format

```latex
\prob{title of the problem goes here}{statement of the problem goes here}
```