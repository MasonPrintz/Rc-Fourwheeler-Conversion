# Rc-Fourwheeler-Conversion
A kit i made to Rc swap my old honda recon


This will be a description of the parts i chose and why. and the general idea of how i plan to make this work.

First off The Steering method. The Few people ive seen do this use steepers but i want this four wheeler still usable normaly. so i spent a long time thinking about it. and i sall a camper going down the road and i thought about what they use to open the stretch out tarps and after some research. i found they use linear actuators. So i thought but how would i mount them and use them to steer it. than i thought what if i attached them to the tie rods (steering linkage) if i use the 2 mounts it comes with i can weld them to the middle of the frame than to the tie rods. and if i want to drive the four wheeler normal i just pop the pin outt of the mounting brackets and it drives normal.

secondly throttle. high power servo. im gonna 3d print a mount on the hanndle bar that the servo slides into. and i can use the servo to move the throttl <img width="1919" height="915" alt="Screenshot 2025-12-22 125009" src="https://github.com/user-attachments/assets/4747e5bf-f1aa-40f9-b407-4ac137ad3fff" />
e. 

Braking i added 2 linear actuators to the list im gonna test weither or not one can turn it or not if only one can im gonna use the other one to drive the foot break. if it takes both linear actuators i will either run no brakes or i will add on another servo when i save up the money.

The controll board I will use a esp 32 to run the project do to its faster run speed.

The generall idea for the code my plan is to take from the receiver on the remote and read it and log it as integers such as (steer) Throttle%) than use the position feed back from the actuators to use greater than and less than equations to drive the motors either way

than from the board the motor drivers will put out the correct voltage to the actuators

the step down converters will be used to drop the 12v four wheeler battery to 5v for the esp32 
