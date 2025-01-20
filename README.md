This repository contains a Hack program that demonstrates a subtle type error. The error occurs due to implicit type conversion during function calls.  The `bug.hack` file contains the buggy code, while `bugSolution.hack` provides a corrected version.

The bug is tricky because it involves a chain of function calls, where a type mismatch in the intermediate steps only becomes apparent in the final result. This highlights the importance of careful type checking and understanding implicit type conversions in Hack.

The solution demonstrates how to correctly handle type conversions to avoid the error and produce the expected output.