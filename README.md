# limits-17
ACM limits 2017 submission

add this to your .spacemacs

```elisp
(add-to-list 'org-latex-classes
             '("acmart"
               "\\documentclass[sigconf]{acmart}"
               ("\\section{%s}" . "\\section*{%s}")
               ("\\subsection{%s}" . "\\subsection*{%s}")
               ("\\subsubsection{%s}" . "\\subsubsection*{%s}")
               ("\\paragraph{%s}" . "\\paragraph*{%s}")
               ("\\subparagraph{%s}" . "\\subparagraph*{%s}")))
```
