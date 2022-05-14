# ABSTRACT

Windshield wipers keep the windshield of a vehicle clear from rain water, snow, dust and road spray. The first windshield wipers were operated manually by moving a lever inside the car. Later wiper designs were powered by the engine's manifold vacuum. Virtually all wipers today employ an electric motor coupled with a linkage mechanism and are actuated by a knob beside the steering wheel. The wiper blade speed can be adjusted by the driver.

In this project the Wiper Control system is implemented using STM32 which is a 32-bit microcontroller IC.The wiper operation can be carried out with basic modes like On, speed change and Off. As STM32 contains only 1 push button, the same button is utilized for all operations. The discovery board contains 4 LEDs

The RED LED is considered for the ACC position. Once the push button is pressed for 2 seconds, the RED LED keeps continuously glowing until the stop of the engine signifying the engine condition to be turned ON.
On the next one press of the user in the push button, the Blue, Green and Orange LEDs turns ON with a pre-set frequency. 
When the push button is pressed again the frequency changes, likewise the frequency is changed for next two press.
If the push button is pressed for 2 seconds continuously, the RED light goes off and the pattern stops bringing it to default position which signifies the engine is turned OFF.
