This project is a continuation of research on a topic first discovered by Benjamin Franklin.
The research is somewhat incomplete, as all of the necessary materials to complete the research has been developed but the results have not yet been found.

In order to understand all of the subsequent materials for this project, it would be useful to understand what a Franklin Circle is.
A Franklin (a, r)-circle is a circle with "a" annuli and "r" radii.
If a=r, the circle can then be referred to as a Franklin (a)-circle.
In this project we will only be concerned with Franklin (8)-circles and Franklin (16)-circles.
Given these Franklin Circles, we also need to index the annuli, the radii, and the spaces they create.
The innermost annuli will be the first and the outermost the 16th.
For the radii, we index the radius in the second quadrant that sits on the horizontal axis to be the first.
The remaining radii will be indexed clockwise.
Thus, the 16th lies in the third quadrant and hangs below the horizontal axis.
The spaces will be denoted by x_(i,j), where i and j are the indices of the radii and annuli, respectively.

Generally speaking, there were two goals of this research:
1) enumerating all of the Franklin (8)-circles
2) finding a basis for Franklin (16)-circles

The "Enumeration" file contains the code necessary to complete the first goal.
This code works sequentially through every possible configuration of numbers to determine if that configuration is actually a Franklin Circle.
Ultimately, the "end result" of this code is the number of Franklin-8 circles.
I extended this code to enumerate all Franklin (16)-circles, however this version is not included because the code requires minor changes but is otherwise entirely repetitive.

The "Matrix Code" file contains the code for the second goal, and the "Equations" file contains the equations expressed in the matrices.
This code generates a 376x256 matrix that could be used to find the basis of a Franklin Circle.
Each row is an equation that expresses a different condition of a Franklin (16)-Circle.
