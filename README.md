This Python Code is for calculation of Cooling Performance of Simple Tube & Plate Type Crossflow Heat Exchanger.

Water is considered as Hot fluid. 
Air is considered as Cold fluid. 
5 Tubes are in Horizontal orientation from which Water flows. 
5 Plates are in Vertical orientation across which Air flows.

Input parameters and properties of Water, Air, Tube and Plates are defined in the code.

Vw_list includes Velocity of Water at Inlet, e.g. Vw_list = [0.00625, 0.0125, 0.025, 0.05, 0.1, 0.2] # m/s. Va_list includes Velocity of Air at Inlet, e.g. Va_list = [12, 12, 12, 12, 12, 12] # m/s. Various combinations of the Inlet velocities can be tried.

Other parameters can also be changed based on the requirement.

CFD results from ANSYS Fluent are mentioned for Comparison. These results can be modified as per requirements. Water_out_temps_ansys shows the results from simulation in Ansys Fluent, e.g. Water_out_temps_ansys = [347.99, 350.85, 352.6, 353.69, 354.34, 354.71] # K. Air_out_temps_ansys shows the results from simulation in Ansys Fluent, e.g. air_out_temps_ansys = [297.63, 297.67, 297.69, 297.72, 297.73, 297.74] # K. (These CFD results are for Inlet Water Velocity of [0.00625, 0.0125, 0.025, 0.05, 0.1, 0.2]  m/s and Inlet Air Velocity of [12, 12, 12, 12, 12, 12]  m/s). These results from Ansys fluent are compared in the Graphs with results from Numerical calculation.

This code also creates the Diagram of Tube and Plate type Heat Exchanger based on the inputs given.
