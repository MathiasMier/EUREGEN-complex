# complex
Complex model with all the complicated stuff (i.e., complicated calibration routines, endogenous technological chane, investor types, myopic or overlapping modeling, many storage technology specific equations, much space for sensitivity analysis, elastic demand, ...)

1) Download zip-file and unpack (leave folder structure as it is) (the model code is already in the zip-file and no need to place it for the current version; however, check for updates of the code)
2) Get CPLEX or Gurobi solver (e.g., https://www.gurobi.com/features/academic-named-user-license/; Gurobi is manually activated, to use CPLEX go to line 1365 and place the * in the beginning of that line and remove the * in line 1366)
3) Download databases from https://zenodo.org/records/10413375 and put into database-folder of the unpacked folder structure
4) Open shell and run the bat-files "run_31segments" (for database v1111xx_3d_1d) or "run_119segments" (for database v1111_4d_1d) (the bat-files run 4x2 scenarios each: bauprice, recovery, high, and long (that mainly vary in the long-run price of natural gas) with/without the EU ETS supplementing policies such as renewables or nuclear targets)
5) Wait shortly for 31 segments and a bit longer for 119 segments (both resolutions are choosen so that they are easily accesible also without much computational power)
6) Consult "Output" for all variables and "Report" for condensed
7) There is a simple visualization routine via the excel (selected report is written into the excel-folder)
