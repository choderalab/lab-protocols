##Module 1: 96-well PCR Cleanup protocol

###SUMMARY: 
This protocol will generate a 96-well plate of unique PCR products, that have been cleaned up and can be used in the upcoming LIC cloning PCR step. 

###TIMING: Not sure yet  

###MATERIALS: 
-  nuclease-free dd H2O in buffer trough 
- reservoir of resuspension buffer
  - EB: 10 mM Tris·Cl, pH 8.5
  - TE: 10 mM Tris·Cl, 1 mM EDTA, pH 8.0
- 96 well 4ti-110 plate (Destination plate)
- Omega 10k MWCO Pall plate 96 well plate
- Scripts
  - Evo: "WIP_SKA_PCRCleanup"
  - Momentum: "WIP_PCRCleanup_SKA"

###INPUT/OUTPUT: 
- Input: a sealed, 384 well plate with PCR product 
- Output: a sealed, 96 well plate with cleaned up PCR product ready for LIC 

###BUFFERS: 
- TE buffer (see above) 

###EQUIPMENT: 
- EVO
- PlateLoc
- INHECO incubator 

###Protocol: 
![Image of workbench](https://github.com/choderalab/lab-protocols/blob/molecular_biology/Molecular_Biology/protocols/img/PCR_cleanup_workbench.png)


1. Set up evo workbench by moving vacuum filter into place and loading 10 uL tips into the correct carrier (as shown above)
2. Load 10mL of buffer into trough marked `E` above. Load 10 mL of water into trough marked `W` above. 
3. Place 10K omega filter plate on the vacuum manifold, with a 96 deep well plate below to collect waste. 
4. Create experiment and run `WIP_PCRCleanup_SKA` script in Momentum
5. Load the source and destination plates in the appropriate nest specified in the experiment creation


###NOTES: 
- Needs a water test 