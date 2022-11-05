# ESE519-LAB2B_I2C_CAPTURE

1. The following images shows the capture of the i2c communication on the digital oscilloscope.
2. The ADPS9960 sensor was connected with the RP2040 Board and we captured the Serial Clock(SCL) and Serial Data Lines(SDA) lines that communicate with the sensor.
3. The green waveform represents the Serial Clock(SCL) while the yellow waveform represents the Serial data(SDA).
4. We can note that the SCL line is quite unifrom in nature which is quite obvious since the clock signals will always be the same, i.e. it will have the rising edges and falling edges with the same duty cycle and same time time period.
5. On the other hand the SDA signals seems less consistent which is quite intuitive becase it carries the actual data including the stop and start bits.
6. Another thing to note is that the rising edges are not very straight and that is because of the bus capacitance.

![WhatsApp Image 2022-11-04 at 5 26 43 PM (1)](https://user-images.githubusercontent.com/114267693/200096297-aa2e494b-84b9-4449-a497-b013503e1e7e.jpeg)

![WhatsApp Image 2022-11-04 at 5 26 43 PM](https://user-images.githubusercontent.com/114267693/200096310-e6f4f171-2faf-4764-a626-b126b82cec92.jpeg)
