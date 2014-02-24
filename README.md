# unikn-Title

This title.tex creates a title page according to the requirements of the Universität Konstanz as stated on the [page of the Zentrales Prüfungsamt][1]. This title page was created 2014, so if you find, that the format has changed, feel free to correct it and send a patch.

The Matrikel-Nr was added to the universities version, as some departements/chairs want this. If you don't need this, just leave it empty.

## Usage

1. Either clone the whole repository or download the ``title.tex`` and the ``unisignet.pdf``.
2. At the place, where you want to put your title page, probably directly after ``\begin{document}``, insert ``\input{title.tex}`` (or similar, depending on your folder structure).
3. Change the commands in the upper part of ``title.tex`` to represent your information.

## The Signet

The ``unisignet.pdf`` is a copyrighted symbol of the Universität Konstanz. Usage can only be allowed by the Universität Konstanz. Usage has been allowed for the title page of a thesis done at the Universität of Konstanz in a way, that the symbol is attributed to the institution and not the author. The title page in the form of ``title.tex`` is in accordance with this usage.

[1]: http://www.studium.uni-konstanz.de/pruefungen/wichtige-mitteilungen-des-zentralen-pruefungsamtes/
