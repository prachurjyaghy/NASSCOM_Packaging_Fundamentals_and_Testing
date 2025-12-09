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
