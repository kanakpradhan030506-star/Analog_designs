## PROJECT : CMOS COMMON SOURCE AMPLIFIER

# AIM

To design and simulate a CMOS Common Source Amplifier using PMOS and NMOS transistors and study its output response.

# THEORY

A Common Source Amplifier is a basic analog circuit used for voltage amplification.

# Features:

• High voltage gain  
• Output taken from drain terminal  
• Input given to gate terminal  
• PMOS acts as load transistor  
• NMOS acts as amplifying transistor  

# CIRCUIT DESIGN

Components used:
• VDD = 5V  
• PMOS transistor (W = 5)  
• NMOS transistor (W = 20)  
• Input voltage source (Vin)  
• Output voltage (Vout)  

Connections:
• PMOS source connected to VDD  
• NMOS source connected to ground  
• Input applied at NMOS gate  
• Output taken from drain node  

# WORKING

When Vin is low:

• NMOS OFF  
• PMOS ON  
• Output remains high  

When Vin increases:

• NMOS starts conducting  
• Current flows  
• Output voltage changes  


# SIMULATION

DC Sweep Analysis performed from 0V to 5V.

Observed:
• Input voltage increases linearly  
• Output changes according to transistor conduction  
• Proper amplifier behavior observed  

# RESULT

The CMOS Common Source Amplifier was successfully designed, simulated, and verified.

# APPLICATIONS

• Signal amplification  
• Analog circuits  
• CMOS IC design  
• VLSI design 

# CONCLUSION

The circuit successfully demonstrates common source amplifier operation and helped in understanding CMOS analog circuit design.