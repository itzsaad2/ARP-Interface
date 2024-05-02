A Networking assignment from my CSC358 networking course. implemented a simple Network interface that is capable of sending and reciving packets using ARP mapping.











This repository contains programming assignments of the course. They are based on Stanford's CS 144 assignments.

To set up the build system: `cmake -S . -B build`

To compile: `cmake --build build`

To run tests: `cmake --build build --target test`

To run speed benchmarks: `cmake --build build --target speed`

To run clang-tidy (which suggests improvements): `cmake --build build --target tidy`

To format code: `cmake --build build --target format`
