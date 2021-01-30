# yasox
yasox - Sokoban Solution Optimizer

The original YASO program is a great software with almost 20 years of development.
Although it has some limitations:
- 32-bit straight-jacket.
- A max memory limit usage of 1500 MB.
- Delphi 4 compiler only.

This fork bypass those limits and achieve:
- 64-bit.
- A max memory limit of 256 GiB !
- Delphi 10 and Free Pascal compilers.

Usage:

YASOX level.sok -log -memory 9000

YASOX level.sok -log -memory 9000 -optimize boxlines/m -order prvg -vicinity 20 10

YASOX level.sok -log -memory 9000 -optimize moves -order prvg -vicinity 20 10
