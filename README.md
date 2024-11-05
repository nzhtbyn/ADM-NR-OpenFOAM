<!--  [![Compatibility: OFver](https://img.shields.io/badge/Compatible_with-OpenFOAM.v2112-lightblue.svg)]()  -->
[![Paper: Author](https://img.shields.io/badge/Author-green.svg)](https://sites.google.com/view/zehtabiyan/home)
[![Compatibility: OFver](https://img.shields.io/badge/Compatible_with-OpenFOAM.v2312-lightblue.svg)]()

# Description
Enabling the momentum-source calculator of the actuator-disk model without rotation (ADM-NR) in OpenFOAM to calculate the source terms based on the disk-averaged velocity.


# Target platform
The code has been rigorously tested and verified to be fully compatible with OpenFOAM v2012, v2112, and v2312, ensuring its smooth integration and reliable performance.

# How to set the model
1- Download the source code.

2- To enable the momentum-source calculator of the actuator-disk model without rotation (ADM-NR) in OpenFOAM to calculate the source terms based on the disk-averaged velocity, follow these instructions:

$\bullet$ Go to your work directory via the following command:
  
`cd $WM_PROJECT_USER_DIR`
       
$\bullet$ Copy the folder _ADM_NR_diskBased_ to your work directory, and compile the new library with the following command
  
 `wmake`
 
$\bullet$ Add the library name to _controlDict_ and update the name in _fvOptions_.


# How to cite
Please, cite this library as:
```
@misc{ADMNR_OF,
  author = {Zehtabiyan-Rezaie, N.},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/nzhtbyn/ADM-NR-OpenFOAM}}
}
```
