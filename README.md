# MOARJPEG

When you must have moarjpeg.

```
Usage:
  moarjpeg [options] filename
Version:   0.0.1

Adds moar jpeg.

Options: (all optional)
  i ITERATIONS:   The number of iterations to perform (default 2)
  q QUALITY:      The quality to use when compressing (defualt 8)
  s SIZE:         Downsizes the image; incrementally scaling the image up to the
                  original size, adding additonal artifacts with each iteration
                  (defualt 80)
  o OUTPUT:       Output file

Example:
  moarjpeg -i 5 -o moar.jpeg
```
