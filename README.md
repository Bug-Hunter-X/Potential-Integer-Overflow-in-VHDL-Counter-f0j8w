# VHDL Counter with Potential Overflow
This repository demonstrates a potential integer overflow bug in a simple VHDL counter.
The counter uses a generic to define its size, but lacks a check for overflow. This could lead to unexpected behavior when the counter reaches its maximum value.
The `bug.vhdl` file contains the buggy code. The solution is presented in `bugSolution.vhdl`.