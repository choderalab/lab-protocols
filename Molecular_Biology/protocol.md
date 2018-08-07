#Protocols (WIP)

###PCR setup
* source: source 96-well plates of 5 uM normalized primers (one forward plate, one reverse plate)
* source: ice-cold 1.25 mL master mix (4C?)
* source: 450 uL of 1.25 ng/uL DNA plasmid 

* destination: 384-well PCR plate at 4C, using 20  uL reaction volumes 
* dispense 10 uL master mix into each well of PCR plate [96-well dispense, 10 uL disposable tips]
* transfer 3 uL forward primer from each source well to each destination well [96-well transfer, 10 uL disposable tips]
* transfer 3 uL reverse primer from each source well to each destination well [96-well transfer, 10 uL disposable tips]
* transfer 4 uL of plasmid from source to each destination well [96-well dispense, 10 uL disposable tips]

* move PCR plate off of Evo 
* seal plate with adhesive film or foil to prepare for PCR
* spin down [for mixing]
* place in PCR machine and run PCR program
* spin down
* remove adhesive film or foil (alternatively: pierce film or foil to remove samples)

###PCR purification with vacuum filter plate:
* source: PCR plate
* source: reservoir of nuclease-free ddH2O
* source: reservoir of resuspension RB buffer
* destination: Thermo Scientific NucleoFast 96 PCR plate on vacuum manifold
* destination: 96-well collection plate
* transfer 50 uL PCR product to NucleoFast 96 PCR plate [96-well transfer]
* vacuum filter for 10 min until completely dry
* transfer 50 uL nuclease-free ddH2O to NuceloFast 96 plate [96-well dispense]
* vacuum filter for 10 min until completely dry
* transfer 50 uL resuspension RB buffer and pipette up/down for 10 mixing cycles [96-well dispense/mixing]
* transfer 50 uL to collection plate [96-well transfer]

or PCR purification with magnetic affinity beads (uses magnetic bead station)

###96-well ligation-independent cloning

PCR setup

PCR reaction [may need to be manual]

PCR clean-up purification (to eliminate free dNTPs)

####LIC insert treatment
* prepare master mix in Epi tube on thermal block at 4C
   + 2 uL/rxn T4 buffer to each well
   + 2 uL/rxn 25 mM dCTP
   + 1 uL/rxn 100 mM DTT
   + 0.2 uL/rxn T4 polymerase enzyme
   + 9.8 uL/rxn nuclease-free ddH2O
* transfer 15 uL of master mix to each well of destination plate [96-well dispense]
* transfer 5 uL purified PCR product from each source well to destination plate [96-well transfer]
* incubate at 22C for 40 min
* heat-denature at 75C for 20 min

####LIC Plasmid treatment 
* Coming soon!

####LIC reaction:
* add 14 uL nuclease-free ddH2O [96-well dispense]
* transfer 3 uL LIC vector reaction from Epi tube on thermal block into destination plate [96-well dispense]
* transfer 3 uL LIC insert reaction into destination plate [96-well transfer]
* incubate 30 min RT to anneal

###Transformation:
* thaw competent cells at 4C
* dispense 50 uL cells into each well of 96-well growth plate [96-well dispense]
* dispense 1.7 uL BME into each well [96-well dispense]
* shaking plate gently for 10 min at 4C
* transfer 6 uL from each DonI digest reaction well into destination wells [96-well transfer]
* incubate at 4C for 30 min
* heat-shock by transferring to 42C heat block for 45 s [duration critical for maximum efficiency]
* inclubate at 4C for 2 min
* add 500 uL pre-warmed growth medium and incubate at 37C for 1h with shaking 225-250 RPM

####Competent cells:
MultiShot TOP10 Chemically Competent E. coli ($3047 / 5 96-wellplates)
http://products.invitrogen.com/ivgn/product/C40005
Transformation efficiency > 10^8

###Clone Selection
Alternative to manual plating for individual clone selection [384-well protocol from http://dx.doi.org/10.2144/000113514]:
* source: transformed culture
* destination: transparent 96-well plate, two transparent 384-well plates
* dilute tranformed culture 1:860 into transparent 96-well plate
* culture in plate reader at 37C with automated real-time OD600 monitoring to determine timing of reaching OD600 of 0.1, from which CFU is computed
* perform additional dilutions with LB media in plate if necessary to synchronize cultures
* when OD600 reaches 0.2 (4x10^6 cells/mL), dilute by factor of 5x10^5 to obtain concentration of 8 viable cells/mL
* from each of 96 source wells, transfer 30 uL aliquots to 4 wells on each of two 384-well plates (25% wells should contain a single cell)
* culture 384-well plates overnight at 37C with shaking (in enclosed incubator or with lid on)
* read OD600 of 384-well plates in plate reader to determine which wells contain cells

###96-well plasmid preps

*Still working on this!!!*

This protocol is modeled after the Millipore 96-well plasmid prep kit [http://www.millipore.com/catalogue/module/c7481]

####Culture growth:
* dispense 1 mL antibiotic-containing LB media from sterile reservoir into sterile 96-well deep block culture plate
* inocculate each well with small volume of cells
* cover plate (lid or foil with holes?)
* grow overnight at 37C with shaking at 320 RPM (in enclosed incubator or with lid on)

####Plasmid purification:
* assemble vacuum manifold with 96-well "plasmid" filter plate inside manifold and 96-well "clearing" filter plate atop manifold
* centrifuge deep-well plate at 1500g for 7 min
* remove supernatant from wells
* dispense 150 uL resuspension solution into each well from resuspension reservoir
* resuspend cells by pipetting and shaking
* dispense 150 uL cell lysis solution into each well from lysis reservoir (ideally while shaking)
* shake for 2 min
* transfer 200 uL lysate from the bottom of each deep well into the clearing plate on vacuum manifold
* apply 8 mmHg (230 bar, 203 torr) vacuum to clearing plate for 5 min
* discard clearing plate and plate plasmid plate (previously inside manifold) atop manifold
* apply 24 mmHg (812.7 mbar, 609.6 torr) vacuum to plasmid plate for 7 min, discarding filtrate
* dispense 200 uL wash solution into each well from wash reservoir
* apply 24 mmHg (812.7 mbar, 609.6 torr) vacuum to plasmid plate for 7 min, discarding filtrate
* dispense 50 uL storage solution into each well from storage solution reservoir
* shake plasmid plate for 5 min
* transfer 50 uL from plasmid plate to 96-well plate for storage

###Plasmids from Addgene:
* `N Terminal fusion vectors` - https://www.addgene.org/browse/article/4179/
* `C terminal fusion vectors` - https://www.addgene.org/browse/article/4192/
