# VHDL Counter Reset Bug

This repository demonstrates a common but subtle error in VHDL code related to counter resets. The `bug.vhdl` file contains a counter that may not reset correctly when the maximum count is reached.  The `bugSolution.vhdl` file provides the corrected version.

**Problem:**

The original counter is missing a line of code in the reset condition, leading to potential issues in how the counter cycles when it reaches its maximum value.

**Solution:**

The corrected code explicitly resets the counter when the maximum count is reached, ensuring proper operation.

This example highlights the importance of careful code review and testing to prevent such subtle errors that may manifest as unpredictable or incorrect behavior.