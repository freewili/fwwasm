Free-Wili WASM header
=====================

This header is for use in projects requiring API access to Free-Wili specific functionality. This repository can easily be integrated into existing cmake projects with the included CMakeLists.txt


Documentation
=============

https://freewili.github.io/fwwasm/

cmake
=====

```cmake
add_subdirectory(path/to/fwwasm fwwasm)
target_link_libraries(${CMAKE_PROJECT_NAME} fwwasm)
```

Doxygen
=======
```bash
doxygen Doxyfile
```


clang-format
============
```bash
clang-format include/fwwasm.h -style=file:.clang-format -i
```


License - MIT
=======

```
MIT

Copyright Intrepid Control Systems, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```