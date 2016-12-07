# Logo der HTW Dresden und Adaption des StuRa der HTW Dresden

Das Logo der *HTW Dresden* zur weiteren Verwendung in Publikationen an der Hochschule.
Zur vereinfachten Verwendung innerhlab der Teilkörperschaft, die der StuRa bezogen auf die Hochschule darstellt, auch dessen Adaption des Logos analog zu dem der Hochschule.

## Konvertierung zu anderen Dateitypen

Für die weitere Verwendung kann es notwendig sein, ein Bitmap-Format oder eine [PDF](https://en.wikipedia.org/w/index.php?title=Portable_Document_Format&oldid=716063782) zu generieren. Dies kann leicht mit Freier Software bewerkstelligt werden.

Für mehr Informationen s.a. für die Konvertierung der Datei-Formate
* tex: [LaTeX-Kurs](http://wwwtcs.inf.tu-dresden.de/~borch/lehre/2015-latex/)
* svg: [Export Command Line Options](http://tavmjong.free.fr/INKSCAPE/MANUAL/html/CommandLine-Export.html)

Die folgenden Beispiele wurden auf *Debian GNU/Linux* getestet

### Bsp. TeX zu PDF

Innerhalb von LaTeX verwenden sich PDF-Dateien leicht mit [\includegraphics](http://golatex.de/wiki/index.php?title=\includegraphics).
Alternativ ist eine auf [TikZ](http://tikz.de/) basierende Umsetzung.

```bash
pdflatex htw-logo.demo.tex
pdflatex stura-logo.demo.tex
```

Oder die `htw-logo.inc.tex` wie in `htw-logo.demo.tex` demonstriert in das eigene TeX-Dokument einbinden und das Logo an entsprechender Stelle plazieren.

### Bsp. SVG zu PDF

```bash
inkscape -z -T -A htw-logo.pdf htw-logo.svg
```

### Bsp. SVG zu PNG

Eine Bitmap-Grafik ([PNG](https://en.wikipedia.org/w/index.php?title=Portable_Network_Graphics&oldid=716163563), kann die Transparenz des Hintergrundes beibehalten), hier mit einer Breite von 512 Pixel.

```bash
inkscape -z -e htw-logo.png -w 512 htw-logo.svg
```

## HTW Farben

Quelle: [Corporate Design der HTW Dresden](https://www.htw-dresden.de/intern/marketing/corporate-design.html)

> Schwarz 

Also gemeint wird RGB(0,0,0) bzw. CMYK(0,0,0,100) sein.

> Orange CMYK  0/45/100/0 RGB 249/155/28
> 
> Blau CMYK 90/50/0/0
>
> Grau 60% Schwarz

Blau und Grau werden u.a. auf der Website verwendet. Für das Logo eher uninteressant und hier nur der Vollständigkeit halber.
