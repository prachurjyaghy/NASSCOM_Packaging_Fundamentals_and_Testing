# PACKAGING EVOLUTION: From Basics to 3D Integration
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
7. CoWoS: Chip on Waffer on Substrate

#### Options for carrier
1. Leadframe, laminate, plastic, ceramic (for high temps), organic RDL, silicon, glass
#### Options for Interconnects
1. Wirebond: using wires over the mold
2. Flip-Chip: using bumps/ solder on the underside to make the connections

### Anatomy of Packages
#### Leadframe
<img width="351" height="420" alt="image" src="https://github.com/user-attachments/assets/d2598bd5-0cfb-4819-823f-11c4e55b1a53" />

All these are on a lead frame to make the metal connections

#### Laminate
<img width="261" height="422" alt="image" src="https://github.com/user-attachments/assets/333d2ae0-7064-4f7a-83aa-a55756dc061e" />

#### Advanced package substrates
<img width="267" height="417" alt="image" src="https://github.com/user-attachments/assets/213961ca-1d00-455d-8c89-e4782608ce82" />

1. Die in 2D sits directly on the substrate
2. In 2.1D, an RDL Layer is added
3. In 2.5D, an Si Interposer which is very close to the 3D

<img width="1422" height="415" alt="image" src="https://github.com/user-attachments/assets/4af7dcb3-9d15-4643-be05-503f7bff975c" />


# From Wafer to Package: Assembly and Manufacturing Essentials
## Supply Chain and Facilities

1. EDA tools, foundary PDKs --> Design House --> IC Design (GDSII)
2. Silicon Wafers, Equipment Gaes, Chemicals, Materials --> Wafer Fabrication --> Wafer with fabricated ICs
3. Substrates, tools, materials, chemicals, Lids --> Package Assembly and Test --> Individual ICs assembled in a package and tested
4. PCBs, Tools, Materials --> Board Assembly and Test --> Many packages assembled on a board and tested
5. Components, Tools --> Product Assembly and Test --> Final Product

### Package Manufacturing Unit
1. Process ATMP: Assembly, Testing, Marking and Packaging. can be done in-house
2. Organization: OSAT: Outsourced Semiconductor Assembly and Test
<img width="893" height="286" alt="image" src="https://github.com/user-attachments/assets/d10bf726-12e3-4154-9212-eb53a6aaa0da" />

### Wafer Pre-Preparation - Grinding and Dicing
#### Activities inside the cleanroom area
     1. Wafer Preparation Area (ISO class 7)
          a. Incoming wafer carried 
          b. Wafer Inspection 
          c. Wafer Front Tape Lamination (as back part is going to be used 
          d. Wafer Backside Grinding 
          e. Tape fram mounting to backside
          f. Two step Wafer dicing (laser grooving + Blade dicing)
     2. Wirebond Packaging
          a. Start with good dies from the diced waffer
          b. Die attach: Epoxy as die attach film to attach with the substrate in uniform pattern to avoid voids
          
<img width="449" height="197" alt="image" src="https://github.com/user-attachments/assets/71ba351d-dd30-47bd-8d65-5ec7536ac141" />

          c. Curing: To mechanically pack with the substrate
          d. Wire Bonding:
               i. EPFO spark
               ii. Free air ball
               iii. Ball bond: using ultrasound + normal force with heat
               iv. Move the capillary tip upwards and makes a loop
               v. It then comes to the packaging substrate pad
               vi. It then pressed to make the bond and once the cresend bond is done, cut it off
               vii. Lead with the wire trail and do the EPO spark and do it all over again
               viii. Gold is the premium one and other materials are considered as per cost

<img width="230" height="138" alt="image" src="https://github.com/user-attachments/assets/d68650c7-d879-42e6-a86f-59b98e25eb6e" />

<img width="457" height="251" alt="image" src="https://github.com/user-attachments/assets/1ffd3dc0-b139-4e50-9af5-bca08b5cc092" />

          e. Molding (Transfer): Passng the modling compund from one side and flowing through a channel
<img width="282" height="100" alt="image" src="https://github.com/user-attachments/assets/42b9d46c-f493-48eb-8683-335c10ff8f7c" />

          f. Marking (Laser)
<img width="217" height="81" alt="image" src="https://github.com/user-attachments/assets/70d782f7-ef59-4347-b79b-0fbf71296d17" />

          g. Singulation (dicing blade)
<img width="213" height="325" alt="image" src="https://github.com/user-attachments/assets/104beb23-d48a-4c98-826b-36e66427178a" />

     
     3. Flip Chip Packaging
<img width="218" height="147" alt="image" src="https://github.com/user-attachments/assets/10d78897-415e-4ab3-b318-2c5806c0561c" />

     Balls/ bumps od the die where thepitch is much lower than the PGA packages. Then the bumps are taken through the mold. After dicing there are no bumps
          a. Bump formation on Si. Top metal later and opening is made with dielectric on the sides. Then underball metalization is done to put the Solder on top of it by reflow process. This reflow is to make the metalization strong on the die
<img width="496" height="153" alt="image" src="https://github.com/user-attachments/assets/92e54e74-738f-40fb-b5fb-62837f292d76" />

          b. Flip the die, solder balls are seen. Then put this die on a substrate with flux on top of the bond pad to protect it.
<img width="170" height="150" alt="image" src="https://github.com/user-attachments/assets/6a7819fc-cdde-40b0-91a1-b03f2e34c76c" />

          c. Then pressure and heat is applied to make the join
<img width="114" height="115" alt="image" src="https://github.com/user-attachments/assets/93f91d18-ee48-4999-8e50-a0b4db2e0b76" />

          d. Fluz cleaning is required as bonds are done
<img width="140" height="106" alt="image" src="https://github.com/user-attachments/assets/39ae1b52-15cf-42ec-bccf-4a50ce368b48" />

          e. Package is of a different material with one CTE, while Si is of differnt CTE (Coefficient of Thermal Expantion, as a result, they tend to have some stress. So underfill is used to mitigate the stress
<img width="115" height="145" alt="image" src="https://github.com/user-attachments/assets/3db48df4-3073-4f8e-8556-1bfe7fb00f34" />

          f. 
