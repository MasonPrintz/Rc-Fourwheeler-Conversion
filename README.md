# Rc-Fourwheeler-Conversion
Please read this. Clearly my reveiwer note was not read. This is a kit to make a real full size fourwheeler remote controlled. A cheap ali express servo will not turn full sized tires, it requires way to much force. And the controller i chose is a very cheap one most crontollers go for hundreds of dollars.this one is low end while still being safe. And please actually pay attention and keep this in mind. i keep saying this is a full sized fourwheeler but everyone keeps thinking its some small scale toy. its a real fourwheeler with a actual engine. so no cheap ali express stuff will turn it.


This will be a description of the parts i chose and why. and the general idea of how i plan to make this work.

The linear actuators is for steering here a picture of the part. (and note i chose this one, because i need 200m and it needs allot of power to be able to turn the wheels this vehichal is not power steering so it has to do all the work. also it has position feedback which is needed for this project a $10 aliexpress one wont cut it) <img width="1919" height="915" alt="Screenshot 2025-12-22 125009" src="https://github.com/user-attachments/assets/af8721da-1a9e-4d2d-b58c-f8a5d3967bca" />



secondly throttle. high power servo. im gonna 3d print a mount on the hanndle bar that the servo slides into. and i can use the servo to move the throttle.
<img width="1180" height="233" alt="Screenshot 2025-12-10 162032" src="https://github.com/user-attachments/assets/f4c6aff6-c575-4c89-bf34-2b5622721ab4" />


Braking i added 2 linear actuators to the list im gonna test weither or not one can turn it or not if only one can im gonna use the other one to drive the foot break. if it takes both linear actuators i will either run no brakes or i will add on another servo when i save up the money.

The controll board I will use a esp 32 to run the project do to its faster run speed.
<img width="1180" height="207" alt="1" src="https://github.com/user-attachments/assets/bf074e99-e024-490e-a74c-3dfa1883af58" />


The generall idea for the code my plan is to take from the receiver on the remote and read it and log it as integers such as (steer) Throttle%) than use the position feed back from the actuators to use greater than and less than equations to drive the motors either way

than from the board the motor drivers will put out the correct voltage to the actuators

the step down converters will be used to drop the 12v four wheeler battery to 5v for the esp32 

<img width="1182" height="228" alt="Screenshot 2025-12-10 162022" src="https://github.com/user-attachments/assets/ee77c428-09ea-41b7-a11c-12d1e72595d8" />

and as for the remote i chose a flysky there a great mix if cheap but still high quality and it has 10 channels for communications reason. If you chose a cheaper remote they are very bad and have safety risks. and It would require very delicate and expensive components to make your own and managing radio waves is very hard i would have to make a receiver and transmittor.
<img width="1182" height="221" alt="2" src="https://github.com/user-attachments/assets/6a0fe3f3-5489-4f8e-8ec2-c855af09a605" />

spare motor drivers incase the esp32s and the ones that come with the actuators dont get along
<img width="1182" height="211" alt="3" src="https://github.com/user-attachments/assets/beea0c87-648b-48ba-90bd-a61fc377352f" />

transistors used to turn off and one the fourwheeler engine 
<img width="1180" height="223" alt="4" src="https://github.com/user-attachments/assets/dd74cccf-3eeb-4981-9d7a-e0509ae707f0" />
