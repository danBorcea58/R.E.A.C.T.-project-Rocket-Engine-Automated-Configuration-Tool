# R.E.A.C.T.-project-Rocket-Engine-Automated-Configuration-Tool

===

# 

### This project aims to develop a Python-based tool for the automatic generation of regeneratively cooled combustion chamber geometries, bypassing the need for conventional CAD software. Starting from a set of geometrical and design parameters, the code generates the combustion chamber, cooling channels, manifolds, the pre-injection chamber and related geometrical features through a fully automated meshing procedure. The final output consists of closed STL volumes that can be directly imported into slicing software for additive manufacturing or used as a starting point for further numerical or engineering analyses. The highly configurable nature of the tool also makes it possible to rapidly generate and compare different chamber and cooling-channel configurations without manually rebuilding the geometry in a CAD environment.

### 

### The project was initially started in late October 2025 and developed until the end of December 2025, before the beginning of my internship at D-Orbit. Development was then temporarily suspended, also due to several technical challenges encountered with the original geometry generation and meshing approach. In August 2026, I resumed the project and completely redesigned the meshing strategy. This new approach provided solutions to the main issues encountered during the first development phase and, at the same time, significantly simplified the implementation of subsequent geometrical features and accelerated the overall progress of the project.

### 

### As the code is still under active development, the final technical report has not yet been created. However, several representative examples of the results obtained so far are available in the gallery folder. These examples show closed STL volumes generated directly by the code and ready to be imported into slicing software or other STL-compatible engineering tools.



### \----------------------



### Update 28th of Septemper 2026



### After several weeks from the last commit this updated does not involve the thrust chamber. Hence the only new feature is the pre-injection chamber, which has been designed starting from zero and required significantly higher effort with respect to the thrust chamber. The description of the new component is available in the README txt file located into the "gallery/example2" subfolder and will not be discussed here. Currently only a few details for the pre-injection chamber still need to be implemented, while the thrust chamber still does not feature any flange interface and requires an important modification to its fuel output from the regenerative cycle. Moreover, the two components are completely independent from each other and require two different codes. The next commit will be mostly dedicated to merge the two scripts as well as all the required input parameters into a single dictionary. Furthermore, some effort will be spent into trying to standardize all extruding, sweeping and lofting functions into one single universal command which, starting from a set of inputs and flags, is able to incorporate all the single functions that are implemented into the code for each command. This way, not only will be the code simplified by severely reducing the number of rows, but also the future features will be much easier and faster to implement.

