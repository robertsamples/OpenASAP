# OpenASAP
An Open Source 3D printed Atmospheric Solids Analysis Probe

<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/7d19281d-1c90-4b61-9ca2-1b4b1b4b8423" width="520" height="720">

## Material selection
### Resin
Any MSLA or SLA resin intended for high temperature applications can be used according to the manufacturer’s instructions. Sirayatech Sculpt Ultra and Formlabs resins have been verified to work. The probe body should be printed in the upright orientation due to the design of the internal structure.

### FDM
An FDM printer may be used with a material with an appropriately high heat deflection temperature such as nylon, polycarbonate, or annealed PLA according to the manufacturer’s instructions. ABS should not be used as depolymerization and release of styrene may cause high MS background, although this has not been proven. Annealed carbon fiber PLA is suggested as the preffered material as it has been proven to withstand the temperatures of the MS inlet for long periods of time, does not release volatile organic compounds in our experience, and is easy to print with an affordable hardened steel nozzle on an unenclosed printer. We suggest use of a 0.4 mm nozzle with standard voron settings (3-4 perimeters, 40% infill) and organic/tree supports inside the button channel.
<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/197a75ac-ccc2-4b5a-8a1f-ba135408e48a)

If carbon fiber PLA is selected part annealing may be done in a laboratory oven, however we annealed parts using the printer heat bed. This was done by placing the parts on a 1 cm bed of gyroid infill printed with 3 walls and no top layers to allow airflow, covering the parts with a box made of 1 cm packing foam in which the 3D printer was shipped, and heating the bed to 100 °C for 30 minutes. Parts were allowed to cool slowly to below the glass transition temperature of approximately 50 °C before being removed from the chamber. Corrections for any contraction and expansion of printed parts were done by printing a 20 mm calibration cube and measuring the X, Y, and Z dimensions before and after annealing. A 1% contraction in X and Y dimensions and 2% expansion in Z dimension were found and thus parts were scaled prior to slicing to compensate for these modifications. Scaling requirements may differ depending on material selection and printing parameters.

<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/38d38846-dd4c-410f-991d-b8750417b125" style="width:30%;">
<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/99535c9b-78d5-4dfd-a4bb-98336707af2b" style="width:30%;">

 
## Postprocessing and assembly

Remove support material if applicable, removal of supports from the inside of the probe channel carefully using forceps or dental picks. Anneal if using carbon fiber PLA, Verify parts fit together properly by inserting the button into the button hole and use the wrench to ensure the button can be turned ¼ turn clockwise to align guide cylinders on the side of the button with the travel channel. Remove the button afterwards

<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/f3d696b8-6178-42bc-9a69-8b657d79b248" style="width:20%;">
<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/29f64920-976d-405f-9405-6fe23aa92b9e" style="width:30%;">

Disassemble a retractable ballpoint pen or obtain a 4.25 x 18 mm or similar compression spring. The spring shown we used was obtained from a PaperMate InkJoy 300RT pen. The exact dimensions are not critical provided the probe button can reach the depth required to turn into the travel channel. A spring that is longer may be cut to length.

Confirm the spring length, which allows the probe button to be locked into the travel channel. To do this, the spring is placed in the recess of the button and the spring spacer is placed around the spring to prevent it from bending in the button hole. The button is reinserted into the probe as before. If it does not bottom out and turn, try a different pen, or cut the spring to length. Complete the final reassembly of the probe. Although not required,we suggest using a drop of cyanoacrylate glue around the spring spacer and recess in the probe button to secure these to the spring.

<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/e8b44b69-61f1-42ad-a77f-ae1d908e9156" style="width:30%;">
<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/2ef0fe74-f212-4226-a582-9ceea040f346" style="width:30%;">

## Installation

Unscrew the four M2 screws securing the outer housing plate screws on the left side and top of the source housing, as well as the x alignment adjustment nut.

<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/28a9e5d7-45fd-46a9-81a6-9d98d8d15c23" style="width:30%;">

Remove the M4 socket cap screw securing the source housing window side flange.

<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/38c79f14-8626-4b93-a362-912df3de7281" style="width:30%;">

Remove the flange and replace the acrylic window with printed port, then reassemble flange and housing plates.

<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/c89591da-4f2c-4ccf-8411-6d9fdc7d1637" style="width:30%;">
<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/b6b33542-cb8e-4cee-aefd-3d35e126a956" style="width:30%;">

Install the IonMax source onto the MS interface and confirm that the tip of the capillary aligns with the MS inlet.

<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/4f5dfd6d-bf00-440b-a13d-2d2c0f4e3570" style="width:30%;">
<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/000ee571-0eef-45c0-9173-e9cb394c5471" style="width:30%;">

## Use



### Safety
When operating the openASAP system, it is important to avoid contact with heated or electrically charged source components as they can reach high voltages and temperatures. We recommend always putting the mass spectrometer in standby mode when handling the source. Additionally, an electrically insulating material, such as glass, should be used for the sample collecting component of the probe.

### Instrument Configuration
Before using the openASAP system, the APCI source and corona discharge needle must be properly installed in the mass spectrometer housing following the manufacturer's instructions. For Thermo instruments, this involves inserting the APCI source and connecting the LEMO electrical connectors and fittings for auxiliary and sheath gas flow. The corona discharge needle should be inserted into the needle hole and the needle grub screw tightened to secure it. High voltage is supplied through a coaxial LEMO connection on the top of the source housing.

The APCI settings may need to be adjusted based on the analyte and instrument being used. For Thermo instruments, we recommend using the following settings as a starting point: Probe position C, a heater temperature of 325 °C, 5 μA current, and a sheath and auxiliary gas flow rate of 30 and 10 arbitrary units, respectively.

### Sampling

[![Watch the video](_Video of a 30 second acquisition with a previous vesion of the OpenASAP probe_)](https://github.com/robertsamples/OpenASAP/assets/64489385/f3cfc7f3-7278-4a68-9012-97aa2ae5c67d)
_Video of a 30 second acquisition with a previous vesion of the OpenASAP probe_

To load a capillary into the ASAP probe, depress the button and insert the capillary open end first until it reaches the maximum depth.

<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/324dfba4-84a0-4651-bef1-40b2bd0052d1" style="width:30%;">

 Collect the sample on the probe tip and then insert it into the APCI source after starting a continuous or set duration acquisition. 

<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/4dca186e-e499-4a8c-9a9f-2fd67232a645" style="width:30%;">

<img src="https://github.com/robertsamples/OpenASAP/assets/64489385/3ffe3aaa-1c70-4100-af71-5c9d20a50be3" style="width:15%;">
