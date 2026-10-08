# Lecture-notes LaTeX style

`myMath-notes.sty` is the supplied personal mathematics lecture-notes package,
version 1.2, dated 2026/09/01. Its contents are unchanged. The distributed
filename matches its `\ProvidesPackage{myMath-notes}` declaration; use that
capitalization on case-sensitive systems.

The repository's [rights notice](../LICENSE) applies to the original style
material. Referenced third-party LaTeX packages retain their own licenses and
are not bundled here.

## Use (after permission)

Copy `myMath-notes.sty` beside your main `.tex` file, or into a location searched
by your TeX installation. A minimal preamble is:

```tex
\documentclass[11pt]{article}
\usepackage{myMath-notes}
```

For figures and tables numbered within subsections, load it instead with:

```tex
\usepackage[subsectionfloats]{myMath-notes}
```

By default, figures and tables are numbered within sections; equations are
section-based and algorithms are subsection-based. The package sets letter-paper
geometry, uses `./figures/` as its graphics directory, and configures hyperlinks,
author-year citations, and R listings. It provides mathematical shortcuts,
theorem environments, navigation commands, and pedagogical display boxes.

It loads `hyperref`, `natbib`, `geometry`, and the other dependencies below.
Avoid loading them again with conflicting options. Customize links with
`\hypersetup{...}` after loading the style. Algorithms use `algorithm` with
`algorithmic` from `algpseudocode`. PGFPlots compatibility is set to 1.18.

The package is designed for English notes. It redefines some standard commands,
including `\P` and `\S`; use `\textparagraph` and `\textsection` for those text
symbols. Review compatibility before combining it with another course style.

## Dependencies

Use a TeX installation providing the following packages, which are extracted
from the style's `\RequirePackage` declarations:

`latexsym`, `amsmath`, `amssymb`, `amsthm`, `mathrsfs`, `amsfonts`, `mathtools`, `mathalfa`, `dsfont`, `bm`, `bbm`, `wasysym`, `marvosym`, `xcolor`, `graphicx`, `framed`, `csquotes`, `xspace`, `xparse`, `cancel`, `listings`, `fancyvrb`, `algorithm`, `algpseudocode`, `geometry`, `needspace`, `etoc`, `chngcntr`, `enumitem`, `array`, `float`, `booktabs`, `multirow`, `tabularx`, `morefloats`, `adjustbox`, `pdflscape`, `pifont`, `natbib`, `tikz`, `pgfplots`, `tcolorbox`, `hyperref`, `tablefootnote`.

Missing-package errors must be resolved in the TeX environment. Copying this
file or installing the Codex skill does not install those dependencies.

## Using it with the skill

The skill and this style are separate components. Installing only the skill
folder does not install the style. Place the style in your course project and
identify it in your request, for example:

> Use the write-lecture-notes skill and the myMath-notes.sty file in this project.
> Preserve the style's environments and numbering conventions.

## Maintenance and verification

Keep the repository copy as the source for public releases. Document changes in
[CHANGELOG.md](../CHANGELOG.md), and update the package version/date when its
implementation changes. Keep personal installations synchronized deliberately.

This initial import was checked for package naming, declared dependencies, and
personal filesystem paths, and verified byte-for-byte against the supplied
file. No compilation or visual validation was performed for this import.
