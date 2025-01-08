# Flow Sensor Setup

1. **Identify the I/O Port on the Cerbo GX**.
2. **Wire the Sensor**:
   - The YF-S201 water flow sensor has three wires:
     - **Red**: Power (connect to +ve terminal of 12V power supply - battery).
     - **Black**: Ground (connect to the common GND from Cerbo and -ve from the battery).
     - **Yellow**: Signal (connect to one of the digital I/O pins on the Cerbo GX).
3. In the Remote Console, navigate to Settings > I/O > Inputs.
4. Locate the input number corresponding to the I/O port you connected the sensor to.
5. Set the input type to **Pulse Meter**.
6. Navigate to the Home Page of the Remote Console interface on the Cerbo GX and select the **Pulse Meter configuration** option.
7. **Set Up and Calibrate the Sensor**:
   - Reset the pulse counter.
   - Set the initial multiplier to 1 for preliminary calibration.
   - Allow water to flow through the sensor into a calibrated container (e.g., a 20-liter vessel).
   - Monitor and note the total pulse count recorded by the system once the container is filled.
   - **Calculate the Multiplier**: `Multiplier = Container Volume (liters) / Pulse Count`.
   - Update the Pulse Meter settings with the calculated multiplier value to ensure accurate flow measurement.
