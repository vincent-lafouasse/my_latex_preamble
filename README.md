# Vincent's special package

## Description


### chemistry/physics

- **mhchem** : an overall useful package for chemists.

Too big for me to know all it can do. I mainly use it to standardize
chemical formulae such as `\ce{CH3CH2OH}` or `\ce{CuSO4.nH2O}`. You can
also represent single, double and triple bonds with `-`, `=` and `#`.

Note that greek letters in `ce` are automatically upright letters.

---

- **siunitx** : provides proper formatting for physical quantities in a consistent
way with readable code.

The commands I use the most are `\SI{number}{unit}`,
`\si{unit}` and `\ang{angle}`. This package is supplemented by `chemstyle`
for non-SI units.

---

- **chemstyle** : provides both `chemstyle` and `chemschemes`.

**chemstyle** : allows for use of non-SI units such as `\cmc`,`\Molar` or `\mmHg`
and provides a command for the standard state symbol (`\standardstate`)
and standard notations for the alkyl chains such as `\tBu` or `\iPr`.

**chemschemes** : useful for numbered and easily referenced
floating schemes with compound numbering.

---

- **upgreek** : allows for upright greek letters.

This comes in useful
when greek letters don't represent quantities, _e.g_ __*pi*__ = 3.14 
should be slanted as it is a number, 
but the pi in **pi**-bond should be upright.

Use `\upalpha` for lowercase upright alpha and `\Upalpha` for the
uppercase variant.

---

#### maths
amsmath
amsfonts
amssymb
amsthm
cancel

#### figures
graphicx
float
caption
subcaption
psfrag


#### formatting
fullpage
titling
titlesec
fancyhdr


#### encoding
inputenc
fontenc
babel


#### misc
appendix
nameref
hyperref
csquotes
lipsum


## Raw list

##### encoding
inputenc
fontenc
babel

##### maths
amsmath
amsfonts
amssymb
amsthm
cancel

##### figures
graphicx
float
caption
subcaption
psfrag

##### chemistry/physics
mhchem
siunitx
upgreek
chemstyle

##### formatting
fullpage
titling
titlesec
fancyhdr

##### misc
appendix
nameref
hyperref
csquotes
lipsum


## Roadmap

[x] short inline comments

[ ] succint description of each package (why I need them)

[ ] a cheat sheet of the commands i use the most

[ ] test `chemmacros` as it seems quite powerful and easy to use
