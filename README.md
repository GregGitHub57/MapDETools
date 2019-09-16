# MapDETools
The purpose of this repository is to provide the public version of the MapDE software related to the paper "Symmetry-based algorithms for invertible mappings of polynomial nonlinear PDE to linear PDE".  This is a research project to develop efficient Maple implementations for determining invertible mappings of differential polynomial systems. 
MapDETools gives tools to help the user to determine the linearizability of nonlinear differential polynomial systems and construct the map if it exists.

# Installation
**IMPORTANT* Requirements:    -- You must have Maple 18**
## Instruction for Windows installation of the MapDETools
******************************************************************
1. Download the LieAlgebrasOfVectorFields package from [LieAlgebrasOfVectorFieldsPackage](http://www.canberra.edu.au/research/faculty-research-centres/msrc/projects/lavf).
2. Follow its installation instruction steps which is: 
   - Copy all three .hdb files (VectorField.hdb, LHPDE.hdb and LAVF.hdb) to your Maple local repository lib folder.  
   - Copy all four .mla files (VectorField.mla, Basis.mla, LHPDE.mla, LAVF.mla) to your Maple lib folder.
   - Restart Maple 
3.  You should be able to load its three packages if the installation was succeeded
    - Type  with(VectorField); with(LinearHomogeneousPDE); with(LieAlgebrasOfVectorFields)
4. Download MappingDETools.mla from the MapDE folder, provided here, and copy it to your Maple local repository lib folder.
5. Restart Maple.
6. Type with(MapDETools) and load MapDETools package.
### Note: 
If the help pages of the LieAlgebrasOfVectorFields package did not work, Please download the updating help pages from the LAVF folder, provided here.


# Demo Notebook
We provide a Demo file included some selected highlights example in the purpose of introducing the functionality of the MapDE algorithm and illustrate the present advantages and future developments in the MapDETools.

# Note from the authors: 
The MapDETools package is in progress. The provided version is the result of our research. We would greatly appreciate for any suggestions and comments that help us to improve the quality of the user version.
