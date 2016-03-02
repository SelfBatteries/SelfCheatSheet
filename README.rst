Self cheatsheet
===============
Informations about the `Self programming language <http://selflanguage.org>`_ (selflang) in compact form.

About
-----

I've decided to create this Cheat sheet to finally force myself into learning Self. There may and will be a lot of bugs and language typos. If you find any, please send request.

You may also add new sections, but keep in mind, that this is not a tutorial, nor the manual. Compactness is what counts. If you add a new page, keep in mind, that you should fill that page.

Building
--------

On the fresh Ubuntu installation, you will need following packages::

    latex-xcolor texlive-common unzip texlive texlive-latex-base texlive-latex-extra texlive-binaries texlive-latex-recommended pgf cm-super texlive-generic-extra

You may install them using the ``sudo apt-get install <package-list>`` command.

This will install tex and the ``pdflatex`` command. To build the cheatsheet, use::

    pdflatex self_cheatsheet.tex
