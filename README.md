# HTW-Logo

Das Logo der *HTW Dresden* zur weiteren Verwendung in Publikationen an der Hochschule.

## Konvertierung zu anderen Dateitypen

Für die weitere Verwendung kann es notwendig sein, ein Bitmap-Format oder eine PDF zu generieren. Dies kann leicht mit Freier Software bewerkstelligt werden.

Für mehr Informationen s.a. für die Konvertierung der Datei-Formate
* tex: [LaTeX-Kurs](http://wwwtcs.inf.tu-dresden.de/~borch/lehre/2015-latex/)
* svg: [Export Command Line Options](http://tavmjong.free.fr/INKSCAPE/MANUAL/html/CommandLine-Export.html)

Die folgenden Beispiele wurden auf *Debian GNU/Linux* getestet

### Bsp. TEX zu PDF

Innerhalb von LaTeX verwenden sich PDF-Dateien leicht mit [\includegraphics](http://golatex.de/wiki/index.php?title=\includegraphics):

```bash
pdf-latex htw-logo.tex
```

### Bsp. SVG zu PDF

```bash
inkscape -z -T -A htw-logo.pdf htw-logo.svg
```

### Bsp. SVG zu PNG

Eine Bitmap-Grafik (PNG, kann die Transparenz des Hintergrundes beibehalten), hier mit einer Breite von 512 Pixel.

```bash
inkscape -z -e htw-logo.png -w 512 htw-logo.svg
```

