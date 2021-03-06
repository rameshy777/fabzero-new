

#  Project   Presentation
   
![Project Slide](/images/projectslide.png)

### Aim of the Project:  
The main aim of the project is to develop an iBELL, intelligent BELL. 
Intelligence means "to fool others". If A fools B, then A is intelligent than B.   It is not always true that "All intelligent are not fools".
Also, it is  not  true  that " All fools  are not intelligent". 

In  our day today life, we  always try  to play  an intelligent  role.  But  still sometimes once a while we may be fooled by others. We can act intelligently  on  those  which we see, or on  those that happen in front of us.  But, it is challenging to play an intelligent role over the events that happens behind us. 

So, this thought has  motivated us to develop an intelligent system called "iBELL" which helps us to be intelligent  even behind our eye  sight. 

### Procedure/Description:  
iBELL  is an Intelligent BELL. It is a normal electronic BELL programed to behave intelligent role.
Whenever anybody misuses or  tries to fool, it goes to "freezing mode"  and gets  activated after specified time.
ie, If you press the buzzer and hold for more time,  immediately without causing nuisance to the owner.  It automatically goes  to "Freeze Mode". Also,  if anybody repeatedly presses the buzzer  it enters to "Freeze Mode". Like this,  several cases of events  are worked out  and  programed to behave  intelligently.

### Hardware Requirement / Electronic Components  used:    
Resistors---500 ohm --2nos.  
Resistors---10 ohm  --2nos.  
LED---------2nos.. Green, Blue  
Micro Controller--ATtiny 44  --1 no.  
Capacitor--------1Micro Farad --1no.  
Switch Button--1no.  
ISP header-----1no.  
Speaker/Buzzer---------1no.  
Resistor--50ohm--2nos.  
Mosfet----------1no. 


### Software Requirement:  
Markdown,  Git, KiCad,  Visual Studio Code,  Freecad,  Inscape,  gimp,  Cura,  3DWOX,  Arduino,   AVR  Code

### PCB Design: 

The  Circuit design, Schematic  diagram,  extraction  of  trace  and  cut   files  are discussed in  detail    in the  Fablab menu under  PCB  design and cutting  is done  using the Micro miller  which is  described     in detail  in  the  Fablab menu under Micro miller.  


#### iBELL Circuit Design:    
![Project Slide](/images/iBell-circuit-diag.jpg)   
#### iBELL Schematic Diagram:     
![Project Slide](/images/iBell-schematic-layout.jpg) 
#### MOSFET Circuit 3d-View:        
![Project Slide](/images/buzzer-schema-3d.png) 
#### iBELL Trace, cut:      

![Project Slide](/images/tr-cu.jpg) 

![Project Slide](/images/trace-cut.jpg) 
![Project Slide](/images/buzzer_trace.png)

### Implementation:  

Now, the components are soldered as  per the PCB  design  on  the  circuit board.
We have arrived  at  two  circuit boards, one  is  the micro controller circuit,  the  other  is the  MOSFET  connected  to the  speaker.  We have also used additional 2 nos.of 50ohm  resistors connected in parallel to suppress the  generated heat. Oscilloscope  was used to check the  working functionality of the speaker.
![iBell-miller](/images/mc-header.jpeg)  

![iBell-PCB](/images/ibell-pcb.jpg)

#### PCB  board after soldering:    
![iBELL Soldered](/images/iBell-soldered.jpg) 

We have used Oscilloscope to check the working condition of Speaker. 
![MOSFET  ](/images/oscilloscope.jpg)

All the circuit boards and components are interconnected and iBELL is ready.

![iBell](/images/iBell.jpeg)

### Coding:  
AVR  program  was written as per our  requirement. Through the programmer, using Arduino, we have compiled and successfully loaded the AVR code in to the micro controller to work intelligently as  per  our requirements.
#### AVR Code:        
![iBELL AVR CODE ](/images/avr-code-last.png) 

Given below is the case-1 arduino code. 

![iBELL Arduino CODE Case-1 ](/images/case1-arduino-code.png)


### Testing:  
The basic model of iBELL is  tested and is working fine without generating any heat. 

### Moulding/Casing:   
#### 3D designed  Outer Case  for iBELL:  ####    
Free Cad was used to design the  3D  outer   Case for  iBell.      

3D design Outer casing for iBELL
![iBELL casing 3d-design ](/images/ibell-casing-3ddesign.png)   
 
 
![iBELL 3d-design-casing ](/images/ibell-3dmoulding.jpg)  

#### 3D Printing for  iBELL  Outer Case:  ####  
 The  3d iBELL outer  Case design was then loaded to 3D printer. After 28 minutes, we are ready with the outer Casing for iBELL.    
   
 Now we  have packed all the  iBELL components  inside the 3D case  and  the bottom is  covered and was  tightly packed using the heating glue gun.

 #### Vinyl Name  sticker for  iBELL :  ####    
 iBELL name sticker was designed using the inscape  and through the use of Vinyl cutter, we got a beautiful name sticker,  which  was  stuck at both sides of the iBELL.  For more  description  on  3D design and 3D printing  go  back to Fablab menu under  3D  Design,  3D Printing.  

 3D printed  Outer Casing for iBELL with Vinyl name Sticker    

   ![iBELL Casing ](/images/iBELL-casing.jpg)

### Final Output/Result:     
The Basic iBELL model is working fine. When we press the switch, light glows and speaker blows sound.  
Below given is the project video. Please click to download.

![click to download the Project video](/images/iBELL-video.mp4)


### Future Enhancement:  
iBELL has vast scope for future enhancement.   
Intelligence can  be fed  to iBELL in  the form of uploading program one by one on case basis,  so as  to  behave more  intelligently  with  added  features/functionalities.  
Case  1,  if switch is pressed and held for more time, iBELL  goes to freezing  mode (inactive  mode)  and after sometime automatically turns  to active   mode.   
Case  2,  if switch  is  pressed on and  off frequently  within the  particular  time interval, again it goes to freezing mode and turns to active mode after some  time.   
Case  1 & 2 events happen when a  known person is trying to fool us. In this circumstance,  iBELL acts intelligently by going to  inactive  mode temporarily.       
Case  3,  iBELL can be enhanced to work like  an Access Control system. List  of  known users face   images and finger prints can  be saved  in the  database.  A  camera and  finger  print capturing devices can be  attached to iBELL.  When any person presses  the  switch, immediately it matches the face  and finger  prints with the stored database and based on the access permissions it automatically signals the access door  to lock or unlock. This feature will be very helpful for persons living  in the same family (children/husband/wife/father/mother/sister/brother). They need not wait for  the family person to wake up  and come to  open the door.    
Case  4,  Even we can program iBELL to sound the names of the person standing behind the door.   
Case  5,  In sensitive areas  (Border areas, LoC) iBELL can be attached to the CCTV camera, so that it alarms loudly  and sends  MMS messages / videos automatically to the control room, if anyone tries to  enter with unauthorized / heavy weapons /materials.    
Like this we can keep on loading iBELL with updated programs for latest features and requirements.    

### End of Fabzero iBELL Project Presentation.               Thankyou all for your kind support.
![The End](/images/theend.jpg)





#### Click [Back](/mdfiles/pcb-design.md)
#### Click [Fablab-Menu](/mdfiles/Fab-Lab.md)
#### Click [Next](/mdfiles/Thankyou.md)