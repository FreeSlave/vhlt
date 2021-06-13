# Vluzacn ZHLT

[![Build Status](https://github.com/FreeSlave/vhlt/actions/workflows/.github.yml/badge.svg?branch=master)](https://github.com/FreeSlave/vhlt/actions/workflows/.github.yml)

Custom Zoner's Half-Life Tools created by vluzacn. This is not my project, I just need repository here to add support for determining of the number of threads on posix systems.

## Building

    make

If you want to pass additional flags to make:

    make USER_FLAGS="your flags"

Example:

    make USER_FLAGS="-static-libstdc++"
