R.E.A.C.T.-project-Rocket-Engine-Automated-Configuration-Tool

===

# 

### This project aims to develop a Python-based tool for the automatic generation of regeneratively cooled combustion chamber geometries, bypassing the need for conventional CAD software. Starting from a set of geometrical and design parameters, the code generates the combustion chamber, cooling channels, manifolds and related geometrical features through a fully automated meshing procedure. The final output consists of closed STL volumes that can be directly imported into slicing software for additive manufacturing or used as a starting point for further numerical or engineering analyses. The highly configurable nature of the tool also makes it possible to rapidly generate and compare different chamber and cooling-channel configurations without manually rebuilding the geometry in a CAD environment.

### 

### The project was initially started in late October 2025 and developed until the end of December 2025, before the beginning of my internship at D-Orbit. Development was then temporarily suspended, also due to several technical challenges encountered with the original geometry generation and meshing approach. In August 2026, I resumed the project and completely redesigned the meshing strategy. This new approach provided solutions to the main issues encountered during the first development phase and, at the same time, significantly simplified the implementation of subsequent geometrical features and accelerated the overall progress of the project.

### 

### As the code is still under active development, the final technical report has not yet been completed. However, several representative examples of the results obtained so far are available in the gallery folder. These examples show closed STL volumes generated directly by the code and ready to be imported into slicing software or other STL-compatible engineering tools.

