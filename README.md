<!--  [![Compatibility: OFver](https://img.shields.io/badge/Compatible_with-OpenFOAM.v2112-lightblue.svg)]()  -->
[![Paper: Author](https://img.shields.io/badge/Author-green.svg)](https://sites.google.com/view/zehtabiyan/home)
[![Compatibility: OFver](https://img.shields.io/badge/Compatible_with-OpenFOAM.v2312-lightblue.svg)]()

# Description
The developed solver handles governing equations in mixed convection heat transfer including continuity, momentum, energy, and electrical equations. The developed solver is able to handle the coupled equations. For a comprehensive understanding of this solver, see this [publication](https://doi.org/10.1016/j.elstat.2019.103415).

# How to set the model
1- Download the source code.

2- To enable the momentum-source calculator of the actuator-disk model without rotation (ADM-NR) in OpenFOAM to calculate the source terms based on the disk-averaged velocity, follow these instructions:

$\bullet$ Go to your work directory via the following command:
  
`cd $WM_PROJECT_USER_DIR`
       
$\bullet$ Copy the folder _ADM_NR_diskBased_ to your work directory, and compile the new library with the following command
  
 `wmake`
 
