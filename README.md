# Zambrano_et_al_2021
Code and files required for the simulations
 Extract all the files in the same folder of the main code in order to avoid errors in the working directory of the Mathematica notebook. 
 
 In order to initialize the variables in the notebook, first you need to set the working directory as the same of the notebook directory, 
 then run the line that initialize the "namesReals" variable in the selected case you intend to check. After that
 initialize the other variables ("reals", "centreal", "pobreal", "listparam", "tasareal", "listsigma").
 
 In order to plot the figures, first you have to run the line "AppendTo[$Path, "_workingDirectory_"];" where _workingDirectory_ is the path
 of the working directory. After that you need to call the previous installed "SciDraw" plotting assistant with the command "Get["SciDraw`"];"
