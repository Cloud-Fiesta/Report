# Content of the repository
Repository that will contain the final reports documenting the whole activity

We gotta two main possibilities, some sort of Markdown language like the one in the README.md file, or a generic writer
like MS Word or LibreOffice Writer.

Generaly I think that md or latex will be better, they way more integrated w/ git, so it's easyer to work togheder on it.
Also they provide a decent swag to the project, it will look way more offical and skilled.

# Contrib guidelines
To contribute to the report there are some general style guidelines that are usefull to ensure that we gotta a
consistent style throughout the entire document.

## Maximum line lenght
I've initially set a maximum linelenght of 120 char, that can be exceeded only if a particular syntax element require
more space, as at `line 53`.
Using this standard we can manage the `overfull hbox` warning, that can lead to some misalignment in the final PDF in the
final PDF.
To ensure that, I generally put a gray vertical line at char 120 in my editor, so I can visually see how many words can
still be written in a line.

## Emph and textit/textbf
Generally, the use of \emph instead of \textit and \textbf is advised, that's just because is way easier to let LaTeX
decide what type of enmphasis use depending on the context, force a particular tipe of emphasis is still permitted.

\newpage
## Indentation

According to the standard LaTeX syntax, every section (chapters, section, subsection etc) mean an indentation level,
every level is a 4-spaces long tab (^I).

As an example, that's an extract from the report:

	\chapter{Introduzione}
	\author{Riccardo Oglietti}
		\section{Il Progetto}
			Some text
			\subsection{Le Persone}
				Some other text

## Numbers

According to best practices of the Italian language, when using numbers, is mandatory the use of the written form,
instead of the "mathematical" one. As an exemple, "_Ci son 2 coccodrilli e un Harambe_" isn't correct, it must be
written as "_Ci son_ **due** _coccodrilli e un Harambe_".
