## GNU Octave ##

The chosen platform for the experimentation herein has been the GNU Octave platform. As a numerical computation platform, it is mostly compatible with comparable platforms, such as MATLAB; however, as GNU Octave is released under a GNU GPLv3 license, the source code was modified for the experiments conducted herein, which resulted in a Modified GNU Octave (M-GNU-O) platform that can better leverage certain accelerants.

In particular, GNU Octave nicely accommodates the need for treatment of matrices as a first class object. By way of example, "it is easy to define a matrix of values in Octave. The size of the matrix is determined automatically" (i.e., N-dimensional array objects are supported).

*Source: https://octave.org/doc/v4.0.1/Matrices.html*

In contrast, in Python, matrices are a special case (i.e., perhaps, not a first class object); hence, when working with matrices in Python (a.k.a. Python matrices), the NumPy package (a scientific computing package that supports N-dimensional array objects) is often utilized. Likewise, in R, the function matrix() needs to be invoked and the arguments (e.g., m number of rows, n number of columns) need to be specified (i.e., perhaps, not a first class object).

In GNU Octave, ' is matrix transposition; this syntax is quite straightforward and intuitive. In R, the easiest way to effectuate matrix transposition is, perhaps, t(). In Python 3, assuming theArray is defined, the easiest way to effectuate matrix transposition is, perhaps, [*zip(*theArray)]. '

For convenience, the Python version releases are provided in Table 1 below:

Table 1: Python Release Version Information

