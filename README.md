# phd-thesis

Conway's Ph.D. Thesis, in LaTeX.

For the code used to produce the figures, see [yawnoc/phd-code].

[yawnoc/phd-code]: https://github.com/yawnoc/phd-code


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


## Reproducibility

The output `thesis.pdf` can be reproduced exactly, run after run,
on a *given* TeX installation.

Unfortunately, different installations will produce different PDF output,
as demonstrated by the experiment at [yawnoc/reproducible-latex].
Nevertheless, for the following groups of TeX Live installations,
identical output *should* be observed
between listed installations belonging to the same group:

- <b>Group 1: TeX Live 2019 Debian</b>
  * Debian 10 (aarch64) texlive-full 2018.20190227-2
  * Debian 10 (x86_64) texlive-full 2018.20190227-2

- <b>Group 2: TeX Live 2020 Debian</b>
  * Debian 11 (x86_64) texlive-full 2020.20210202-3

- <b>Group 3: TeX Live 2020 Not Debian</b>
  * macOS 10.15 (x86_64) TeX Live 2020
  * Termux 0.112 (armv7l) texlive-full 20200406-4
  * Windows 10 (x86_64) TeX Live 2020/W32TeX

[yawnoc/reproducible-latex]: https://github.com/yawnoc/reproducible-latex


<!--
$ sha256sum CONTINGENCY.txt 
921830e179739e5fcb066affb8c793272984ae541187b9b70491542bff5f82e3  CONTINGENCY.txt
-->
