# LaTeX-Template

A LaTeX template for keeping notes or journals.

Look at [main.pdf](main.pdf) to see the state of the current build.

## Getting Started

If you are new to LaTeX, use [Overleaf](https://www.overleaf.com/). You can jump into editing and rendering LaTeX files without setup and your changes are saved automatically. 

You can also download a TeX distribution such as:
* https://miktex.org/
* https://www.tug.org/texlive/

Either of those distributions will come with the `TeXworks` LaTeX editor.

Open [main.tex](main.tex) in your editor of choice. Make sure [main.tex](main.tex) stays in the same folder as the [Images](Images), [Preamble](Preamble), and [Sections](Sections) folders, otherwise it can't find them.

## Explanation of each file

[main.tex](main.tex):
* Sets the [document class](https://en.wikibooks.org/wiki/LaTeX/Document_Structure#Document_classes) to `article`, font size to 12pt, and paper size to letter, i.e. 8.5" x 11".
* Begins and ends the document.

[Preamble/custom_commands.tex](Preamble/custom_commands.tex):
* Custom commands, usually to establish shorthands.

[Preamble/custom_settings.tex](Preamble/custom_settings.tex):
* Custom settings, e.g. whether or not to number sections.

[Preamble/environments.tex](Preamble/environments.tex):
* Custom environments of the [ntheorem](https://ctan.org/pkg/ntheorem?lang=en) package.

[Preamble/header_footer.tex](Preamble/header_footer.tex):
* Header and footer settings for the [fancyhdr](https://ctan.org/pkg/fancyhdr?lang=en) package.

[Preamble/packages.tex](Preamble/packages.tex): 
* [geometry](https://ctan.org/pkg/geometry): Used to set the margin size.
* [microtype](https://ctan.org/pkg/microtype): Automatically provides a variety of small adjustments to make documents look better.
* [graphicx](https://ctan.org/pkg/graphicx): Used for rendering images from the [Images](Images) folder.
* [mathtools](https://ctan.org/pkg/mathtools): An extension of [amsmath](https://ctan.org/pkg/amsmath), used for typesetting mathematical notation.  
* [amssymb](https://ctan.org/pkg/amsfonts): Provides a variety of mathematical symbols.
* [ntheorem](https://ctan.org/pkg/ntheorem): Used to define environments of particular formatting for particular needs, e.g. theorems, definitions, and remarks.
* [framed](https://ctan.org/pkg/framed): Used by [ntheorem](https://ctan.org/pkg/ntheorem) to draw frames around environments.
* [fancyhdr](https://ctan.org/pkg/fancyhdr): Used to render headers and footers.
* [enumitem](https://ctan.org/pkg/enumitem): Used to typeset lists.
* [multicol](https://ctan.org/pkg/multicol): Used to render text in more than one column.
* [imakeidx](https://ctan.org/pkg/imakeidx): Used to render the index.
* [xcolor](https://ctan.org/pkg/xcolor): Provides color options.
* [tikz](https://www.ctan.org/pkg/pgf): Used for creating graphics.
* [wrapfig](https://www.ctan.org/pkg/wrapfig): Used for wrapping text around graphics.
* [hyperref](https://www.ctan.org/pkg/hyperref): Used to insert hyperlinks in text.
* [parskip](https://www.ctan.org/pkg/parskip): Used to improve paragraph rendering.
* [lipsum](https://www.ctan.org/pkg/lipsum): Used to render lorem-ipsum text, mainly for testing purposes.

[Sections/toc.tex](Sections/toc.tex):
* Renders the table of contents.

[Sections/Notes.tex](Sections/Notes.tex):
* This is where you write your document. 
