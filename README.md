# A LaTeX Package for Jim Wood's Classes

*Record Scratch.* So, you've found yourself taking one of Jim's classes. Here's 
a LaTeX file to make formatting your papers a piece of cake.

## Usage

1. Download (or clone) this repository and unzip the folder. If you're writing 
your paper on Overleaf, just upload the files to your project directory.
2. Download the bibliography files `unified.bbx` and `unified.cbx` from the
[biblatex-sp-unified](https://github.com/semprag/biblatex-sp-unified) repository
and place them in your project directory.
3. If you're using XeLaTeX or LuaLaTeX, download an IPA-complete Unicode font.
For this class, I recommend [Doulos SIL](biblatex-sp-unified).
4. Pick an example package. I recommend `expex`, and have included it in the
template file, but you could use `gb4e` or something else.
5. Pick a tree package. I recommend `forest`, but you could also use `qtree` or
`tikz-qtree`.
6. Put your bibliography inside the TeX file, between `\begin{filecontents}`
and `\end{filecontents}`; this ensures your bib file is never separated from
your TeX file.
7. Get to writing!