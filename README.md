Official documents of the Open Bioinformatics Foundation
========

Documents maintained in markdown format may use an extension, as listed below.

* `OBF Bylaws.md`: Uses [Pandoc](http://johnmacfarlane.net/pandoc/) markdown extensions. Conversion using the following command:

        $ pandoc -t html -o "OBF Bylaws.html" "OBF Bylaws.md"
  For generating the PDF use this:

        $ pandoc -o "OBF Bylaws.pdf" --latex-engine=$pdflatex "OBF Bylaws.md"
  where `$pdflatex` is `pdflatex` if it is in your path, or the full path to `pdflatex` otherwise.

* `Donation-info-for-SPI.md`: plain markdown