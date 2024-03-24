# belt_lock
by [MikeYankeeOscarBeta](https://github.com/MikeYankeeOscarBeta/) (VoronDesign Discord: #MikeyMike V2.5796, Voron Toolchangers Discord: MikeyMike - Github: [MikeYankeeOscarBeta](https://github.com/MikeYankeeOscarBeta/StealthChanger))

## Description
A solution for mounting 9mm and 6mm 2mgt/2gt GT2/GT3 belts to mgn12 carriage with M2-SHCS or 2mm pin. Designed to handle high belt tensions.
Versions for both inverted and normal belts.

## Features
- Belt Pin.
- Does not clamp the belt against the carriage.
- For monolith (inverted belts) it will not change the belt path (keeps the belt path perfectly straight).
- For normal belt direction there will be a ~0.8mm y offset.
- Keeps within the confines of the carriage (unless using the external clamps).
- builds 6mm out in y
- Tested with 15kg static load per belt

## BOM
| Part                        | Amount    | Description                                                      |
|-----------------------------|-----------|------------------------------------------------------------------|
| M2x25mm SHCS or 2x25mm PIN  | 4         |  Pin for more strength, m2 screw for ease of use                 |

## Print Instructions
Print it upright, the strength comes from the layer direction. printing it in the incorrect orientation will result in a weaker part.  
Use support (make sure your supports are tuned to the point where you're able to remove them carefully without breaking the part).  
40%+ infill  
4 perimitters  
4 top and bottom layers  
0.2mm layer height  (or smaller)
0.4mm nozzle (or smaller)
enable filling gaps


### BOM - m2_belt_clamp
| Part                        | Amount    | Description                                                      |
|-----------------------------|-----------|------------------------------------------------------------------|
| m2x4x3.5 Heatset Nut         | 6        |  4mm deep, m2 threads, 3.5mm outer diameter                      |
| m2x10mm SHCS Screw           | 6        |  m2x12 SHCS also works ok                                        |

### BOM - m3_BeefyBeltClamp
| Part                        | Amount    | Description                                                      |
|-----------------------------|-----------|------------------------------------------------------------------|
| m3 hexnut                   | 6        |                                                                   |
| m3x8mm SHCS Screw           | 6        | m3x12 SHCS also works                                             |

## Support
Raise issues via github or contact via discord.
Voron Toolchangers Discord "Belt Lock" thread: https://discord.com/channels/1119433664799965186/1218280403870289990