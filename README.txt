--------------------------------------------------------------
                      DRO and DIVIDER Systems Project
--------------------------------------------------------------

Description:
-------------
The **DRO System** (Digital Read-Out) and **DIVIDER System** are developed as complementary systems to improve the functionality of vintage industrial watchmaking machines. The primary objective of the project is to modernize these old machines by adding precision controls while maintaining their antique appearance. These machines are highly valuable collector's items and their preservation is essential.

The **DRO System** displays and modifies values from sensors and linear scales through a 7” touch screen controller. It also serves as the control center for the entire system, with a graphical user interface (GUI) that provides various functions such as setting zero points, adjusting values, and controlling the spindle.

The **DIVIDER System** complements the DRO system by controlling two stepper motors. These motors perform various functions such as linear advance cycles and angular indexing, with precision screw/nut systems and screw and endless wheel systems.

**Note**: This project is non-confidential and can be shared publicly in accordance with the confidentiality policies of the company.

Features:
---------
1. **DRO System**:
   - Touchscreen interface (7” controller).
   - Displays values from RL2IC sensors.
   - Controls multiple axes with values from linear scales.
   - Allows the user to perform various functions:
     - **ZERO**: Set values to 0.
     - **Ø / R**: Double the value (Ø = Diameter) or reset to the original (R = Radius).
     - **+ / -**: Add or subtract a value.
     - **Spindle speed**: Displays spindle motor speed.
     - **Spindle torque**: Displays spindle motor torque.
   - Functions through a graphical user interface with control buttons and menus.

2. **DIVIDER System**:
   - Controls 2 stepper motors for:
     - **Linear advance cycle**: Motor 1 drives a precision screw/nut system to perform a linear movement.
     - **Angular indexing**: Motor 2 performs angular indexing by rotating to a defined number of divisions.
   - Operates based on the angular zero bridge and current linear zero point.
   - Uses sensors to monitor the angular position, ensuring precision in every cycle.

3. **System Integration**:
   - The DRO system and DIVIDER system work together to enhance the user experience, providing precise control over the movements of the watchmaking machines.
   - The microprocessor in the DRO system manages both systems, ensuring smooth operation and synchronization.

Materials and Hardware Used:
----------------------------
- **DRO System**: 
  - 7” touch screen display
  - RL2IC sensors
  - Microprocessor (e.g., STM32 or equivalent)
  - Various control switches and buttons
  - Power supply

- **DIVIDER System**:
  - Stepper motors (2)
  - Precision screw/nut system
  - Screw and endless wheel system
  - Angular position sensors
  - Circular scale for angular indexing

Operating Instructions:
-----------------------
1. **DRO System**:
   - Power on the system and the touchscreen will display the main menu.
   - Select the desired axis to monitor values.
   - Use the function buttons to interact with the system (e.g., setting zero, changing values, adjusting spindle speed and torque).
   - The DRO system will continuously update values in real-time as inputs are modified.

2. **DIVIDER System**:
   - Once the DRO system is calibrated and zeroed, the DIVIDER system will begin its cycle.
   - Stepper motor 1 will execute a linear advance cycle, moving the system by the defined distance and then returning to the starting position.
   - Stepper motor 2 will perform angular indexing, rotating to the specified division points, based on the given angular sector.

License:
--------
This project is shared under the **MIT License**. You may freely use, modify, and distribute the code, as long as you respect the attribution requirements. However, all proprietary hardware used is subject to the company's policies.

--------------------------------------------------------------
