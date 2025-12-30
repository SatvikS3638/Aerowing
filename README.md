# Project Overview
Three airfoil geometries which were selected on the basis of ease of maufacturing were selected as potential candidates of 2D sections of the rear wing of a FS vehicle and numerical analysis was coducted and compared in high-fidelity and low-fidelity simulations using ANSYS and Xflr5 respectively to determine the one with optimal lift and drag performance at an Angle of Attack range of 0 to 15 degrees. The flow conditions were taken to be 80 kmph and characteristic length = 1m. 

# Numerical Setup
## ANSYS Fluent
Fluent was used as the ANSYS tool for the CFD analysis. The Re = 1564574 was calculated from the given flow conditions and inlet was adust accordingly for airfoil chord length. The y+ value for grid spacing near the wall of the C-mesh domain was calculated from the tool provided by [https://www.cadence.com/en_US/home/tools/system-analysis/computational-fluid-dynamics/y-plus.html]. A circular region of finer mesh was introduced around the airfoil to further improve the results. The turulence model used was viscous k-omega SST.

## XFLR5
The Re based flow conditions and airfoil geometry were provided to the tool which extracted the required results as directed. 

# Results
Among the three airfoils analysed(NACA 4412, LNV109A, NACA 2410) NACA 4412 seemed to provide the optimal Lift-to-Drag ratio over the Angle of Attack range. 

