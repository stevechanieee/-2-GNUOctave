## GNU Octave ##

The chosen platform for the experimentation herein has been the GNU Octave platform. As a numerical computation platform, it is mostly compatible with comparable platforms, such as MATLAB; however, as GNU Octave is released under a GNU GPLv3 license, the source code was modified for the experiments conducted herein, which resulted in a Modified GNU Octave (M-GNU-O) platform that can better leverage certain accelerants.

In particular, GNU Octave nicely accommodates the need for treatment of matrices as a first class object. By way of example, "it is easy to define a matrix of values in Octave. The size of the matrix is determined automatically" (i.e., N-dimensional array objects are supported).

https://octave.org/doc/v4.0.1/Matrices.html

In contrast, in Python, matrices are a special case (i.e., perhaps, not a first class object); hence, when working with matrices in Python (a.k.a. Python matrices), the NumPy package (a scientific computing package that supports N-dimensional array objects) is often utilized. Likewise, in R, the function matrix() needs to be invoked and the arguments (e.g., m number of rows, n number of columns) need to be specified (i.e., perhaps, not a first class object).

In GNU Octave, ' is matrix transposition; this syntax is quite straightforward and intuitive. In R, the easiest way to effectuate matrix transposition is, perhaps, t(). In Python 3, assuming theArray is defined, the easiest way to effectuate matrix transposition is, perhaps, [*zip(*theArray)]. 

Perhaps, GNU Octave can be construed as being more syntactically intuitive for ML.

