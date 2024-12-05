# Off-by-One Error in Go Slice Iteration

This repository demonstrates a common off-by-one error in Go when iterating over slices. The `bug.go` file contains the erroneous code, while `bugSolution.go` provides the corrected version.

The error arises from an incorrect loop condition that causes the code to access an index beyond the bounds of the slice, resulting in a runtime panic.

The solution shows how to properly iterate using the `<` operator instead of `<=` to avoid this issue.