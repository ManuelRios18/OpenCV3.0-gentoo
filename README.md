
## Instructions to compile in Gentoo

1. Copy the sources in `home/nao/opencv-3.0.0`
2. inside the virtual machine Execute:

```
    cd opencv-3.0.0
    mkdir build
    cd build
    cmake -D CMAKE_BUILD_TYPE=Release -D CMAKE_INSTALL_PREFIX=/usr/ ..
    make install
```
