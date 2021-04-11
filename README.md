# phd-thesis

Conway's Ph.D. Thesis, in LaTeX.

For the code used to produce the figures, see [phd-code].

[phd-code]: https://github.com/yawnoc/phd-code


## Compile

**WARNING.**
Images of wet signatures are loaded
from the external directory `../phd-thesis-signatures`.
Always check that these image files are not malicious etc. before compiling.
If a signature image file does not exist, it will be omitted.

Run `./compile` to compile from scratch.
This calls `./clean` (which removes ignored files)
and `./version` (which generates the Git version information)
before actually compiling.

If using Windows, all three scripts should work in Git BASH.


<!--
$ sha256sum CONTINGENCY.txt 
921830e179739e5fcb066affb8c793272984ae541187b9b70491542bff5f82e3  CONTINGENCY.txt
-->
