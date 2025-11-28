# SCPI-Multimeter-Simulator
Simulates an SCPI-controlled DMM measuring components of an RLC circuit. 
1. Run fake_scpi_instrument.py
2. Run client.py
3. Client runs through series of sequential test queries and commands, returning values in an RLC circuit:
   a. *IDN?
   b. MEASU:IMM:TYP VDC
   c. MEASU:IMM:TYP VDC?
   d. MEASU:IMM:TYP IDC?
   e. MEASU:IMM:TYP IDC
   f. MEASU:IMM:TYP IDC?

I am currently working on adding user input, allowing them to choose the target RLC component to measure voltage across. 
