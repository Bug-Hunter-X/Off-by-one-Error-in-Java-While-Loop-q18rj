# Off-by-one Error in Java While Loop

This repository demonstrates a common off-by-one error that can occur in Java while loops due to improper incrementing of the loop counter. The `BuggyLoop.java` file contains the buggy code, while `CorrectedLoop.java` provides the corrected version. 

The bug occurs because the loop variable 'i' is incremented twice in each iteration, leading to unexpected loop termination.  This is a subtle error that can be difficult to detect without careful code review and testing.