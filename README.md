# RF_data_transmitter_and_receiver
The main aim of this project is to construct a short-range (min:5m) RF DATA
transmitter operating at 2.2MHz center frequency and receiver device.

![BOARD](https://github.com/ErmanIZTECH/RF_data_transmitter_and_receiver/blob/master/Images/transceiver.PNG?raw=true){:class="img-responsive"}
![BOARD](https://github.com/ErmanIZTECH/RF_data_transmitter_and_receiver/blob/master/Images/transceiver.PNG?raw=true){:height="25%" width="25%"}
![BOARD](https://github.com/ErmanIZTECH/RF_data_transmitter_and_receiver/blob/master/Images/transceiver.PNG?raw=true){:height="700px" width="400px"}
You can access the Detailed Report for this project from the link below.

**[Report[PDF]](https://github.com/ErmanIZTECH/RF_data_transmitter_and_receiver/blob/master/P3_Final_Report%20end.pdf)**

### Modulation Method
Amplitude Modulation has been utilized to transfer the data. 
 
 ## Circuitry parts
 ### Colpits Oscillator
 With a center frequency 2.2MHz Colpits oscillator design with a buffer. 
 
 ![colpitts](https://github.com/ErmanIZTECH/RF_data_transmitter_and_receiver/blob/master/Images/colpitts.PNG?raw=true)
 
 Where Ct is the Carrier Signal
 ### Data Interface
 The data transferred to the transmitter or from receiver by USB to TTL converters.
 
 ![USBTTL](https://github.com/ErmanIZTECH/RF_data_transmitter_and_receiver/blob/master/Images/USB_TTL.PNG?raw=true)
 
 
  ### Amplitude Modulator
  Simple bjt amplitude modulator circuit following have been used.
  Ct is the carrier input Mt is the message signal which is obtained from the Computer Serial interface (USB TTL Converter)
  
  ![Modulator](https://github.com/ErmanIZTECH/RF_data_transmitter_and_receiver/blob/master/Images/AModulator.PNG?raw=true)
  
   ### Transmitter (Tuned Amplifier)
  transmitter tuned amplifier circuit. The unwanted frequency components generated in the modulation process required to be eliminated by the filter of the tuned amplifier.
  
  ![Transmitter](https://github.com/ErmanIZTECH/RF_data_transmitter_and_receiver/blob/master/Images/Transmitter.PNG?raw=true)
  
  ## Antenna
  * Simple cable antenna can be used however the ideal length for this frequency is too large therefore in order to match the shorter antenna to the circuit it had to be matched with inductors 
  * With few trials on different inducotrs and applying a curve fitting on gain values shows the ideal inductor value for your antenna.
  * Simply connect the inductors in series to the antenna.
