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
STM32Cube IDE 
Windows Build Tools
OpenOCD
QEMU


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
| LR_02 |Different colour LED's |	Implemented |
