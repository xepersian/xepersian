---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: enhancement
assignees: vafa-k
---

> The index to Digital Typography lists eleven pages where the importance of stability is stressed, and I urge all maintainers of TeX and METAFONT to read them again every few years. Any object of nontrivial complexity is non-optimum, in the sense that it can be improved in some way (while still remaining non-optimum); therefore there’s always a reason to change anything that isn’t trivial. But one of TeX’s principal advantages is the fact that it does not change—except for serious flaws whose correction is unlikely to affect more than a very tiny number of archival documents.
> 
> **— DONALD E. KNUTH, “The TeX tuneup of 2008,” TUGboat 29:2 (2008), 233–238**

<!---
!! Please fill out all sections !!
-->

## Brief outline of the feature request


## Check/indicate
- [ ] Relevant to the `bidi` package
- [ ] [The `bidi` package issue tracker](https://github.com/xepersian/bidi/issues) has been searched for similar issues?
- [ ] [The `xepersian` package issue tracker](https://github.com/xepersian/xepersian/issues) has been searched for similar issues?
- [ ] Links to <tex.stackexchange.com> discussion if appropriate
- [ ] Links to <qa.parsilatex.com> discussion if appropriate

## Minimal example

```tex
% !TEX TS-program = XeLaTeX
% !TEX encoding = UTF-8 Unicode


\documentclass{article}            % or some other class

  % Any packages other than the xepersian package must be loaded here

  % The xepersian package must be loaded as the last package
\usepackage[%
    % Any xepersian package option goes here
]{xepersian}

\settextfont{<fontname>}

  % Any preamble code goes here
  
\begin{document}

  % Demonstration of feature request here
  
\end{document}
```

## Expected behavior
