# MapDETools
The purpose of this repository is to provide the publicity version of the MapDE code related to the paper "Symmetry-based algorithms for invertible mappings of polynomial nonlinear PDE to linear PDE".  This is a research code and in progress towards to supply efficient Maple implementations for determining an invertible mapping of differential polynomial systems when it exists. 
MapDETools gives a potent mixture of speed and productivity features of the LAVF to help the user to determine the linearizability of nonlinear differential polynomial systems to linear one and construct the map if it exists.

# Installation
*IMPORTANT* Requirements:    -- You must have Maple 18.
Instruction for Windows installation of the MapDETools
******************************************************************
1. Download LieAlgebrasOfVectorFields package from "LieAlgebrasOfVectorFieldsPackage" 
2. Follow its installation instruction steps. 
    2.1. Copy all three .hdb files (VectorField.hdb, LHPDE.hdb and LAVF.hdb) to your Maple local repository lib folder. 
    2.2. Copy all four .mla files (VectorField.mla, Basis.mla, LHPDE.mla, LAVF.mla) to your Maple lib folder.
    2.3. Restart Maple. 
3.  You should be able to load three packages if the installation was succeeded
   -- Type  with(VectorField);
   -- Type  with(LinearHomogeneousPDE);
   -- Type  with(LieAlgebrasOfVectorFields);
4. Download MappingDETools.mla from the MapDE folder and copy it to  your Maple local repository lib folder.
5. Restart Maple.
6. Load MapDETools.

# Demo Notebook
We provide a Demo file included some selected highlights example in the purpose of introducing the functionality of MapDE algorithm and illustrate the present advantages and future developments in the MapDETools.

# Note from the authors: 
The MapDETools package is in progress. The provided version is the result of our research steps. The public version needs cleaning and debugging steps. We would greatly appreciate for any suggestions and comments that help us to improve the quality of the user version which supposed to integrate into Ma¬ple.
