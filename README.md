# Smart-VR-Glasses
My Academic Project - Smart Glasses

#throwback_april_2024

https://github.com/Anandhu-Sudha/Smart-VR-Glasses/blob/2a4d9cf7c6ddfa500b1b19f0197566ddcb278201/pictures/final.jpg
https://github.com/Anandhu-Sudha/Smart-VR-Glasses/blob/2a4d9cf7c6ddfa500b1b19f0197566ddcb278201/pictures/final2.jpg

The Project idea submission started in month of September 2023, we were a team of 3. So after going back and forth on different areas and ideas, we landed on this. This has a great resemblance to Apple's i-vision but the i-vision is launched in feb 2024. Our plan was to make something like the Iron man's "E.D.I.T.H" Glasses.

It's planned and executed in 6 months of time, so it's no where near to any market products which may has been in the R&D for years.

Our main objective was to add : 
- real-time object detection & if required object description.
- Smart phone connectivity 
- and should be useful for people with disability
  (for blind people- scenario interpretation, deaf people-live transcription)

Although this was our objective , due to constraints we were only able to achieve our 2 objectives , ie. Object & face detection, smartphone connectivity:

Construction & Components:
--------------------------

Hardware:
Raspberry pi 5 (8gb ram)
USB Webcam
5 inch TFT display
12v li-ion battery pack
5v li-ion battery pack

Software:
Raspbian OS
python, Open-CV, KDE Connect.


Selecting the Platform:
-----------------------
At the initial stage we were planning to use the Nvidia Jetson nano since it requires real-time image processing, but due to the high cost we had to settle down to raspberry pi-5. Which was also not bad as expected, it handled really well.

The second main component was the display unit. Like the same , had something different in my mind. to import dual displays from Chinese website like ali-express and ebay.That plan also had to change due to import issue. Finally bought a 5 inch TFT display(which was poor in terms of pixel density) used for automotive purposes. took the display out the frame and inserted it into a FPV goggle frame my friend had. ( Thanks to @akhilsamvarghese ).

Finally, the camera setup. i bought the pi camera for this project but sadly some interfacing issue with the pi, the Pi5 was recently launched so the camera lacked some support, So instead we decided to go with the USB Web camera.

Assembling:
-----------

The display unit can be worn because it's an FPV goggle frame. for the rest of the components i had to use my Sony Camera Bag, and connecting wires are routed through an electrical hose. 

The video out from the pi can't be directly connected to the screen since the TFT doesn't offer any HDMI input. so we used an HDMI to AV converter.

The raspberry pi, HDMI-AV converter, Battery pack for the Display and pi, all this packed in the camera bag.

