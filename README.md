# periodic-table
slang code to produce a periodic table as .png or .pdf

This code snipped uses the slang xfig module (www.jedsoft.org/slang/) to render a periodic table.

Usage: 
       psegen filename.pdf
       psegen filename.png
       
       if no filename is given, the output will be saved in 'pte.pdf'

Option:
      -g black and white instead of colors

WARNING: The code runs quite a while and produces a lot of output since the text is processed by latex