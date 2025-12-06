# PACKAGING EVOLUTION: FROM Basics to 3D Integration
## PROTECTED ENV to REAL WORLD

1. All the components of the various chips on an SOC to all work together from the manufacturing to the real world usage
     a. Preparing die for the real world
     b. It requires Protection of semiconductor devices on die (ex: corrosion, moisture and physical damage)
     c. Connection of die to other dies (Ex: Ball Grid Array Package)
<img width="572" height="221" alt="image" src="https://github.com/user-attachments/assets/b5fa76ab-8e84-45e9-8597-468444344c24" />

## Packaging and Testing Industry

1. Integrated Device Manufacturer (IDM): They do the design, fabricate and package too
2. Fabless: These are Semiconductor design-centric (Ex: Qualcomm, NVidia, AMD, Apple, etc.)
3. Foundry: These only focus on Wafer manufacturing by developing technolgy (Ex: TSMC, Global Foundries, SAMSUNG, etc.)
4. Outsourced Semiconductor Assembly and Test(OSAT): They focus on packaging and testing semiconductors and wafers (Ex: ASE, Amkor, JCET, etc.)


## Package requirements and foundational package types
### Requirements:
1. Connection (PIN Count)
2. Thermal dissipation: Material and its thermal dissipation based on the real world use case
3. Form Factor: Depends on the board and its requirement to be able to operate
4. Reliability/ Durability: Material reliability
5. Cost

### Package structure
<img width="520" height="188" alt="image" src="https://github.com/user-attachments/assets/f6bc7454-8e76-4c5c-9d0b-2629e4868c71" />
     1. Die-to_carrier interconnections is done first
     2. Then Carrier to Board interconnections
     3. Then modling is applied over the package

#### Types
##### Through-hole mounting
1. It goes through a hole where it is used. Like DIP
2. Another one is PGA where grid of holes are layed out for the pins to sit

##### Surface mount Technology
1. QFN/ QFP
2. PBGA: Plastic Ball grid array
3. LGA: Land Grid Array
4. CSP: Chip scale package. Package size is close to Chip size. This is because of the board layout footprint constraints
5. MCM: Multi Chip Module
6. PoP: Package on Package, seen on memories
7. CoWoS

##### OPtions for carrier
1. Leadframe, laminate, plastic, ceramic (for high temps), organic RDL, silicon, glass
##### Options for Interconnects
1. Wirebond: using wires over the mold
2. Flip-Chip: using bumps/ solder on the underside to make the connections
