# keyboardv2

A second version of my original keyboard I designed during Hackpad V2. This keyboard follows a slight variation of the ANSI-75 Layout and is coded with QMK and and customizable with VIAL.
The keyboard deviates from my original design by implementing RGB and embracing the plate-less design. The keyboard has per-key RGB thanks to the SK6812-Mini-e Inverted LED.
![image](https://github.com/user-attachments/assets/a9986fd9-15ea-4a51-91de-f6ab6a484443)

## Keyboard in VIAL
![image](https://github.com/user-attachments/assets/befaa6c8-d0e0-4115-9e05-6f89d63b9ac0)

## Keyboard Case
![image](https://github.com/user-attachments/assets/2bb38367-7e88-4d97-ad61-50bc3008b817)

## Section of keyboard routing near the microcontroller
![image](https://github.com/user-attachments/assets/b91a9971-25eb-4397-9776-d0de8851b002)

## KLE viewer of the keyboard (ANSI-75)
![image](https://github.com/user-attachments/assets/114e993f-5b88-4c41-b6dc-0942ea61358d)

## PCB Render
![image](https://github.com/user-attachments/assets/28c11136-58be-442b-ba71-7750f75a48d7)

## All together!
![image](https://github.com/user-attachments/assets/98af1268-53a8-41a9-8298-e5d024aac4c7)


# Note about the case V2 design
The new design was designed differently from the rest of the keyboard for Blueprint. It fixes some of my issues with the previous design, mainly the size and the thickness. This design is a bit more fragile, but unless you absolutely destroy your keyboard at 400WPM, it should hold. The USB port design is also slightly tighter, but unless you are using a USB cable thicker than the MCU itself, you should be fine. The other changes are the screw holes having chamfering to prevent snapping off under pressure, and the tolerances being increased to be 3D printed better.

# Bill of Materials (for highway)
| Item                                                          | Cost(INR) | Cost(USD) |
|---------------------------------------------------------------|-----------|-----------|
| PCBA                                                          | 6460      | 75        |
| Switches                                                      | 2800      | 33        |
| Keycaps                                                       | 1300      | 15        |
| Rotary Encoder, Threaded Inserts, M3x6 Screws, Adhesive Grips | 1500      | 18        |
| Stabilizers                                                   | 1000      | 13        |
| Case (Printing Legion)                                        | N/A       | N/A       |
| **Total**                                                     | **12060** | **154**   |
