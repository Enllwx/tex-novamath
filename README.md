# tex-novamath

"Nova Mathematica" symbola et macrones LaTeX in Latina

"Nova Mathematica" LaTeX symbols and macros in Latin.

## Usage

It might be worthy to read this [tex.stackexchange](https://tex.stackexchange.com/questions/1137/where-do-i-place-my-own-sty-or-cls-files-to-make-them-available-to-all-my-te)
question.

Use
```
kpsewhich -var-value=TEXMFHOME
```
to find the install directory of TeX packages. This directory will be referred
to as `$TEXMFHOME`.

Then, create the directory `$TEXMFHOME/tex/latex/local$ and clone
`tex-novamath` into it.

Then execute
```
texhash $TEXMFHOME
```
to update the available tex packages.
