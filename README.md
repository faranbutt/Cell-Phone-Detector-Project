## Mobile Signal Detector 📞🕵🏻‍♂️📡
As increase in the technology in the world using the electronic equipment’s are being used in the wrong way like in the examin🕵🏻‍♂️🕵🏻‍♂️📡📡ation halls and in the confidential room. To avoid this we are introducing a project called MOBILE PHONE DETECTOR.
This handy, pocket-size mobile transmission detector or sniffer can sense the presence of an activated mobile cell phone from a distance of one and-a-half meters. So it can be used to
prevent use of mobile phones in examination halls, confidential rooms, etc. It is also useful for detecting the use of mobile phone for Spying and unauthorized video transmission. The circuit
can detect the incoming and outing calls, even if the mobile phone is kept in the silent mode. The moment the Bug detects RF transmission signal from an activated mobile phone, it starts sounding a beep alarm and the LED blinks. The alarm continues to beep until the signal

# Problem Statement
- Previously, there was no technology to detect the cell phones in the examination hall and in cell phone restricted areas. There is manual checking and there is still a chance of having the cell phone with the person if he is not checked properly. So to avoid this problem, an automatic
detection of cell phone is introduced.

# Circuit Diagram
![Image Alt Text](/images/Circuit%20Diagram.png)

# Working
Mobile phone uses RF with a wavelength of 30cm at 872 to 2170 MHz. That is the signal is high frequency with huge energy. When the mobile phone is active, it transmits the signal in the form of sine wave which passes through the space. Ordinary LC (Coil-Capacitor) circuits are used to detect lowfrequency radiation in the AM and FM bands. The tuned tank circuit having a coil and a variable capacitor retrieve the signal from the carrier wave. But such LC circuits cannot detect high frequency waves near the microwave region. Hence in the circuit, a capacitor is used to detect RF from mobile phone considering that, a capacitor can store energy even from an outside source and oscillate Like LC circuit. One lead of the capacitor gets DC from the positive rail and the other lead goes to the negative input of ICi. So the capacitor gets energy for storage. This energy is applied to the inputs of ICi so that the inputs of IC are almost balanced with 1.4 volts. In this state output is zero. But at any lime IC can give a high output if a small current is induced to its inputs. There a natural electromagnetic field around the capacitor caused by the 50Hz from electrical wiring. When the mobile phone radiates high energy pulsations, capacitor oscillates and release energy in the inputs of IC. This oscillation is indicated by the flashing of the LED and beeping of Buzzer. In short, capacitor carries energy and is in an electromagnetic field. So a slight change in field caused by the RF from phone will
disturbed the field and forces the capacitor to release energy.

# Simulation on Proteus
![Image Alt Text](/images/proteus.png)

# PCB Layout
![Image Alt Text](/images/pcb.png)

# Hardware
![Image Alt Text](/images/patched.png)

# Conclusion:
This pocket-size mobile transmission detector or sniffer can sense the presence of an activated mobile cell phone from a distance of one and-a-half meters. So it can be used to prevent use of mobile phones in examination halls, confidential moms, etc. It is also useful for detecting the use of mobile phone for spying and unauthorized video transmission.

# White Paper:
https://github.com/faranbutt/Cell-Phone-Detector-Project/blob/main/PROJECT%20REPORT.pdf