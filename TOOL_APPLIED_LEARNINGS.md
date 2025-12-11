# Thermal Simulation of Semiconductor Packages with ANSYS

## Getting to know ANSYS Electronics Desktop

    1. Install the free version as the steps provided in the lab manual to install the ANSYS Electronics Desktop application
    2. Once loaded check the topside for the tool designers. SInce we are doing the thermal simulation Icepak is required.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7c8f5438-bdef-4453-91a3-53563355e2a8" />

    3. Click on the IcePak and it will load a blank project to work on
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ff2ab822-402f-437d-a746-d280e32bcaf5" />

    4. The list inside the project has all the elements. Liek the 3D components, boundary conditions and monitor the areas. It is the flow of the design top to bottom of any design
<img width="383" height="396" alt="image" src="https://github.com/user-attachments/assets/741ce533-0b61-4d99-805f-7eefd1a522e5" />

    5. Different geometry and can be used to create different shapes for the design on the tool
    6. Will use an inbuilt package from the toolkit. Here will use the flipchip BGA
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/95f8345c-3403-44cf-9cb1-f5a4c9b523ae" />

## Setting up Flip-Chip BGA Package

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d1028bec-6beb-4047-9401-6819dc0d7c5b" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d2572b53-2d61-4963-9ba9-66b8f31b7f92" />

    1. 1 W power depends on the frequency on how much the chip can withstand
    2. Heatsink may or may not be there based on the cost

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c60409cb-3b3f-46ca-9ab1-c1b88b7cc861" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/52e79959-de8f-4be9-a920-12b6e71fa456" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5eccd079-c02a-48ba-aeca-4b33e9aca02b" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/91633037-7eec-4b8a-9b2a-ea4e64367cca" />

### Check the different layers of the package
#### Substrate
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/94a3d7cc-b390-479f-a6fd-692d63f6da60" />

#### Underfill
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7e013ec2-4f65-49b9-8155-c1a382f66c14" />

#### VIA Material
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/53230859-98d9-402f-8eb8-5f05a078dc40" />

#### SI Typical Die
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/522c470e-568a-4ad9-ad38-c07e1e8d7d7e" />

        NOTE: With more advanced packaging, there will be multiple dies on top of each other (Multiple heterogenous layers) with which the thermal conditions also arise

### Check other types of packages
#### PBGA (Wirebond)
<img width="1408" height="801" alt="image" src="https://github.com/user-attachments/assets/710a748f-69ad-4853-baf4-9f201522709e" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fd18db3e-d3a7-4fe6-916c-d7bd2525980c" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f31c2609-7a75-4ca2-a261-d5c29f312592" />


#### QFN
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6f5cbfbe-8a00-4769-9c80-9760944bbf0c" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7b42a4b7-8aa5-4ba9-ac98-c5588791a13a" />


### Material Definations and Thermal Power Sources

        1. Go to the Model to check the data
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/613ef26e-9620-43d0-91c0-268fb964ae6d" />

        2. Now the thermal condition to put throught the die
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a672f285-06aa-457a-81f6-4de54c444644" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b288af27-f996-49c4-aff2-7fbc8ccb45de" />

        3. Define the source using temperature as the thermal condition. It could throw a warning, we can remove the other condition for thermal and only keep one
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/515e5d3b-1569-4452-a779-267ecd308051" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d42afd55-c43a-496c-9e0d-4d5dcf686913" />

        4. Add a monitor on the substrate, die and underfill for temperature
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7c8d1fd9-eb5a-411f-85ea-d8d95d0e0320" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e64d8f36-d5b9-4975-b3f6-ce41ee611ae1" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dc2bda40-ea9d-4a61-ba5a-11746519e63d" />


### Meshing and Running the Thermal Analysis for Flip-Chip

        1. Generate Mesh will start, if project is not saved it will ask for it. It will run in local machine. 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0b30820b-b832-4154-9c85-118b4441b99d" />

        2. Shows number of elements andvarious properties
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bea45da5-245d-46f8-a371-837bd9c0fdc1" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/089decb4-eb66-4ccc-b265-d7bc94440bdb" />

        3. Mesh is a more important parameter to check the accurate structure. We can select and redo if required
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5ab6f025-704f-4548-a99b-4e516c8d498c" />

        4. Add an analysis setup
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/41fab826-72d3-4222-98ea-fb03e07b77d2" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/075f28a6-54ae-446f-acbc-5b52a12ed50c" />

        5. Now do validation and all green means it is good to go. It will not show the boundary conditions, only once we analyse will find out
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8ada4cb6-f1d0-42ac-a0bf-e025e4f6eb8b" />

        6. If we get warning for underfill not having mesh, we can add it too
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/019626b5-f7a7-4a47-a213-0345791167fd" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/104d8ee4-0ae7-4313-b3e9-24ea1566e792" />

        7. Run the mesh again for the whole as we generated mesh for a region only, validation should pass
        8. After this Click on Analyze All
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0efde475-adf1-4c1e-90da-c693a56bd44e" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f1bdd6db-5262-4e00-988a-2c9b755384b6" />

        9. Once normal completion message is shown, select the package and go to plot fields.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ce59ce03-71d2-47c5-b2ee-060ca5639005" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f881660a-fe4d-4345-8cb0-affb2cee6dbf" />

        10. Select the fields and click on Done
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/213ebb52-9723-45af-a86d-9d6309910f4b" />

        11. The thermal level is showing the conditions based on the temperature plot
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/99d50385-6b16-4fdb-b13d-70de5d0b73b7" />

        12. These output will change based on the conditions as per requirement

