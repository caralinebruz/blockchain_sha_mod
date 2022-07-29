# Modified SHA-256
Modified implementation of the SHA-256 algorithm in Python.

The code is based closely as possible to the standard for maximum clarity. The standard can be found here: http://dx.doi.org/10.6028/NIST.FIPS.180-4

My modification includes double rotation of `sigma_0`, corresponding to `term_2` in the suffix of each 512 bit chunk of message. The number of rounds remains the same. The block size remains the same.
