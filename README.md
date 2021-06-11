# MiniMiniZ

This the amalgamated [miniz library](https://github.com/richgel999/miniz) in a single header.

## Usage

Copy `miniminiz.h` into your C or C++ project, include it anywhere you want to use MiniZ API.
Then do the following in *one* C file to implement MiniZ:
```c
#define MINIZ_IMPL
#include "miniminiz.h"
```
Note that almost no modification was made in the MiniZ implementation code,
thus there are some C variable names that may collide with your code,
therefore it is best to declare the Lua implementation in dedicated C file.

Optionally provide the following defines:
  - `MINIZ_EXPORT`     - qualifier on API declarations

## Updates

- **11-Jun-2021**: Library create using [this latest commit](https://github.com/richgel999/miniz/commit/9edb278d22ad5545fb4561595a4d96eaab55ffa3).

## License

Same license as MiniZ.
