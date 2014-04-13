Lab4_Her
========

Lab4 Creating PRISM

=======
####Design:


######ALU Modification
The ALU was modfified by adding the following cases to the ALU code:

The following is the schematic of the cases being added to the ALU: 

######ALU Test and Debug:

*Test Result:*
  * The test was simple and straight forward. Reference below for testing results.


*Debug*
  * There wasn't much debugging required for the ALU component. The hardest thing was realizing that LDA and IN
had the same exact code.


######Datapath Modifications:
 The Datapath required quite a bit of modication. The modifications primarily composed of connecting the wires into the right components and understanding the schematic and what each oomponent does. With exception of the ALU potion, the DATA path modifcations connected all the wires:
 
 
######Datapath Test and Debug:

*Test Result*
 *  The result turned out great. The testing included declaring the ALU component, other then that, the SIMULATION was analyzed, reference the REVERSE ENGINEERING section for the analysis.
 
*Debug*
  * The debugging of the Datapath primarily composed of removing a misplaced comma and semi colon from the testbench that was improperly placed by the original author. Furthermore, I used else if, stead of elsif, so I had to go back and modify the code after receivnig an error. Other then the two debugging mentioned above, there weren't any additional debugging done.
  
