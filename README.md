PART I: (55 Points) STANDARD CELL BASED FULL ADDER DESIGN
1. (5 Points) Restore the given FA_p1 schematic by designing a full adder (FA) using standard cells from GSCLIB045.
 <img width="1008" height="538" alt="image" src="https://github.com/user-attachments/assets/0470672a-db15-4580-ab38-b87a82b45744" />

2. (5 Points) Create a maestro cell view for the testbench provided. (In this part only cover the (A1, B1, Ci1) signal set. Verify the logical correctness of your FA through functional simulation
Testbench  
the waveform shows the correct functionality
it has been verified with the truth table of Full adder
  
it gives the output exactly as the truth table 

4. Question: What is the minimum steps that you need to cover all 32 vectors? Do your simulation with minimum steps. (Bonus: +5 points)

step1: we need to set trans analysis to 33ns
step2: VDD and VSS values need to be fed from stimuli
step3:select the output pins from design
step4:upload the desired vector file
step 5:run the simulation and view the result in waveform

Area calculation and pin placement estimation
  
layout  
No DRC errors reported
 
LVS is also clean
 

PART II: (55 Points) TRANSISTOR-LEVEL MIRRORED STRUCTURE
1. (5 Points) Restore the given FA_p2 cell by designing a full adder (FA) using mirrored design from Figure 1. Please follow the sizing values in the figure by referencing the standard library inverter (with [1, 1.5] sizing).
 
Note: - PMOS is 390nm,NMOS is 260nm, but the one at the extreme left are 
PMOS= 390nm x 6, NMOS = 260nm x 4

functionality and the symbol has been created successfully 

also the testbench has been created for both the parts
 

Layout for part 2 has been created
due to the huge size screenshot cannot be taken

PART III: (30 Points) MULTI-BIT ADDER CONSTRUCTION

Two RCA have been made
One is made by the Fa_p1

 

another by the Fa_p2
 

both the layouts have been created without any DRC or LVS errors
 RCA_p1  

RCA_p2
 

clearly RCA_p1 has less area and was more abutable compared to RCA_p2
