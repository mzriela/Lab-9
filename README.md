# Lab-9
In this lab, I learned how an ESP32 reads RFID cards with an MFRC522 reader, checks the card's UID against an authorized list and lights green LED or sounds a buzzer. I also learned how to use millis() and event handler functions instead of delay(), so the program can react to new cards without freezing.
# Required Equipment
- ESP32 Development Board
- MFRC522 RFID Reader Module (RC522)
- MIFARE Classic 1K card and key fob
- Green LED and Red LED
- 2 x 220 Ω resistors
- Active piezo buzzer
-	Breadboard
-	Jumper Wires
-	USB Cable
# Software
- Visual Studio Code
- PlatformIO
- Serial Monitor
- MFRC522 Library
- Lab9_starter_main.cpp file (provided by instructor)
# Safety Instructions
-	Disconnect power before modifying circuits.
-	Verify all wiring before powering the circuit.
- Connect the MFRC522 to 3.3V only – 5V can damage it.
-	Ensure all grounds are connected.
-	Use a 220 Ω resistor with each LED.
-	Bonus only: never write to block 0 or to blocks 3, 7, 11 … 63 of a card. Only use block 4.
-	Avoid short circuits.
-	Keep the workstation organized.
# Assembly Diagram
<img width="684" height="516" alt="image" src="https://github.com/user-attachments/assets/b0bb203c-88fb-4a93-85a8-728d5f5478cf" />

