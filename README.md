# RF_data_transmitter_and_receiver
The main aim of this project is to construct a short-range (min:5m) RF DATA
transmitter operating at 2.2MHz center frequency and receiver device.

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
