LatexModules
============

Module for Latex using the memoir package.


Example
-------
Your tree looks like this:

+ Document/
	- Main.tex
	- MemoirSetup.tex
	- Preamble.tex

Your Main.tex would look like this:

```latex
\documentclass[a4, english]{memoir}
\input{Preamble}

\begin{document}
\chapther{The memoir setup file}
This is the memoir setup file.
\begin{itemize}
\item It's simple
\item It's clean
\item It's ready to use.
\end{enumerate}

And now -- dummy text:

\lipsum[1]
\end{document}
```

Then your preamble would be:

```latex
\input{MemoirSetup} 
...
\title{Memoir setup}
```

That is all you need.
