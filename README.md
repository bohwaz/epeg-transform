epeg
====

Insanely fast JPEG/JPG thumbnail scaling with the minimum fuss and CPU
overhead. It makes use of libjpeg features of being able to load an image by
only decoding the DCT coefficients needed to reconstruct an image of the size
desired.

Forked from https://github.com/mattes/epeg

## Install

    sudo apt-get install build-essential cmake nasm
    git clone github.com/koofr/epeg
    cd epeg
    mkdir build
    cd build
    cmake ..
    sudo make install
