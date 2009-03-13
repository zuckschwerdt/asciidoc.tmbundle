AsciiDoc TextMate bundle
========================

This is a TextMate bundle for AsciiDoc, see [the website](http://www.methods.co.nz/asciidoc/)

It's got some basic commands and snippets working. Accessible by shortcuts and tab expansion.
The language grammar features the very basics only. I.e. some structure and markup higlighting.
Output is available as *preview* (TextMate window), rendered *HTML* and *PDF* (pdflatex required).

Commands and Snippets
---------------------

Commands:

 - Preview
 - Convert Document
 - Typeset as PDF
 - Show Documentation

Snippets:

 - Bold
 - Italic
 - Quoted
 - Superscript
 - Subscript
 - Headings (try `Ctrl-Cmd-T h1`)
 - Tab expansion for blocks (try `== TAB`)

Installation
------------

To install via Git:

    cd ~/"Library/Application Support/TextMate/Bundles/"
    git clone git://github.com/zuckschwerdt/asciidoc.tmbundle.git "AsciiDoc.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

Also be sure to have asciidoc itself and maybe LaTeX around.

Source can be viewed or forked via [GitHub](http://github.com/zuckschwerdt/asciidoc.tmbundle/tree/master).

Author
------

Christian Zuckschwerdt

Enjoy.
