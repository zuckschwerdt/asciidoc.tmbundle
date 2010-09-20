AsciiDoc TextMate bundle
========================

This is a TextMate bundle for AsciiDoc, see [the website](http://www.methods.co.nz/asciidoc/)

It's got some basic commands and snippets working. Accessible by shortcuts and tab expansion.
The language grammar features the very basics only. I.e. some structure and markup higlighting.
Output is available as *preview* (TextMate window), rendered *HTML* and *PDF* (pdflatex required).

Commands and Snippets
---------------------

Commands:

 - Preview (try `Ctrl+Opt+Cmd+P`)
 - Convert Document (try `Ctrl+Shift+H`)
 - Typeset as PDF (try `Cmd+R`)
 - Show Documentation

Snippets:

 - Bold (try `Cmd+B`)
 - Italic (try `Cmd+I`)
 - Quoted (try `Cmd+'`)
 - Superscript (try `Ctrl+Shift+up`)
 - Subscript (try `Ctrl+Shift+down`)
 - Headings (try `Ctrl+0` to `Ctrl+4` or `h1 TAB` to `h4 TAB` for one-liner versions)
 - Table generation (try `|= TAB`)
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

Christian Zuckschwerdt. Complementary shortcut and fixes by Guillaume-Jean Herbiet.

Enjoy.
