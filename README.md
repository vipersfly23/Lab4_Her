Lab4_Her
========

Lab4 Creating PRISM
=======
####Design:


######ALU Modification
The ALU was modified by adding the following cases to the ALU code:

![alt text](https://github.com/vipersfly23/Lab4_Her/blob/master/ALU_case.GIF?raw=true "ALU MODIFICATIONS")

The following is the schematic of the cases being added to the ALU: 

![alt text](https://github.com/vipersfly23/Lab4_Her/blob/master/ALU_Schematic.GIF?raw=true "ALU SCHEMATIC")

######ALU Test and Debug:

*Test Result:*
  * The test was simple and straight forward. Reference below for testing results and analysis.
  
  ![alt text](https://github.com/vipersfly23/Lab4_Her/blob/master/ALU_analysis_1.GIF?raw=true "1 of 3 Analysis")
  ![alt text](https://github.com/vipersfly23/Lab4_Her/blob/master/ALU_analysis_2.GIF?raw=true "2 of 3 Analysis")
  ![alt text](https://github.com/vipersfly23/Lab4_Her/blob/master/ALU_analysis_3.GIF?raw=true "3 of 3 Analysis")

*Debug*
  * There wasn't much debugging required for the ALU component. The hardest thing was realizing that LDA and IN
had the same exact code.


######Datapath Modifications:
 The Datapath required quite a bit of modication. The modifications primarily composed of connecting the wires into the right components and understanding the schematic and what each oomponent does. With exception of the ALU potion, the DATA path modifcations connected all the wires:
 
 ![alt text](https://github.com/vipersfly23/Lab4_Her/blob/master/Datapath_schematic.GIF?raw=true "DATAPATH MODIFICATIONS")
 
 
######Datapath Test and Debug:

*Test Result*
 *  The result turned out great. The testing included declaring the ALU component, other then that, the SIMULATION was analyzed, reference the REVERSE ENGINEERING section for the analysis.
 
*Debug*
  * The debugging of the Datapath primarily composed of removing a misplaced comma and semi colon from the testbench that was improperly placed by the original author. Furthermore, I used else if, stead of elsif, so I had to go back and modify the code after receivnig an error. Other then the two debugging mentioned above, there weren't any additional debugging done.
 
*Testbench Operation*
 * The operation of thePRISM work as the schematic provided for the datapath and alu, the missing portion is the memory. That's where the testbench comes in. The testbench plays the memory role, thus providing the data, and address as a memory would normally hold. That's the main operation of the testbench, is providing the information, playing the role of memory.

####Lab Functionality

ALU Simulation [COMPLETED]

Datapath Simulation Demo [COMPLETED]

######Files:

[ALU SHELL](https://github.com/vipersfly23/Lab4_Her/blob/master/ALU_shell.vhd)

[ALU TESTBENCH](https://github.com/vipersfly23/Lab4_Her/blob/master/ALU_testbench.vhd)

[DATAPATH SHELL](https://github.com/vipersfly23/Lab4_Her/blob/master/Datapath_shell.vhd)

[DATAPATH TESTBENCH](https://github.com/vipersfly23/Lab4_Her/blob/master/Datapath_testbench.vhd)

[LAB4 WAVE](https://github.com/vipersfly23/Lab4_Her/blob/master/Lab4_waveform.wcfg)

####REVERSE ENGINEERING

######Simulation Analysis (CLICK TO ENLARGE):

50ns - 100ns Analysis

![alt text](https://github.com/vipersfly23/Lab4_Her/blob/master/Datapath_analysis.GIF?raw=true "50ns - 100ns Analysis")

Jump Instruction Analysis:

![alt text](https://github.com/vipersfly23/Lab4_Her/blob/master/Datapath_Jump.GIF?raw=true "Jump Instruction Analysis")

######Prism Program Listing w/ Address

Below is the program listing, inserted into the PRISM program for neatness.

![alt text](https://github.com/vipersfly23/Lab4_Her/blob/master/Datapath_address.GIF?raw=true "Program A")


========
####Documentation

No help received.


  
