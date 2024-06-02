# Example-of-MPT3-toolkit-solution-failure
This document presents a series of cases where the conversion from V-representation to H-representation using the MPT3 toolbox fails.
The ‘Vertex’ file contains a set of 5-dimensional vertices. Execute the following statements in the MATLAB environment：
P=Polyhedron('V',Vertex)
This function is used in the MPT3 toolbox for solving convex hulls. The resulting structure P does not contain the computed parameter matrices H and b.
