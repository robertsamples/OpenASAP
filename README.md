
# OpenASAP
An Open Source 3D printed Atmospheric Solids Analysis Probe

<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/7d19281d-1c90-4b61-9ca2-1b4b1b4b8423" width="520" height="720">

## Material selection
### Resin
Any MSLA or SLA resin intended for high temperature applications can be used according to the manufacturer’s instructions. Sirayatech Sculpt Ultra and Formlabs resins have been verified to work. The probe body should be printed in the upright orientation due to the design of the internal structure.

### FDM
An FDM printer may be used with a material with an appropriately high heat deflection temperature such as nylon, polycarbonate, or annealed PLA according to the manufacturer’s instructions. ABS should not be used as depolymerization and release of styrene may cause high MS background, although this has not been proven. Annealed carbon fiber PLA is suggested as the preffered material as it has been proven to withstand the temperatures of the MS inlet for long periods of time, does not release volatile organic compounds in our experience, and is easy to print with an affordable hardened steel nozzle on an unenclosed printer. We suggest use of a 0.4 mm nozzle with standard voron settings (3-4 perimeters, 40% infill) and organic/tree supports inside the button channel.

If carbon fiber PLA is selected part annealing may be done in a laboratory oven, however we annealed parts using the printer heat bed. This was done by placing the parts on a 1 cm bed of gyroid infill printed with 3 walls and no top layers to allow airflow, covering the parts with a box made of 1 cm packing foam in which the 3D printer was shipped, and heating the bed to 100 °C for 30 minutes. Parts were allowed to cool slowly to below the glass transition temperature of approximately 50 °C before being removed from the chamber. Corrections for any contraction and expansion of printed parts were done by printing a 20 mm calibration cube and measuring the X, Y, and Z dimensions before and after annealing. A 1% contraction in X and Y dimensions and 2% expansion in Z dimension were found and thus parts were scaled prior to slicing to compensate for these modifications. Scaling requirements may differ depending on material selection and printing parameters.
 
## Postprocessing and assembly

Remove support material if applicable, removal of supports from the inside of the probe channel carefully using forceps or dental picks. Anneal if using carbon fiber PLA, Verify parts fit together properly by inserting the button into the button hole and use the wrench to ensure the button can be turned ¼ turn clockwise to align guide cylinders on the side of the button with the travel channel. Remove the button afterwards

Disassemble a retractable ballpoint pen or obtain a 4.25 x 18 mm or similar compression spring. The spring shown we used was obtained from a PaperMate InkJoy 300RT pen. The exact dimensions are not critical provided the probe button can reach the depth required to turn into the travel channel. A spring that is longer may be cut to length.
 
Confirm the spring length, which allows the probe button to be locked into the travel channel. To do this, the spring is placed in the recess of the button and the spring spacer is placed around the spring to prevent it from bending in the button hole. The button is reinserted into the probe as before. If it does not bottom out and turn, try a different pen, or cut the spring to length. Complete the final reassembly of the probe. Although not required,we suggest using a drop of cyanoacrylate glue around the spring spacer and recess in the probe button to secure these to the spring.

## Installation

Unscrew the four M2 screws securing the outer housing plate screws on the left side and top of the source housing, as well as the x alignment adjustment nut. Remove the M4 socket cap screw securing the source housing window side flange.

Remove the flange and replace the acrylic window with printed port, then reassemble flange and housing plates.

Install the IonMax source onto the MS interface and confirm that the tip of the capillary aligns with the MS inlet.