#### Checking QFN for Meshing and Thermal Analysis

    Tried the QFN and PBGA for wirebond, could not figure out why the intersect is happening. Might have missed something
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c8d1b50e-5bba-4b02-a1ab-ae09ef4aea1c" />


# Building a Semicon Package from Scratch
## Package cross-section modeling in ANSYS

        1. Previously we loaded the package directly with the flow. Will now build every step from scratch
        2. Objective is to start from die to the molding of the package
        3. Previously we went through the thermal analysis, but it is more than that. We need to do the electrical analysis too for creating a design

### Creating the Die and Substrate 
        1. The Die size will be based on the final range as per requirement which will be determined after the waffer tinning is done and it moves ahead in the process (Ex: like the High Band width, which has stacking)
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6da5d5a2-7082-4372-9db9-d26b5df9c279" />

        2. After we give the die size, will thicken the sheet as below
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7aa152f9-0850-48c3-9cd9-b872145b601e" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ac99feec-eb67-4225-bd7c-abb9285c96eb" />

        3. Update the property of the rectangle created with the Name and Material
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7e37bf02-fd83-4024-a7ff-f4ebbcc2cf2b" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b4786553-1b9c-47a9-b819-4accd0c2d22e" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f5ed7d79-99ea-42a3-b603-fc1c816531f6" />

        4. Create another rectangle for the substrate and update the size values
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/87299ae0-e6b4-4ef9-9898-064239e28e88" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e566ac2b-b53e-4f7d-a1a6-9fc7dd2f1dcd" />

        5. Now do the thicken sheet process of 0.5mm for the substrate
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d2ff60c9-9eac-4620-9b9f-249471447e40" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e0de13b2-6a95-4cb2-8dc2-e67c8ce3c04d" />

        6. As substrate should not cover the die, will change the thickness to -0.5mm
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5d1e6dde-f7fd-4312-99a7-136e312e842d" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/da9e58a7-59db-41cb-a5de-16f0cc3d9925" />

        7. As we have seen in the previous packages, the die will not directly sit on top of the substrate an is incorrect


### Adding Die Attach Material and Bond Pads
        1. Edit the substrate rectangle
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6b026dc5-803f-4614-8267-7995e70b6b2a" />

        2. Create a space in between for the die attach
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/25398edb-6b2f-4f46-9a63-5c26e03937fe" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/306ff812-4d31-480a-871e-a78a3a5c67cc" />

        3. Add a die attach material. Create a rectangle over the die and make the changes
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a614a915-2702-4e4d-8cc0-0d78804bd3d9" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/48430aca-8584-4bc2-9d60-a6835c1ab4ca" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/abfa182e-9c2d-4f26-b5d7-fae3a4899d04" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9e938a6d-ba07-487f-825f-05cc2de6563c" />

        4. Create bonds between two bond pads of the substrate and on the die. 
        5. Add the die position from the centre as below and thicken the sheet
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3d7f9d44-73e1-419d-8794-9a3f13515e5f" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5f40fc60-7a87-42ce-84fd-434cb5b3f9a8" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dcd3e8f6-2a36-4a37-9f98-bec3446718f3" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9fe523d3-bbba-494e-bce8-ea0a69fe567c" />

        6. Now create bonds on the substrate and thicken sheet
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/22762d5f-86c6-40b9-bd63-ba9651e41ee9" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/13fbfb7e-f183-442d-a6a7-6e95f9bc8386" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e31a4f29-b3b7-419e-8190-20d3d64d9aa2" />


### Wire Bond Creation and Material Assignment
        1. Go to the Draw option of bondwire. Start and end with the middle of the bond. There are different weight of the wires. Will take the deafult on here. If the height needs to be higher then we can coose accordingly
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f2fdcf3f-ed77-402c-a621-bfa7c5cfe5ae" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2968ae28-d3fa-4c60-8a58-5d5376acec54" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/aef1e83a-6c36-4e14-b1df-476a218448f0" />

        2. Following this method, we can complete the bond over all the die and substrate
        3. Assign material for the bondwire and has to be ductile to be able to bend and be connected to the substrate
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0b0a9d76-2e73-435d-8f04-03462478d4d5" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/85c5ec58-758f-438d-bebe-89c4e828355e" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/13f5bd48-3689-4258-a8f6-791f571da60e" />

        4. If in search of bondwire for gold type, all the performance levels are mentioned


### Applying Mold Compound and Finalizing the Package Model
        1. Create a rectangle over the substrate and thicken sheet of 1.2mm and update the material to Epoxy
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3d06ef46-43e8-4ef4-928a-794233bfcaf3" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1430b887-01cc-44f4-a848-c616c2f11af0" />

        2. Now the height of the mold compund is higher that it is more than wire bond because when the laser marking happens there is enough headroom of effecting the wirebond
        3. After this the electrical and analysis can be done on these packages as similar to the built in packages in the icepak tool
