Moje poznámku k "dračáku" co občas hrajeme
==========================================

Development
-----------

Dokumentace je v adresáři 

Nainstaluju (na Fedora Linux) si nástroj na generování PDF (Sphinx):

    dnf install python3-sphinx python3-sphinx-latex   # možná i python3-sphinxcontrib-svg2pdfconverter-common, uvidíme

Sestavím PDF:

    make -C docs/ latexpdf

Výsledek je tady:

    docs/build/latex/ndrak.pdf
