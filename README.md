# MPI lab4

## Exercise 1
Look for loops that cannot be unrolled or functions that cannot be inlined. 
Is there anything you can change to permit these optimizations?

*there is a directive __always_inline that tells the compiler that
 the function is to be inlined if possible, places where you want to permit
 inlining should be marked with #pragma inline_enable/disable*
 
 
 ##Exercise 2
 