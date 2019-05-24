                                     5-stage Ring Oscillator Schematic- To -Layout Design
   
   A ring oscillator is a circuit which consists of an odd number of inverter stages, where the output of each stage of the ring oscillator is given to the input of next stage and output of final stage is then fed back to the first stage input. Also, no external input is given to the device, only an initiallization pulse is provided at once to drive the circuit. Initiallization is required to avoid metastability in the design. 

Report: Created a report file to summarize the work done

Tools Used:
Mentor Graphics - Tanner L-Edit (Physical Layout)
Mentor Graphics - Tanner T-Spice (Netlist creation & Simulation)
    
Observation and Results:     
    Analyzed the design with and without initialliation to understand the metastable behaviour of the circuits.
    Based on calculations and Simultion, verified the frequency of Oscillation with change in supply Voltage, Operating Temperature
    and Load capacitance
    
Conclusion:
    Based on tested cases, observed a specific case in terms of supply voltage and temperature was best suited for high speed operation
    of the circuit
    With minimum load capacitance the circuit can work faster
    Also, an interesting note is that the number of stages is not correlated with delay of the circuit 
