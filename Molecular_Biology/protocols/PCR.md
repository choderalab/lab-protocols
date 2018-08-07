##Module 1: 96-well PCR protocol

###SUMMARY: 
This protocol will generate a 96-well plate of unique PCR products, that will serve as the source for the upcoming PCR cleanup protocol. This protocol uses 20uL reaction volumes 

###TIMING: Less than 1 day (2-3 hours) 

###MATERIALS: 
- 2 4ti-110 96-well, round bottom plates with 5 uM normalized primers (50-100uL in each well) 
  - 12 forward primers 
  - 8 reverse primers 
- 450 uL of 1.25ng/uL template DNA (plasmid) in a microfuge tube 
- 1.25mL Master Mix in a microfuge tube 
  - [Phusion High-Fidelity PCR Master Mix with HF Buffer](https://www.thermofisher.com/order/catalog/product/F531S) 
- 384-well LC480 PCR plate 
- 2.5 boxes of 10uL conductive hanging tips 
- Scripts
  - Evo: `WIP_PCRsetup_SKA_AXR`, `WIP_SKA_precool` 
  - Momentum: `WIP_PCR_SKA`

###INPUT/OUTPUT: 
- Input: a plate with forward primers, a plate with reverse primers, an eppendorf tube of template DNA plasmid 
- Output: a sealed 96-well plate of PCR product

###BUFFERS: 
- None

###EQUIPMENT: 
- EVO
- LC480
- Centrifuge on automation desk 
- Plateloc 
- INHECO incubator 

###Protocol: 
![Image of workbench](https://github.com/choderalab/lab-protocols/blob/molecular_biology/Molecular_Biology/protocols/img/PCR_Workbench.png)

1. Run EVO script`WIP_SKA_precool` directly to precool metal microfuge tube adaptor for about 15-25 minute. Abort script when plate is around 4C
2. Place Master Mix in well A1 (red) in metal microfuge tube adaptor, and template DNA in B1 (blue) 
3. Place 394-well PCR plate in the next you want to specify in the `step 5`
4. Put forward primer (purple) and reverse primer (orange) plates directly into carrier 
5. Run experiment based on Momentum script `WIP_PCR_SKA`. 
    - make sure to specify the nest that you put the 384-well plate in at `step 3`

####PCR reaction Specifics: 
- 3 uL of 5uM forward primer
- 3 uL of 5uM reverse primer
- 4 uL of 1.25ng/uL template DNA (plasmid) 
- 10 uL of Master Mix 

###NOTES: 
- Still having trouble with the labeling format, but the barcode should have all of the relevant data
- Will switch over to SBS tips when they arrive 
