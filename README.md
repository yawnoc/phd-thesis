# phd-thesis

Conway's Ph.D. Thesis, in LaTeX.


## Copyright 2021 Conway

Permission is granted to distribute unmodified copies of this repository.

Permission is NOT granted to make modifications or create derivative works.

The file [`conway.bst`] alone
is licensed under the [LaTeX Project Public License v1.3c].

For the code used to produce the figures, see [yawnoc/phd-code].

[`conway.bst`]: conway.bst
[LaTeX Project Public License v1.3c]: https://spdx.org/licenses/LPPL-1.3c.html
[yawnoc/phd-code]: https://github.com/yawnoc/phd-code


## Compile

Permission is granted to compile the thesis from source,
provided that the resulting output is not distributed or published.

This software comes with ABSOLUTELY NO WARRANTY etc. etc.

Run `./compile` to compile from scratch.
This calls `./clean` (which removes ignored files)
and `./version` (which generates the Git version information)
before actually compiling.

If using Windows, all three scripts should work in Git BASH.

Image files for wet signature and date are loaded
from the external directory `../phd-thesis-signatures`.
If an image file does not exist, it will be omitted.


## Reproducibility

Assuming that no images are loaded from `../phd-thesis-signatures`,
the output `thesis.pdf` can be reproduced exactly, run after run,
on a *given* TeX installation.

Unfortunately, different installations will produce different PDF output,
as demonstrated by the experiment at [yawnoc/reproducible-latex].

Nevertheless, for the following groups of TeX Live installations,
identical output is observed
between listed installations belonging to the same group:

- <b>Group 1: TeX Live 2019 Debian</b>
  * Debian 10 (aarch64) texlive-full 2018.20190227-2
  * Debian 10 (x86_64) texlive-full 2018.20190227-2

- <b>Group 2: TeX Live 2020 Not Debian</b>
  * macOS 10.15 (x86_64) TeX Live 2020
  * Termux 0.112 (armv7l) texlive-full 20200406-4
  * Windows 10 (x86_64) TeX Live 2020/W32TeX

Moreover, [DiffPDF 2.1.3-1.2] confirms that
the output of Group 1 is *visually* identical to the output of Group 2.

[yawnoc/reproducible-latex]: https://github.com/yawnoc/reproducible-latex
[DiffPDF 2.1.3-1.2]: https://packages.debian.org/buster/diffpdf


<!--
$ sha256sum CONTINGENCY.txt 
921830e179739e5fcb066affb8c793272984ae541187b9b70491542bff5f82e3  CONTINGENCY.txt
-->
