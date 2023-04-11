# LDO-Regulator
Design and Simulation of Three-Stage LDO Regulator with SMC.


### Circuit Schematic
![alt text](https://user-images.githubusercontent.com/90058055/231262017-49960ce2-684a-4fdc-9753-feb65ddf380c.png "Circuit Schematic")

### Loop Gain & Phase
![alt text](https://user-images.githubusercontent.com/90058055/231263188-05b9e046-7838-406e-9ac6-56860b33a24b.jpg "Loop")

The loop has DC gain equal to 107 dB, UGF equal to 15MHz phase margin equal to 66 degrees, and gain margin of 12 dB.

### Drop-Out Voltage
![alt text](https://user-images.githubusercontent.com/90058055/231264119-6991da4d-1b9a-4af0-90da-67538b736a8c.jpg "Drop-Out")

The circuit has Drop-Out voltage lower than 200 mV.

### Transient Load Switching
![alt text](https://user-images.githubusercontent.com/90058055/231264734-62e86a31-27b8-4235-a3cf-4268b7be2511.jpg "Transient")

High UGF and sufficient phase margin restore the desired output voltage quickly after any change in the load current.
<br>
It is important to note that a minimum current draw is necessary to achieve adequate quality factor for restoring desired output voltage.

### PSR
![alt text](https://user-images.githubusercontent.com/90058055/231267639-37a67696-7a3c-4669-9000-424540d1815b.jpg "PSR")

The circuit has PSR equal to -68 dB at DC.

