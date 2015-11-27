<!--
 ! To produce html from markdown:
 !     markdown -o README.html README.md
 ! Tested with markdown: discount 2.1.6 DL=DISCOUNT.
 ! See:  http://www.pell.portland.or.us/~orc/Code/discount/
-->

# Project:  ringojs-docs

This project is to convert the RingoJS API documentation from HTML to PDF format, so you can view the documents in a more convenient form, especially on mobile devices.

The output PDF's have internal links, as in the html docs.  However, not all PDF viewers are capable of activating these links.

I have tested the docs using the free mobile version of Adobe Acrobat Reader, under IOS 8.x, with success.

# How to build this project:

        cado -u mkdoc.cg

Output goes to the `dist` directory, e.g.:

        dist/ringojs_api_0.11.pdf (270 pages)
        dist/stick_api_0.4.pdf (54 pages)

# Prerequisites:

  * Install `wkhtmltopdf` command line tools from:  <http://wkhtmltopdf.org>
  * Install `cado` from:  <http://sourceforge.net/projects/cado/files>

# See Also:
  * <http://wkhtmltopdf.org>
  * <https://github.com/russt/cado>
  * <http://ringojs.org>
  * <http://ringojs.org/api/0.11/index.html>
  * <http://ringojs.org/api/stick/index.html>
  * <https://github.com/ringo/ringojs>
  * <https://groups.google.com/forum/#!forum/ringojs>
