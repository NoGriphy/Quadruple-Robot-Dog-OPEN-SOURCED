## ( QUADRUPED ROBOT DOG - INSPIRED BY Unitree ): OPEN-SOURCED ##

As you may have read the repository title, this is my FIRST an open-sourced robot dog project. If I have missed any resources, please message me on Reddit **( https://www.reddit.com/user/Severe_Package6618/ - Display name is StepPhase-01 )**

<p align="center">
  <img src="RD_Image_References/Reddit_PFP.jpg" width="400">
  <br>
  <em>Reddit Account</em>
</p>

---

### ( Introduction ):
In order for this project to work, I really recommend you using a 3D printer that has a dimension of 260 x 260 x 300 mm^3 (the one I'm using is Creality). If you don't have one - it's fine - try to adjust the component on your printing platform **diagonally** until the part fits perfectly without crossing the boundary. 

This project will utilise 12 servos/motors, **DS3235 (a torque of 35kg/cm) | 180-degrees**, you can purchase it from Amazon, AliExpress, or any websites that are completely safe. The reason why we need DS3235 is that we want to have a strong torque that would lift at least 1 kilogram (KG) of body weight. Even the servos can easily this weight, we also need to ensure that when adding electronics (e.g., batteries, cables, microcontroller, AI vision, etc), the DS3235 servos are still be able to lift them without struggling. 

To extract the servos' full potential, we have to use 6.8 V - 7.4V (volts) 2200mAh (or higher current) battery (note: this would add additional weight to the robot, and we need to be constantly cautious about the total weight while making this project). Otherwise, if you have, let's say, a 5V 15A power supply, the servos won't be able to exert all its torque power **(~21 out of 35kg/cm)**, meaning it would be slightly tedious to conduct the heavy-lifting. 

---

### ( What Do We Need for the Quadruple Robot Dog: Resource Requirements? ):
- A 6.8V - 7.4V 20A power supply or battery
- ESP32 (Any standard ESP-32. I'm using Devkit v1)
- Raspberry Pi 2W (For Python code compilation)
- LiPo Battery 2200mAh 7.4V 50C (with a built-in XT60 cable)
- UBEC Voltage Regulator (Note: Find the product that is able to decrease a **7.4V power to 6V**) 
- Hiwonder LSC-32 32-Channel Controller (Alternative: PCA9685 driver board can be acceptable if you have solutions to prevent current spike that is higher than 10 Amps)
- 12 DS3235 Servos
- CAD parts/components (Robot Dog) - **You can access and download them through the 'RD_CAD' folder.**
- A camera for AI vision (Note: If you have a camera that is specialized for AI, it would be perfect as long as it does NOT connecting with a USB cable.)
- 2M 6-25mm screws (Note: It is recommended to purchase a kit that contains all sizes. If you already have them, ignore this note)
- Arduino IDE (C++)
- ROS2 (Robot Operating System) - **OPTIONAL** (note: please ignore this requirement if you don't know how to code ROS2 programs; it is optional for serial communications and nodes distribution. I will post a standard Python code.)

---

## ( Step 1 - Building the Robot Dog by Using CAD Parts ): 
Please check the '**RD_Building_Instruction**' page if you're unsure how to assemble the robot components. 
**HERE IS THE COMPLETED VIEW FOR THIS PROJECT (SP-01). Download the file, and open it on your CAD software (e.g., Autodesk Fusion, Solidwork, etc): https://drive.google.com/file/d/1cRC2gju0PUmeT0fz4Unme0vgVkuIykVL/view?usp=sharing**

<p align="center">
  <img src="RD_Image_References/RD_Complete_Design.jpg" width="500">
  <br>
  <em>Build Reference: R.D. View</em>
</p>

---







