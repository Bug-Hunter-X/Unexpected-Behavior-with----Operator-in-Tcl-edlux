# Tcl Bug: Unexpected Behavior with == Operator

This repository demonstrates an uncommon bug in Tcl related to the `==` operator.  The `==` operator in Tcl performs string comparison instead of numerical comparison, leading to incorrect results when numbers are treated as strings.

The file `badproc.tcl` shows a procedure that uses `==` to compare numbers. The file `badproc_solution.tcl` shows a corrected version. 