|Python 3.9.1  |documentation released on 8 December 2020.   |
|--------------|---------------------------------------------|
|Python 3.9.0  | documentation released on 5 October 2020.   |
|Python 3.8.7  | documentation released on 21 December 2020. |
|Python 3.8.6  | documentation released on 23 September 2020.|
|Python 3.8.5  | documentation released on 20 July 2020.     |
|Python 3.8.4  | documentation released on 13 July 2020.     |
|Python 3.8.3  | documentation released on 13 May 2020.      |
|Python 3.8.2  | documentation released on 24 February 2020. |
|Python 3.8.1  | documentation released on 18 December 2019. |
|Python 3.8.0  | documentation released on 14 October 2019.  |
|Python 3.7.9  | documentation released on 17 August 2020.   |
|Python 3.7.8  | documentation released on 27 June 2020.     |
|Python 3.7.7  | documentation released on 10 March 2020.    |
|Python 3.7.6  | documentation released on 18 December 2019. |
|Python 3.7.5  | documentation released on 15 October 2019.  |
|Python 3.7.4  | documentation released on 08 July 2019.     |
|Python 3.7.3  | documentation released on 25 March 2019.    |
|Python 3.7.2  | documentation released on 24 December 2018. |
|Python 3.7.1  | documentation released on 20 October 2018.  |
|Python 3.7.0  | documentation released on 27 June 2018.     |
|Python 3.6.12 | documentation released on 17 August 2020.   |
|Python 3.6.11 | documentation released on 27 June 2020.     |
|Python 3.6.10 | documentation released on 18 December 2019. |
|Python 3.6.9  | documentation released on 02 July 2019.     |
|Python 3.6.8  | documentation released on 24 December 2018. |
|Python 3.6.7  | documentation released on 20 October 2018.  |
|Python 3.6.6  | documentation released on 27 June 2018.     |
|Python 3.6.5  | documentation released on 28 March 2018.    |
|Python 3.6.4  | documentation released on 19 December 2017. |
|Python 3.6.3  | documentation released on 03 October 2017.  |
|Python 3.6.2  | documentation released on 17 July 2017.     |
|Python 3.6.1  | documentation released on 21 March 2017.    |
|Python 3.6.0  | documentation released on 23 December 2016. |
|Python 3.5.10 | documentation released on 5 September 2020. |
|Python 3.5.8  | documentation released on 1 November 2019.  |
|Python 3.5.7  | documentation released on 18 March 2019.    |
|Python 3.5.6  | documentation released on 8 August 2018.    |
|Python 3.5.5  | documentation released on 4 February 2018.  |
|Python 3.5.4  | documentation released on 25 July 2017.     |
|Python 3.5.3  | documentation released on 17 January 2017.  |
|Python 3.5.2  | documentation released on 27 June 2016.     |
|Python 3.5.1  | documentation released on 07 December 2015. |
|Python 3.5.0  | documentation released on 13 September 2015.|
|Python 3.4.10 | documentation released on 18 March 2019.    |
|Python 3.4.9  | documentation released on 8 August 2018.    |
|Python 3.4.8  | documentation released on 4 February 2018.  |
|Python 3.4.7  | documentation released on 25 July 2017.     |
|Python 3.4.6  | documentation released on 17 January 2017.  |
|Python 3.4.5  | documentation released on 26 June 2016.     |
|Python 3.4.4  | documentation released on 06 December 2015. |
|Python 3.4.3  | documentation released on 25 February 2015. |
|Python 3.4.2  | documentation released on 4 October 2014.   |
|Python 3.4.1  | documentation released on 18 May 2014.      |
|Python 3.4.0  | documentation released on 16 March 2014.    |
|Python 3.3.7  | documentation released on 19 September 2017.|
|Python 3.3.6  | documentation released on 12 October 2014.  |
|Python 3.3.5  | documentation released on 9 March 2014.     |
|Python 3.3.4  | documentation released on 9 February 2014.  |
|Python 3.3.3  | documentation released on 17 November 2013. |
|Python 3.3.2  | documentation released on 15 May 2013.      |
|Python 3.3.1  | documentation released on 7 April 2013.     |
|Python 3.3.0  | documentation released on 29 September 2012.|
|Python 3.2.6  | documentation released on 11 October 2014.  |
|Python 3.2.5  | documentation released on 15 May 2013.      |
|Python 3.2.4  | documentation released on 7 April 2013.     |
|Python 3.2.3  | documentation released on 10 April 2012.    |
|Python 3.2.2  | documentation released on 4 September 2011. |
|Python 3.2.1  | documentation released on 10 July 2011.     |
|Python 3.2    | documentation released on 20 February 2011. |
|Python 3.1.5  | documentation released on 9 April 2012.     |
|Python 3.1.4  | documentation released on 11 June 2011.     |
|Python 3.1.3  | documentation released on 27 November 2010. |
|Python 3.1.2  | documentation released on 21 March 2010.    |
|Python 3.1.1  | documentation released on 17 August 2009.   |
|Python 3.1    | documentation released on 27 June 2009.     |
|Python 3.0.1  | documentation released on 13 February 2009. |
|Python 3.0    | documentation released on 3 December 2008.  |
|Python 2.7.18 | documentation released on 20 April 2020     |
|Python 2.7.17 | documentation released on 19 October 2019   |
|Python 2.7.16 | documentation released on 02 March 2019     |
|Python 2.7.15 | documentation released on 30 April 2018     |
|Python 2.7.14 | documentation released on 16 September 2017 |
|Python 2.7.13 | documentation released on 17 December 2016  |
|Python 2.7.12 | documentation released on 26 June 2016.     |
|Python 2.7.11 | documentation released on 5 December 2015.  |
|Python 2.7.10 | documentation released on 23 May 2015.      |
|Python 2.7.9  | documentation released on 10 December 2014. |
|Python 2.7.8  | documentation released on 1 July 2014.      |
|Python 2.7.7  | documentation released on 31 May 2014.      |
|Python 2.7.6  | documentation released on 10 November 2013. |
|Python 2.7.5  | documentation released on 15 May 2013.      |
|Python 2.7.4  | documentation released on 6 April 2013.     |
|Python 2.7.3  | documentation released on 9 April 2012.     |
|Python 2.7.2  | documentation released on 11 June 2011.     |
|Python 2.7.1  | documentation released on 27 November 2010. |
|Python 2.7    | documentation released on 4 July 2010.      |
|Python 2.6.9  | documentation released on 29 October 2013.  |
|Python 2.6.8  | documentation released on 10 April 2012.    |
|Python 2.6.7  | documentation released on 3 June 2011.      |
|Python 2.6.6  | documentation released on 24 August 2010.   |
|Python 2.6.5  | documentation released on 19 March 2010.    |
|Python 2.6.4  | documentation released on 25 October 2009.  |
|Python 2.6.3  | documentation released on 2 October 2009.   |
|Python 2.6.2  | documentation released on 14 April 2009.    |
|Python 2.6.1  | documentation released on 4 December 2008.  |
|Python 2.6    | documentation released on 1 October 2008.   |
|Python 2.5.4  | documentation released on 23 December 2008. |
|Python 2.5.3  | documentation released on 19 December 2008. |
|Python 2.5.2  | documentation released on 21 February 2008. |
|Python 2.5.1  | documentation released on 18 April 2007.    |
|Python 2.5    | documentation released on 19 September 2006.|
|Python 2.4.4  | documentation released on 18 October 2006.  |
|Python 2.4.3  | documentation released on 29 March 2006.    |
|Python 2.4.2  | documentation released on 28 September 2005.|
|Python 2.4.1  | documentation released on 30 March 2005.    |
|Python 2.4    | documentation released on 30 November 2004. |
|Python 2.3.5  | documentation released on 8 February 2005.  |
|Python 2.3.4  | documentation released on 27 May 2004.      |
|Python 2.3.3  | documentation released on 19 December 2003. |
|Python 2.3.2  | documentation released on 3 October 2003.   |
|Python 2.3.1  | documentation released on 23 September 2003.|
|Python 2.3    | documentation released on 29 July 2003.     |
|Python 2.2.3  | documentation released on 30 May 2003.      |
|Python 2.2.2  | documentation released on 14 October 2002.  |
|Python 2.2.1  | documentation released on 10 April 2002.    |
|Python 2.2p1  | documentation released on 29 March 2002.    |
|Python 2.2    | documentation released on 21 December 2001. |
|Python 2.1.3  | documentation released on 8 April 2002.     |
|Python 2.1.2  | documentation released on 16 January 2002.  |
|Python 2.1.1  | documentation released on 20 July 2001.     |
|Python 2.1    | documentation released on 15 April 2001.    |
|Python 2.0.1  | documentation released on 22 June 2001.     |
|Python 2.0    | documentation released on 16 October 2000.  |
|Python 1.6    | documentation released on 5 September 2000. |
|Python 1.5.2p2| documentation released on 22 March 2000.    |
|Python 1.5.2p1| documentation released on 6 July 1999.      |
|Python 1.5.2  | documentation released on 30 April 1999.    |
|Python 1.5.1p1| documentation released on 6 August 1998.    |
|Python 1.5.1  | documentation released on 14 April 1998.    |
|Python 1.5    | documentation released on 17 February 1998. |
|Python 1.4    | documentation released on 25 October 1996.  |

*Source: https://www.python.org/doc/versions/*

Perhaps, GNU Octave can be construed as being more syntactically intuitive for ML.

