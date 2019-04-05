# style-eit-latex
LaTeX style for the Department of Electrical and Computer Engineering, Technische Universität Kaiserslautern (TUK)


## Build
There is nothing to build right here in this repository. It is included as a submodule into the document templates where required.
However, if you really want to use it directly in your own documents, you can do so by including:
```
% for English documents (standard)
\usepackage{style-eit-latex/EIT}
```
or
```
% use [de] option for German documents
\usepackage[de]{style-eit-latex/EIT}
```

Additional option: [pt] for setting the standard font to PT Sans (sans serif)


## Known Dependencies
* texlive-science
* texlive-fonts-extra


## Contributors:
* Christian De Schryver <schryver@eit.uni-kl.de>
* Matthias Jung <jungma@eit.uni-kl.de>
