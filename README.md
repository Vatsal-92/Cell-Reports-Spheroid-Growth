# Cell-Reports-Spheroid-Growth

This repository contains the following files:
1. A subroutine to predict the growth of a tumour spheroid in hydrogels of different stiffness, taking into account biochemical signalling from bone cells i.e. osteoblasts and osteoclasts, via signalling constants for TNF-α (𝛾𝛼), TGF-β (𝛾𝛽) and IL-6 (𝛾6). 
2. An Abaqus input file describing the finite element model setup

Code Demo:
1. Install Abaqus Cae (https://www.3ds.com/products-services/simulia/products/abaqus/abaquscae/), Visual Studio and oneAPI
2. Link Abaqus with Visual Studio and oneAPI to run subroutines
3. Open Abaqus command window to run the subroutine with the .inp file in Abaqus
   
These files are configured to reproduce the simulated 4T1 tumor spheroid growth in the tri-culture (i.e. MC3T3+RAW+4T1) conditions as reported in Figure 2I of the manuscript. All other simulated results can be reproduced by modifying the parameters as outlined in the manuscript

For any questions regarding these files, please contact Vatsal Kumar, Eoin McEvoy or Laoise McNamara.
