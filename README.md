# RootSlice_FBA
RootSlice files needed to generate lateral root anatomy parameters that are fed into the FBA model used in the manucript titled A role for fermentation in aerobic conditions as revealed by computational analysis of maize root metabolism during growth by cell elongation.

# Here are the steps to run RootSlice (currently we have only tested on Windows):
1. Download the zip file named "RootSlice_9-7-2023.1"
2. Extract the files and make sure RootSlice.exe, InputData file, and all the VTK files are in the same folder.
3. Input parameters can be changed in the InputData file. Description for each parameter are given in the alongside the parameters.
4. Once you have the desired InputData file, run the RootSlice.exe. Ignore the VTK errors.
5. Once the program has finished, navigate to the new generated folder which will be titled with the user given name (specified in the InputData file).
6. To visualize the root model, Open all the tissue and subcellular feature files as one paraview (https://www.paraview.org/download/) project. Dont add the allVTP file.
7. volume parameters for each cortical cell layer can be obtained from the "individual_cortical_cell_volume" file.
8. Epidermis volume and surface area calculations are done by post processing the cortical cell file data. 
