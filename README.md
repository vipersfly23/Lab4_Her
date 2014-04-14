Lab4_Her
========

Lab4 Creating PRISM

![alt text](https://github.com/vipersfly23/CE4_Her/blob/master/Program_A.GIF?raw=true "Program A")

* [Program A](https://github.com/vipersfly23/CE4_Her/blob/master/Program_A_Her.psm)


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
  
