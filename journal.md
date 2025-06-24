very chopped journal

Creator: Abhinav A. 
Time Spent- 20+ hours across almost exactly a month


Note: this isnt going to be that in depth, but js know i actually did work and iterate on this


Background: The idea started near the end of may, and I began the project officially on May 26th. I actually started locking in more recently than that, but there was at least some progress being made throughout the whole time period. I love 3d printing a lot, and i really didnt want to spend a lot of money on a whole filament dryer, and it felt cool to make my own.

CAD is by far the thing im most competent in, when it comes to the design process, and thats why one of the design considerations that I had in mind was that the project should have  as little pcb design or coding as possible, and just make something I was comfortable with. my other projects were designed against this philosphy, but just for this project i wanted to make something with the skills i enjoy using.

May 26th- spent around an hour drawing different ideas and deciding how the spools should have  fit inside the whole box (1 hour)

May 28th- decided to use the design from creality's filament dryer, with a hinge from the bottom (lloking back at this, it was a stupid idea and i changed it), also spent about another hour just researching parts (total- 2 hrs)

May 29th- spent about an hour deciding on what electronics to use, settled on using a timer module/temp sensor that could do all the work, also made the decision to add blower fans to the inside to evenly spread heat and make sure the spool was consistenly heated.I worked on the cad more too which took up more time but wasnt anything noteworthy(3 hours)
 
may 30-31- procrastination

june 1st-7th- only did hackpad, so i kinda had to put a pause in this (no work done :sob:) 

June 8th- found the specific electronics that i wanted (listed in the BOM), and spent at leaast an hour trying to find everything on GrabCAD (2 hrs)

June 9th- had friends over hell no im not doing work we stay procrastinating

june 10th- finally had a decent looking 3d model of the whole thing, realized a pivot wont work so I switched to hex bearings that we use in robotics. I also found the single most important resource that i could possibly find: a video by another guy who tried the same. His parts were the same as mine so a lot of my stuff is based on his. (3 hrs)

June 11th- realized i suck at electronics and attempted to make a wiring diagram and also realized that i should be using a different timer module (jz-801, not xyj02). I also used a lot of that guy's wiring diagram because I realized that if i were in control of this, at least 1 explosion/fire would happen. (2 hrs)

Wiring diagram:
![alt text](<Screenshot 2025-06-24 171912.png>) 

June 13th- Fixed minor issues with the cad, also came across this weird interference that was causing the hood to not close properly. After trying about 5 different solutions, ranging from a gap that would fit the exact shape of the spool to make it fit, to making the hood bigger, and also extending the base. Eventually i founnd out that i am an idiot, and there was space for the spool in the first place and if I just moved it back slightly why do i do this to myself im still mad (4 hrs)

June 4th- started accounting for the fact that i couldnt print everything on my P1S (256mm cubed print volume, so about 10 inches), so the entire day was just slightly resizing everything so I could print everything. 
things I did: 
    -Changed the base width from 11 inches to 10 inches 
    -spit the hood into 2 peices, so that I could keep that extra length while also not have 100g of support material, while also making the decision to make the two peices to be held together with heatset inserts, using the dimensions that hackpad gave us.
(3 hrs)

june 17th, locked in and finished everything, finalized BOM
Some minor/major stuff
-imported all the components from grabcad (took a stupid amount of time), and created mounting holes/placed them on the thing
-added holes for electrical components to wire
-added a vent for the blower fan and then immediately realized that i didnt want it, so i removed it
-realized that the hinge is buggeed because of some interference, so I added a fillet that should make the hinge not be dumb
 
(3 hrs)
Before:
![alt text](<Screenshot 2025-06-24 175420.png>) 
After:
![alt text](<Screenshot 2025-06-24 175544.png>)

Final product i think: ![alt text](<Screenshot 2025-06-17 123134.png>)