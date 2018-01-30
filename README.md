# Systems of Springs
This repository contains a few helpful pieces of Python code 
that can be used to compute time dependent positions of 
springs in 2 and 3 dimensions. This is some introductory work
I am doing to learn about finite element analysis. My goal is
to eventually use the code from this project to simulate 
structural engineering problems.

# To Do
* Need to fix the issue with the animation in 2 and 3 dimensions.
The problem is that I only have certain lines connecting the masses
together. Instead I need to write the code that looks at the matrix
K and connect masses based on the none zero entries in that matrix.
This way any system can be animated.
* Use a more accurate numerical method of solving the spring dynamics.

# Contents
* literature - This directory contains relavent articles I used to
	write my Python code.
* src - The directory that contains the jupyter notebooks and 
	various other source codes used to simulate springs.

