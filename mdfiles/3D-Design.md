# 3D  Design
## *Scope of work:* 
To design a 3D model for holding the Micromiller bits
The Diameter of the Micromiller bit is 3mm and height is 30mm

## *3D Design Model:*
A small block ( Length: 16mm; Width: 30mm; Height:25mm) containing 3 cylindrical cut of radius 1.8mm and height 25mm that can properly accommodate 3 Micromiller bits

![bit holder](/images/bit-holder.jpg)
## 3D--Designing Process: Using FreeCad
Open new file in Free cad and draw cube and cylinder as per the given below dimensions:
Cube: l=16mm; w=30mm; height=25mm;
Cylinder1: r=1.8mm; height=30mm
Placement: x=8; y=5; z=5;
Cylinder2: r=1.8mm; height=30mm
Placement: x=8; y=15; z=5;
Cylinder3: r=1.8mm; height=30mm
Placement: x=8; y=25; z=5;

Now, apply boolean operation Difference on Cube and cylinder
apply boolean operation Difference on Cut0 and cylinder1
apply boolean operation difference on Cut1 and cylinder2

# *Output:* #

![bit holder 3D print](/images/bit-holder-3d.jpg)

The file will be saved in .FCStd format. Export to .stl format.   

Now open the file using 3DXWOX

Save the file with extension .gcode, Export to media drive.

Go to the 3D printer, mount the drive and print.

[Back](/mdfiles/Fab-Lab.md)  ***(Please click  Back to go to Fab-lab)***
