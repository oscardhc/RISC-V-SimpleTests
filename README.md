# RISC-V-SimpleTests

Here's some simple tests of RISC-V instructions, including assembly language (`.code` files) and "binary" data files (`.data` files, writting in plain text).

Data files can be loaded with `$memreadb` in Verilog, and every single line is a byte in memory.

| Test names | Instructions used       |
| ---------- | ----------------------- |
| I1         | `ori`                   |
| J          | `ori`, `jal`, `jalr`    |
| LS1        | `ori`, `lw`             |
| LS2        | `ori`, `lw`, `sw`, `sh` |