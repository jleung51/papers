# Papers Authored by Jeffrey Leung

A collection of papers authored by me.

These papers are typeset in LaTeX. They were generally written for coursework.

## Directory

<a href="https://github.com/jleung51/papers/blob/master/ethical-considerations-of-human-enhancement/ethical-considerations-of-human-enhancement.pdf">Leung, J. (2018). Building the Tower of Babel: Ethical Considerations of Human Enhancement. _CMPT 320: Social Implications of a Computerized Society_.</a>

<a href="https://github.com/jleung51/papers/blob/master/research-proposal-microservices-for-healthcare/research-proposal-microservices-for-healthcare.pdf">Leung, J. (2017). Research Proposal: Utilizing Microservices for Healthcare Systems. _CMPT 376W: Technical Writing and Group Dynamics_.</a>

<a href="https://github.com/jleung51/papers/blob/master/capabilities-of-microelectrodes/capabilities-of-microelectrodes.pdf">Leung, J. (2015). The Capabilities of Microelectrodes. _IAT 267: Introduction to Technological Systems_.</a>

## Build

Required packages: `texlive texlive-bibtex-extra texlive-publishers`

To build the initial file, run:
```
pdflatex $FILENAME
```

Then build the bibliography (`.bib` file):
```
bibtex $FILENAME
```

Then build the file again, twice:
```
pdflatex $FILENAME
pdflatex $FILENAME
```

A `build` script is provided for convenience.