This repository demonstrates a potential crash in Objective-C related to the use of `performSelector:withObject:afterDelay:` and object deallocation.  The `bug.m` file contains the problematic code, which leads to a crash due to accessing released memory. The solution, provided in `bugSolution.m`, addresses this by utilizing blocks and GCD, ensuring proper object lifecycle management.