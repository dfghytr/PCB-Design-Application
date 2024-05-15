# PCB-Design-Application
# Aim
To design a Invisible burglar alarm in a PCB desihn application.

# Software required
Eagle

# Procedure
1.Open a new schematic file within your project.</br>
2.Use the libraries provided in EAGLE or create custom libraries if necessary.</br>
3.Place components onto the schematic sheet by using the 'Add' tool.</br>
4.Connect the components using the 'Net' tool.</br>
5.Label nets appropriately to ensure clarity</br>
6.Once routing is complete, perform a ERC to ensure there are no errors and save the schematic.</br>
7.Click on the 'Generate/Switch to Board' icon to create a board from your schematic.</br>
8.EAGLE's board layout editor allows you to place components, route traces, and define board shapes.</br>
9.Arrange components on the board to optimize space usage and minimize signal interference.</br>
10.Route traces to connect components according to your schematic.</br>
11.Use the various routing and editing tools provided by EAGLE to ensure proper routing and avoid design rule violations.</br>
12.Once routing is complete, perform a design rule check (DRC) to ensure there are no errors and save the board layout.</br>
13.Go to File > CAM Processor and set up CAM jobs to generate Gerber files for your PCB layers.</br>
14.Verify generated files to ensure they contain all necessary information.</br>
15.Save the generated manufacturing files.</br>

# Theory
An invisible burglar alarm circuit operates on the principle of detecting interruptions in a continuous beam of light, often infrared, which is invisible to the human eye. The core components include an infrared LED emitter and a photodetector, such as a photodiode or phototransistor, positioned to receive the light beam. The LED continuously emits infrared light, forming an invisible line of security. When this beam is unbroken, the photodetector generates a consistent signal. This signal is fed into a comparator circuit that constantly monitors the output voltage from the photodetector. Under normal conditions, the output remains steady. However, if an intruder passes through the beam, it disrupts the light path, causing a sudden drop or change in the photodetector's output signal.

The comparator detects this change and triggers an alarm circuit, which can include various types of alert mechanisms such as sirens, lights, or notifications to a security system. To enhance reliability and prevent false alarms, the circuit might incorporate signal amplification, filtering, and logic gates. Amplifiers boost the photodetector's signal, making it more discernible, while filters eliminate noise that could cause false triggers. Logic gates ensure that only significant and sustained changes in the light beam result in an alarm, thus reducing the likelihood of false alarms due to brief or minor interruptions. By using infrared light, the system remains invisible to intruders, maintaining the element of surprise and increasing the effectiveness of the security setup. This combination of components and design considerations ensures a robust and efficient invisible burglar alarm circuit, providing discreet and reliable intrusion detection.

### Working 
1. **Infrared LED Emission**: An infrared LED emits a continuous beam of infrared light, which is invisible to the human eye.

2. **Beam Alignment**: The infrared LED and a photodetector (photodiode or phototransistor) are aligned such that the photodetector receives the uninterrupted beam of infrared light.

3. **Photodetector Signal**: The photodetector generates a steady electrical signal when the infrared beam is unbroken, corresponding to the constant light it receives.

4. **Comparator Monitoring**: This signal is fed into a comparator circuit that continuously monitors the output voltage from the photodetector.

5. **Signal Change Detection**: When an intruder interrupts the infrared beam, the photodetector’s signal changes (typically drops) due to the loss of light.

6. **Comparator Activation**: The comparator detects this significant change in the signal and activates the alarm circuit.

7. **Alarm Triggering**: Upon activation, the alarm circuit triggers alert mechanisms such as sirens, lights, or notifications to a connected security system.

8. **Signal Amplification**: Amplifiers may be used to boost the photodetector’s signal, making the system more sensitive and capable of detecting smaller changes.

9. **Noise Filtering**: Filters are included to remove any noise from the signal that could cause false alarms, ensuring that only genuine interruptions trigger the alarm.

10. **Logic Gates Integration**: Logic gates are used to process the signal further, ensuring that only sustained interruptions (not brief or accidental) activate the alarm.

11. **Invisible Detection**: The use of infrared light ensures the detection system remains invisible to potential intruders, maintaining the element of surprise.

12. **Power Supply**: The entire circuit is powered by a suitable power supply, ensuring consistent operation of the LED, photodetector, and electronic components.

13. **System Reset**: After the alarm is triggered and the intrusion is addressed, the system can be reset to resume normal operation.

14. **Adjustable Sensitivity**: Some systems may allow adjustment of sensitivity to cater to different environments and levels of security required.

15. **Robust Design**: The circuit is designed to be reliable and efficient, minimizing false alarms and ensuring consistent performance.

16. **Versatile Application**: This type of alarm system can be used in various settings, including residential, commercial, and industrial environments, for effective intrusion detection.

# Circuit Diagram
![WhatsApp Image 2024-04-25 at 3 41 30 AM](https://github.com/dfghytr/PCB-Design-Application/assets/138970628/d2443e28-204e-4d87-ad59-0f504c6f6180)

# Output
### Schematic diagram
![Screenshot 2024-05-15 190436](https://github.com/dfghytr/PCB-Design-Application/assets/138970628/7ed2a111-379e-4d1a-beae-540f914a722c)

### Layout diagram
![Screenshot 2024-05-15 190454](https://github.com/dfghytr/PCB-Design-Application/assets/138970628/d66d46f0-039f-435e-a726-dbd9b6415791)

# Result
Thus Invisible burglar alarm in a PCB desihn application is designed successfully.

