# Peripheral connections

The Limboid possesses several electrical sensors and actuators, and the number is expected to increase as it evolves. Peripheral connections are the connections between the Android phone, core signaling module (CSM), and sensors and actuatos in the Limboid's body and skin. Following are the peripheral connections:

- USB OTG cable connecting android to CSM arduino nano.
- CSM uses enable lines and I2C bus to communicate with valve array module's PCA9685 ic (and future sensing modules which can be plugged into CSM breadboard). CSM produces PWM square waves to drive the prime mover power mosfets which connect using small stranded wires. Flat ribbon cables or flexible flat cables are soldered directly to the somatosensory strips and are inserted into sockets mounted on the CSM breadboard.
