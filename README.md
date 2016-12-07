main
========================

[![Build Status](https://travis-ci.org/unius1004/test.svg?branch=master)](https://travis-ci.org/unius1004/test)

C++ STL variant of https://code.google.com/p/google-diff-match-patch.

STL Port was done by Sergey Nozhenko (snhere@gmail.com) and posted on
https://code.google.com/p/google-diff-match-patch/issues/detail?id=25

The STL Port is header only and works with std::wstring and std::string.

Compile and run the test cases:

    g++ main.cpp -o main && ./main

Or use CMake ...

Compile and run the speedtest - requires the files speedtest1.txt and speedtest2.txt for comparison:

    g++ main.cpp -o main && ./main
