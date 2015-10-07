# KTH Beamer Theme

This is an UNOFFICIAL beamer theme for KTH, The Royal Institute of Technology. It uses the eps print logo [zip](https://intra.kth.se/polopoly_fs/1.486659!/Logotyp%20f%C3%B6r%20trycksak.zip), which is replicated in [this](kth-logo) repo for convenient installation.

# Install & Usage

From the terminal run:

```
  cd ~/.texmf/tex/latex && git clone https://github.com/edwtjo/kthBeamerTheme
```

And in your beamer tex file use:

```
\documentclass[newPxFont,kthFooter]{beamer}
\usetheme{kth}
...
```

# Disclaimer

This is a still early fork and rebrand of the excellent sthlm beamer theme by
Mark Hendry Olson. This forked theme's color palette is still not aligned to the
KTH palette. It is distributed under the same license, the GPL-3.
