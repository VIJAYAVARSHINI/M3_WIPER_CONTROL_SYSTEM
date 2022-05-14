# INTRODUCTION
Wiper's are used to clean the wind shield of the car at the front and rear. A wiper control system is essential to control and maintain the speed of operation of the wiper. Wiper works by removing oil,dust,rain water and dirt.That get struck to the wind shield and the arm is provided by the motor.The warm gear is able to generate the force required to move the wipers as fast as they need to move. The car wipers that have been available in the present day market are manual systems that work on the principle of manual switching. In this project a wiper system that switches ON the wiper on and changes speed of operation and stops the wiper action. 

Advanced Wiper Speed Control System is utilised in all sorts of automobiles, and its primary function is to remove rain air drops from the vehicle's front screen. Because driving a vehicle in the rain is quite difficult, we will use wipers to clear the front screen of the vehicle, which is a mirror, so that we may drive the vehicle even in the rain.


# WIPER CONTROL SYSTEM 
WCS has separate on/off buttons for control. Generally, in case of automobiles there are 2 wipers, each of it performing synchronized action with respect to one another. The are functions for washing and heating.The intrevals for speed can be varied with the help of + and - buttons. The washing functions includes the spraying action followed by wiping and purging. Even though the wiper is put off during the middle of its operation, it completes it cycle by travelling back to the home position.

![image](https://user-images.githubusercontent.com/101562511/168415359-af26279a-a7da-4635-af6b-6d2f056ea761.png)

# BASIC RESEARCH

Modern windshield wipers can also be operated on an as-needed basis. The intermittent wiper option, as opposed to the continuous wiper option, cycles the wipers on and off every few seconds rather than operating continuously. It was in the 1970s that intermittent control made its debut in autos. A steady power source was used to control the original intermittent wipers, which were routed through a series of switches to achieve their functionality. Most automobile wipers are now controlled by a microprocessor, which is becoming increasingly common.

Many wiper systems in cars today are controlled by a rain sensor, which measures the speed at which raindrops hit the windshield and activates the wipers. The inputs from the sensor are evaluated by a microprocessor, which then calculates the speed at which the wipers should travel.

# FEATURES
STM32 series 32-bit microcontroller is based on arm Cortex-M3 processor.

It can support a wide range of 32-bit applications, including high-performance, real-time functions, digital signal processing, and low-power, low-voltage operation. At the same time, it has a fully integrated and easy-to-use development. Based on STM platform and meet the requirements of real-time control, there are four options. They are μ C / OS-II, μ Clinux, eCos, FreeRTOS and Dujiangyan operating system (djyos). The following describes the characteristics and shortcomings of these five embedded operating systems.

μ C / OS-II is a priority based preemptive multitask real-time operating system, which includes real-time kernel, task management, time management, communication synchronization (semaphore, mailbox, message queue) and memory management. It can make each task work independently, do not interfere with each other, it is easy to implement on time and without error, make the design and expansion of real-time applications easy, and greatly reduce the design process of applications.


 # 4 W'S
 
### WHAT 
  * Windshield wipers keep the windshield of a vehicle clear from rain water, snow, dust and road spray. 
### WHY 
  * To keep the windscreen clean and clear the particles which causes disturbance to viewing.
### WHEN 
  * When visibility is affected. Likely, the windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.
### WHO 
  * Mark Anderson


# SWOT Analysis 

### Strength
* Visibility
* Safety
* Basic needed equipment for all automobiles

### Weakness 
* High cost
* Not automatic
* Inertia

### Opportunities
* Automatic operation and rain sensors can be implemented in future.

### Threats 
* Once the board is repaired replacement is needed.
* Economical Crisis

# SOFTWARE REQUIREMENTS 

* STM32Cube IDE 
* Windows Build Tools
* OpenOCD
* QEMU


# REQUIREMENTS
## High level requirements
| ID | Description | Status |
| --- | --- | --- | 
| HR_01 | Car ON and OFF |	Implemented |
| HR_02 |	Wiper ON |	Implemented |
| HR_03 |	Wiper Speed Change |	Implemented |
| HR_04 |	Wiper OFF |	Implemented |
## Low level requirements
| ID |	Description | Status |
| --- | --- | --- |
| LR_01 |Push Button |	Implemented |
| LR_02 |Three colour LED's |	Implemented |

# WORKING

Windshield wipers keep the windshield of a vehicle clear from rain water, snow, dust and road spray. The first windshield wipers were operated manually by moving a lever inside the car. Later wiper designs were powered by the engine's manifold vacuum. Virtually all wipers today employ an electric motor coupled with a linkage mechanism and are actuated by a knob beside the steering wheel. The wiper blade speed can be adjusted by the driver.

In this project the Wiper Control system is implemented using STM32 which is a 32-bit microcontroller IC.The wiper operation can be carried out with basic modes like On, speed change and Off. As STM32 contains only 1 push button, the same button is utilized for all operations. The discovery board contains 4 LEDs

The RED LED is considered for the ACC position. Once the push button is pressed for 2 seconds, the RED LED keeps continuously glowing until the stop of the engine signifying the engine condition to be turned ON. On the next one press of the user in the push button, the Blue, Green and Orange LEDs turns ON with a pre-set frequency. When the push button is pressed again the frequency changes, likewise the frequency is changed for next two press. If the push button is pressed for 2 seconds continuously, the RED light goes off and the pattern stops bringing it to default position which signifies the engine is turned OFF.

# TESTCASES AND OUTPUT

## High Level Test Cases
| Test ID | Description | Expected Output | Actual Output |
| --------|:------------|:--------|:-----------|
| 1 | Push Button pressed | ACC mode ON | Red LED ON |
| 2 | Push Button pressed | WIPER starts | LED's ON and switching| 
| 3 | Push Button pressed | WIPER changes speed | LED's ON and switching | 
| 4 | Push Button pressed | WIPER works at high speed | LED's ON and switching |  
| 5 | Push Button pressed |ACC mode OFF | LED OFF| 


## LOW LEVEL TEST CASE
 | Test ID | Description | Expected Output | Actual Output | Status | 
 | --------|:------------|:--------|:-----------|:-------------| 
 | 1 | Push Button --> pressed | Car starts | Red LED ON | PASS |
 | 2 | Push Button --> pressed | WIPER starts and operates at different speed | Different LED's gets ON in sequence | PASS |
 | 3 | Push Button --> pressed | Car Stops | LED OFF | PASS |
 
 # OUTPUT
 
 ## CAR ON
 
 ![image](https://user-images.githubusercontent.com/101562511/168419950-daac1271-cde3-4833-883d-a3cb25f6dfe5.png)
 
 ## WIPER OPERATION
 
 ![image](https://user-images.githubusercontent.com/101562511/168419963-ffcba513-8c00-48ad-b331-8b6bcff08071.png)
 
 ## CAR OFF

![image](https://user-images.githubusercontent.com/101562511/168419911-04ae9432-24e5-4519-95d4-ae55db7ad56f.png)
