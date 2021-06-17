# Computer Arquitecture
## Filter creation

The project consists of the programming, in assembler of the Motorola 88110, of a set of routines that perform the filtering of an image by means of a programmable filter.
The project consists of programming, in assembler of the Motorola 88110, a set of routines that perform the filtering of an image by means of a programmable filter.
The image will be an array of p ıxels, each of which is represented by an unsigned byte that specifies its level.

unsigned byte specifying its grey level (0 equals black and 255 equals white). The filter
filter is based on a recursive convolution operation with a kernel represented by
a constant K and a matrix of dimension 3.

Each element of the filter is actually a fractional number obtained by dividing the corresponding element of the matrix by the constant K.
