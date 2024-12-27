# Go: Panic on Nil Map Access

This repository demonstrates a common error in Go: panics caused by accessing elements in a nil map.  The `bug.go` file contains code that will panic if run. The `bugSolution.go` file shows the corrected version.

**Problem:** Attempting to access a map element before checking if the map is nil results in a runtime panic.

**Solution:** Always check if a map is nil before accessing its elements.