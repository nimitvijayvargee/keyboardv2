---
title: "Nimit's Keyboard V2"
author: "Nimit Vijayvargee"
description: "A QMK supporting keyboard built around the RP2040"
created_at: "2025-05-22"
---

# May 22
Time Spent: 2 Hours <br>
Made a schematic of the keyboard and also laid out all the components into the PCB editor. Did research on the parts and components and am preparing for the Bill of Materials.
![image](https://github.com/user-attachments/assets/2bfc4952-ecf7-43d0-bbd8-a5e2e2b371a8)
![image](https://github.com/user-attachments/assets/c519edf1-19a3-451f-8437-d094cd4ecabb)
![image](https://github.com/user-attachments/assets/02cf0898-5c04-47fe-bf69-45a2c7c3d7f0)


# May 26
Time Spent: 1 Hour <br>
Re-routing the PCB so that I can include a ground plane. Also improved the schematic by flipping LEDs in alternate rows to decrease routing issues.
![image](https://github.com/user-attachments/assets/b807c907-4a2c-418e-a2e5-638701fd6a0b)
![image](https://github.com/user-attachments/assets/41aec6c1-79fd-4c7f-9dea-11d88603817b)


# May 27 - June 5th
Time Spent: 6 Hours <br>
Polishing the PCB. Also added decoupling resistors according to the PCB Spec. Fixed electrical issues and began setting up my QMK environment to work on the firmware.
Compared prices and conducted research on components across manufacturers. Finalized PCBA and component settings in JLCPCB
![image](https://github.com/user-attachments/assets/9f430366-019c-418c-8241-b8f223c23ae0)
![image](https://github.com/user-attachments/assets/fbf86d83-12aa-47f0-900c-018b943784f9)

# June 6th - June 11th
Time Spent: 3 Hours <br>
Completed PCB, created KLE layout (for future porting to VIAL) and setup configs for QMK. Also made the Case sketch
![image](https://github.com/user-attachments/assets/07bc01bf-ac24-491d-af63-58112a3cf7e1)
![image](https://github.com/user-attachments/assets/16003fce-9efe-4107-aaeb-0c661cb58836)


# June 12th 
Time Spent: 2 Hours <br>
Completed case (extrusion), compared prices and created BOM list. Case is left to export. After this, I will only need to finish setting up the QMK definitions to work with the LEDs and the rotary encoders.
![image](https://github.com/user-attachments/assets/ab1204d3-6e9b-4b53-8d96-15958b275e2c)


# June 13th
Time Spent: 1 Hour <br>
Exported Case files into printable 3D models. Commited local project files from KiCad and Fusion to github.
Also started working on polishing QMK to work with the LEDs.


# June 14th
Time Spent: 2 Hour <br>
Took a break from QMK and started working on the VIAL configs instead. Successfully loaded keyboard into VIAL editor.
Readied the project for submission!
![image](https://github.com/user-attachments/assets/2176f7c5-4bc1-44d3-b3c2-f6717521ecc8)

# June 18th - June 19th
Time Spent: 1 Hour <br>
Added silkscreen art, worked on QMK configs.
![image](https://github.com/user-attachments/assets/12a224a1-d5a0-49b2-8f60-df78a339d182)

# July 4th - July 5th
Time Spent: 8 Hours <br>
The PCBs arrived! I spent more than 4 hours each day to solder them, test connections and resolder them! My soldering skills weren't that good and left a lot to be desired but it ended up working out! I also a burnt a pad for one of the switches (oops) so I had to solder a copper wire between that pad and the diode but oops!
![image](https://github.com/user-attachments/assets/e1cf34dd-e4c6-45d0-9fd1-07f93653a251)
![image](https://github.com/user-attachments/assets/cd633f5e-076a-41dd-b36c-7f01b007cc20)


# July 5th - July 7th
Time Spent: 7 Hours <br>
Getting QMK to compile with the RGB Features! It took a lot of trial and error and it was very annoying to get it working. I also worked on getting vial worked out at the same time! It was kind of difficult since I am more used to python but adding all my features in info.json worked without any actual code so that was kind of nice.
I also had to do a bit of troubleshooting on the solder joints because they were bugging the matrix by shorting ground.
![image](https://github.com/user-attachments/assets/904b2a05-60f2-4a3e-9909-25495975fe56)

