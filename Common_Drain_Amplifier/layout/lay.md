vdd vdd 0 DC 5
vb vb 0 DC 1
*vin vin 0 ac sin(4 1 1k 0 0 0 50)
vin vin 0 ac.sin(4 1 1k 0 0 0 50)
*vin vin 0 dc 5
.ac dec 100 100 10g
*.dc vin 0 5 .1
*.tran 0 5m
.include "C:\Users\Kanak Pradhan\OneDrive\Desktop\verilog_project\C5_models\C5_models.txt"
*.options post