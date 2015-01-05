ApplesDereconstruction
======================

This is a work in progress intended to visually demonstrate the concept of matrix rank using the [singular value decomposition](https://en.wikipedia.org/wiki/Singular_value_decomposition) (SVD) matrix factorization. It begins by decomposing the 256x256 image `sample_10.png` using the SVD and proceeds by visually showing rank-1, 2, 3, 5, 15, and -256 reconstructions. The higher the rank of the reconstruction, the more faithful the reconstruction is to the original image. The rank-256 reconstruction is identical to the original except for floating point rounding error.

It is implemented as an [IPython notebook](https://ipython.org/notebook.html) which has been exported to HTML and hosted on GitHub Pages [here](https://crowsonkb.github.io/ApplesDereconstruction/) so that it may be viewed without having IPython installed.
