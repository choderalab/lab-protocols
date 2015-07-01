# How to use the Auto-ITC200

* Make sure your plate is sealed using one of the plastic seals. For now, we are uncertain whether it is okay to use the pierceable seals. (TODO: Verify this with Antonio Luz.)
* Book time on the machine at https://ppms.rockefeller.edu/ . You will need to have received training before this option will be made available to you.
* It is no longer allowed to plugin USB sticks directly into the machine connected to the ITC machine. We can use the computer in the room next door for USB or internet access and use this shared folder:

On the ITC computer desktop:  
![ITC computer](https://raw.githubusercontent.com/choderalab/choderalab/master/wiki_images/usbcomputer.png?token=ADyyA18a5qwf-iYnkryhVQIPcizCX4J7ks5U-eBHwA%3D%3D)

On the USB computer desktop:  
![USB computer](https://raw.githubusercontent.com/choderalab/choderalab/master/wiki_images/usbcomp2.png?token=ADyyAxRDYAfD23mmY5ulpzY70Tl8R8YVks5U-eB5wA%3D%3D)

If the computer is locked, use the HTSRC user, and password `screening`


## At the ITC
* Write down date, name and experiment details in the logbook.
* Make sure to label plate 'Chodera lab'. Write down phone number and possibly experiment details.
* Check the system to make sure it is idle. You can use the display on the machine to see the status.

If someone else is still running, you can try and contact them. If you can't reach them within 15 minutes, you are allowed to abort their run using the abort button on the machine. You may want to ensure that your protocol involves a thorough cleaning step at the beginning.

There are two main programs on the computer that you need to be aware of:

1. The MicroCal iTC200 software  controls the calorimeter.

2. MicroCal Auto-iTC200 software controls the Autosampler and communicates with the MicroCal iTC200 software to control the MicroCal iTC200 instrument. 

Less importantly: 

* Origin, for data display

Use Auto-iTC200 to:
* Set tray temperature
Go to the System tab, set tray temperature at 1 degree below experiment. 
* Using switch on the physical machine, open tray.
* If any plates are left in the machine, leave them on the table next to the machine.
* Wipe any moisture out of the tray, leave it open for a short while so it can dry.
Go to iTC200 and:
* Set jacket temp to experiment temperature. 

If it was previously set differently, this could take a little while.
Meanwhile:

Go to the room 2 doors down the hallway and
* Spin the ITC plate in the plate centrifuge.
* DONT FORGET to BALANCE OUT THE CENTRIFUGE. You can use an extra (dirty) plate for this.
* Use 1000 rpm. Start using green arrow. Once it reaches 1000, press stop.

After you are done with centrifuging the plate, return to the machine.
* Put into tray, slot 1 (back left) with A1 as the back left cell.
* Close the tray using the button on the machine.

Back to the computer:
* Go to Auto-iTC 200 -> experiments
* Set the data path(c:\ITC200\data\chodera, make a new folder with the date).
* Give a name to the log file, which will be placed in this folder.

Next:
* Import spreadsheet from the shared folder.
* Check the spreadsheet to make sure that all experiments have methods assigned to them and concentrations are correct. 
* Press validate, which will show how much methanol, water, detergent and waste volumes are needed.
* Check the bottles at the side of the machine and see if any need refilling or emptying.
* Waste goes down the drain in the back room
* There should be water near the sink. Methanol should be in the cabinet, as well as detergent.
* Check the pressure on the valve(s) of the gas canisters, the gauge should be at the line.

If everything seems to be in order:
* Hit the run button in the Auto-iTC200 software.

After a short initialization, your protocol will get started.
### Stopping/aborting a run
If you need to end a run, there are two options.

* Stop, which finishes the current experiment before quitting. 
* Abort, which stops mid-experiment.

You can select these either on the machine display, or in the Auto-iTC200 software. When you press stop, please be aware that you might not be able to take the tray out immediately. 

### Disposal of plates

Often, people leave their ITC plates in the room for someone else to dispose. However, we generally just carry them back to our lab and dispose of them in our waste. 


