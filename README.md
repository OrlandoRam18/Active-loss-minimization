# Active-loss-minimization
The directory is a set of files that optimize the losses of active power in a power system, the power system data regarding bus, line, generators and shunt elements is specified on the excel file: 14 bus data.xlsx, the set of functions can be used to optimize active power losses on any power system given the data in the 14 bus data.xlsx format.
To execute the program just run the file Main_ploss.py

The constrains considered by the proposed code are the following:
•	Maximum and minimum generation limits per each unit
•	Voltage profile limits
•	Maximum and minimum reactive limits of compensation devices
•	Transmission limits of lines and transformers
The solver used to optimize the active power losses was the Sampe Jaya.


