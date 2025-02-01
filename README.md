# Tcl String Comparison Bug
This repository demonstrates a common error in Tcl string comparisons, specifically when using the `==` operator.  The code in `bug.tcl` attempts a numerical comparison, but because it's using strings the behavior is unexpected leading to potential issues.