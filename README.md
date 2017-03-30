# travis_qmake_gcc_cpp14_bpp

Branch|[![Travis CI logo](TravisCI.png)](https://travis-ci.org)|[![Codecov logo](Codecov.png)](https://www.codecov.io)
---|---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_bpp.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_bpp)|[![codecov.io](https://codecov.io/github/richelbilderbeek/travis_qmake_gcc_cpp14_bpp/coverage.svg?branch=master)](https://codecov.io/github/richelbilderbeek/travis_qmake_gcc_cpp14_bpp/branch/master)
develop|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_bpp.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_bpp)|[![codecov.io](https://codecov.io/github/richelbilderbeek/travis_qmake_gcc_cpp14_bpp/coverage.svg?branch=develop)](https://codecov.io/github/richelbilderbeek/travis_qmake_gcc_cpp14_bpp/branch/develop)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++14`
 * Libraries: `STL` and `Bio++`
 * Code coverage: none
 * Source: one single file, `main.cpp`

Less builds:
 * Use of C++98: [travis_qmake_gcc_cpp98_bpp](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98_bpp)
 * Use of C++11: [travis_qmake_gcc_cpp11_bpp](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11_bpp)
 * Use of STL only: [travis_qmake_gcc_cpp14](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14)
