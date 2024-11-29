How to use?

- get the tiff files from anywhere, better - suite2p corrected
- convert to 32 bit through ImageJ, crop to get the final size less than 4 Gb
- save the final file
- recommended to create a folder to place the file
- run the AQuA2 in Matlab (no excluded borders, set the fps etc.), threshold on 2-3, test a few)
- run CFU and choose the CFUs that you need
- load the traces to the workspace and save the .mat file with the masks and traces to the previously created folder

Then:
- set up the standard conda env and install all necessary libs
- run the imports
- run the functions
- create the cell with the links to the .mat file and where to save the outputs
- run the cell with links and the script cell
