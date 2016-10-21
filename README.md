# How to install pyfst
The python package pyfst is needed for reconstructing compound words. This package itself needs OpenFst shared libararies, that we already built when installing Kaldi. To install pyfst and make it use the Kaldi's OpenFst libraries, install it like that (as root):

`CPPFLAGS="-std=c++0x -I/usr/local/kaldi-trunk/tools/openfst/include -L/usr/local/kaldi-trunk/tools/openfst/lib" sudo  pip install pyfst
`

# Reference
http://oss.io/p/alumae/kaldi-offline-transcriber
