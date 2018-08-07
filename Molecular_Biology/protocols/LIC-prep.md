##Module 2: 96-well LIC Preparation 

###SUMMARY: 
This protocol will generate 2x 96-well plates of PCR products ready for LIC. One will have a poly-C tail, the other will have a poly-G tail 

###TIMING: Less than 1 day (2-3 hours) 

###MATERIALS: 
- Master Mix (30 uL/rxn) [Master Mixes will be in 1.5mL aliquots) 
   + 4 uL/rxn T4 buffer to each well
   + 4 uL/rxn 25 mM **dCTP** or **dGTP** 
   + 2 uL/rxn 100 mM DTT
   + 0.4 uL/rxn T4 polymerase enzyme
   + 19.6 uL/rxn nuclease-free ddH2O
- 96-well plate of cleaned up PCR product (6uL/rxn) 
- Scripts
  - Evo: `WIP_SKA_LIC_prep`, `WIP_SKA_LIC_incubation`
  - Momentum: `WIP_SKA_LIC_prep`

###INPUT/OUTPUT: 
- Input: a cleaned up 96-well plate of PCR products, tube of dCTP master mix, tube of dGTP master mix  
- Output: 2 sealed LIC-ready PCR products, to be used as source plates for LIC annealing 

###BUFFERS: 
- None

###EQUIPMENT: 
- EVO
- Centrifuge on automation desk 
- Plateloc 
- INHECO incubators

###Protocol: 

![Image of workbench](https://github.com/choderalab/lab-protocols/blob/molecular_biology/Molecular_Biology/protocols/img/LIC_prep_deck.png)

1. Make two aliquots of `dCTP Master Mix` and two aliquots of `dGTP Master Mix` on ice 
2. Transfer master mixes ependorf block on decklayout as above 
3. Load source cleaned up PCR product plate and two empty 96-well plates into nest specified when creating the experiment 
4. Run experiment based on `WIP_SKA_LIC_prep` in momentum 

###NOTES: 
 
