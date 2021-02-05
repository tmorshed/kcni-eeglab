# kcni-eeglab
Description and records of operations at KCNI EEG Lab (CAMH room 624)

### To add to wiki:



1. Clear disinfection guidelines
   - When patients are in

       <span style="text-decoration:underline;">and</span>

   - When we’re alone
2. Transfer a bulk of this very document to the:
   - Project board
   - Wiki


### To do:
1. *Run cables*
2. Conduct Auditory Oddball task w. events communicated via serial port
3. Write experimental guidelines
4. Inventory
5. Initialise all the sensors
6. GitHub repo


### Request CAMH to do:
1. Provide lab coats and laundry schedule
2. Clean the Faraday Cage:
    1. Very dusty
    2. Fix broken floor
3. Allocate head wash station (preferably nextdoor)
4. Put up the hanger for drying the electrodes
5. Bleach the sink. It’s been oxidised


### Purchase list: 

What e.g., wet wipes        | Status (Y/N)
|:--------------------------|--------:|
Gloves                      |       Y
Tags                        |       N
Organic/biohaz waste basket |       N
Scissors                    |       N
Normal saline               |       N
Screwdrivers                |       N



# 


# Setup


### Before setting up:
*   Get one set of electrodes from the hanger. (CMS/DRL  +   A-B-...-H)
    *   Make sure it's dry. If it still has moisture, use paper towels to dry it.
    *   Connect them to the pertinent ports.
        *   EEG connects to the top wide slots and CMS/DRL has a PS-like port in front.
*   Get a cap from the hanger.
    *   Make sure it is dry. If it still has moisture, do not try to dry it. Wait until it is dry. Do not use a heat gun/hair dryer. Do not sun-dry.


### Wearables:



*   Wear the cap on the patient. It should not be too loose nor should it be too tight. Let the patient breathe but extend the elastic fabric a bit.
*   Apply the gel
    *   Take some gel from the tube using the bent syringe.
    *   Deploy the gel in the selected electrode holes on the cap. (swirl the syringe while emptying to increase the surface area)
    *   Continue deploying until a small bit overflows out of the hole.
*   Connect each EEG electrode right after you have applied the gel.
*   Connect the CMS/DRL electrodes
    *   **CMS**: Connect to an <span style="text-decoration:underline;">empty EEG electrode location</span>, if not available, tape it to the <span style="text-decoration:underline;">forehead</span> using a hypo-allergenic tape.
    *   **DRL**: This would be perfectly connected to the right leg, but the bony structures on the right arm or hand are okay too. The elbow or the [styloid process of the ulnar bone](https://i.pinimg.com/originals/7c/75/e1/7c75e1ce5db96a0fc71104eae3a97bf1.png) (the bump on the side of your wrist) are great choices. If none are possible, put the electrode right below the temporomandibular joint (TMJ) on the sharp edge of the mandible.


### Initialise the ADC:
*   Press the power button to turn on.


### Acquisition
*   Open Actiview from $PATH. 
*   Un-check the 8EXG items from the left panel.


### After use:
*   Wash the electrodes or clean with a damp cloth/tissue (nothing other than water). Dry gently with a paper towel.
*   Hang the electrodes to dry (there is a hanger for electrodes, in the X location)
*   Sanitise the cap using the spray provided. Hang cap to dry as well


## Notes:
*   **The conductive gel contains parabens. **Must ensure that participants don’t have paraben allergies.
*   Add 8 EXG has to be un-checked
*   Electrodes should not touch each other or metal. EVER.
*   The electrodes are only sensitive when they are in equilibrium.
    *   Put all electrodes in a bucket of non-sterile normal saline every week for ~5 minutes to _reduce _the electrochemical cells and bring the electrodes back to equilibrium.
