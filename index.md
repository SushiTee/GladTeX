GladTeX
=======

About
-----

GladTeX is a preprocessor that enables the use of LaTeX maths within HTML
files. The maths, embedded in `<EQ>...</EQ>` tags, as if within `\(..\)` in LaTeX (or `$...$` in TeX),
is fed through latex and replaced by images.

Additionally all images get an alt-tag for alternative texts that contains the
LaTeX-equivalent of the image. This is handy for text-mode browsers or blind
people.

GladTeX also supports caching of formulas in order to enable incremental
document editing or simply to share formulas across web pages.

GladTeX can be used with [Pandoc](http://pandoc.org) in order to convert
MarkDown to HTML with LaTeX formulas.

It also contains a library GleeTeX to custom tailor the generation and
conversion process to your needs and to embedd it into your (web) application.

Source Code
-----------

The source code can be obtained using git:

    $ git clone https://github.com/humenda/gladtex.git

Documentation
-------------

You can obtain documentation on the command line by executing `gladtex -h`.
Furthermore there's a man page available with `man gladtex`.

The documentation can be viewed [online](manpage.html) as well. It contains the
program usage, as well as the description of the [file
format](manpage.html#file-format) and
[examples](manpage.html#examples).



Contact
-------

Please feel free to send patches, comments, feature requests or even simply
thanks to `shumenda //at\\ gmx __dot__ de`.


&copy; Copyright 1999-2010 Martin Gulbrandsen, 2013-2015 Sebastian Humenda
