PDF Merge
    by Tim Pease
    http://github.com/TwP/pdf_merge

== DESCRIPTION:

Merge pages from two PDF files into a single PDF file.

== SYNOPSIS:

If you have a single-sided scanner with a sheet feeder, you can imagine
scanning in a set of double sided pages and producing a PDF file. This
file will contain all the odd numbered pages (1,3,5...). Flipping the
stack of papers over and scanning the reverse sides will produce a second
PDF file containing the even numbered pages in reverse order (...6,4,2).
This script will merge these two files and generate a single PDF file with
the pages interleaved in the correct order.

== REQUIREMENTS:

This Python script only works on Mac OS X. It relies on the Quartz
CoreGraphics framework for processing the PDF files. Any version of OS X that
has the CoreGraphics framework should suffice for using this script.

== INSTALL:

Place the "merge.py" script somewhere in your path.

== LICENSE:

(The MIT License)

Copyright (c) 2009

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
