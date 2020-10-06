https://github.com/schlegelp/skeletor has a great implementation of the article "Skeleton extraction by mesh contraction", but it uses CloudVloume which is not local and not easy to use.
I've created a short script for calculating the skeleton of an stl file using Trimesh.
Just add the file to the directory where you clone the code from https://github.com/schlegelp/skeletor, and add an stl file to the folder too.

References:
Au OK, Tai CL, Chu HK, Cohen-Or D, Lee TY. Skeleton extraction by mesh contraction. ACM Transactions on Graphics (TOG). 2008 Aug 1;27(3):44.
https://github.com/schlegelp/skeletor
https://github.com/aalavandhaann/Py_BL_MeshSkeletonization

The abstract and the paper can be found here: http://visgraph.cse.ust.hk/projects/skeleton/
Also see this YouTube video: https://www.youtube.com/watch?v=-H7n59YQCRM&feature=youtu.be

Some of the code in skeletor was modified from the Py_BL_MeshSkeletonization addon created by #0K Srinivasan Ramachandran and published under GPL3.

Enjoy