# UAV Architecture Basics

This note summarizes the basic architecture of a UAV system from a beginner engineering perspective.

## Main UAV Subsystems

### 1. Frame / Airframe

The frame is the physical structure of the UAV. It supports the motors, wings, battery, electronics, payload, and landing components.

For fixed-wing and VTOL UAVs, the airframe must balance:

- Low weight
- Structural strength
- Aerodynamic efficiency
- Space for electronics and payload
- Mechanical stability during takeoff, cruise, and landing

### 2. Propulsion System

The propulsion system creates thrust and lift.

Common components:

- BLDC motors
- Propellers
- ESCs
- Battery
- Power distribution wiring

In a VTOL UAV, vertical motors are used for takeoff and landing, while a cruise motor can be used for efficient forward flight.

### 3. Flight Controller

The flight controller is the main control unit of the UAV.

It reads sensor data, estimates the aircraft attitude and position, and sends commands to motors, ESCs, or servos.

Examples of related components:

- IMU
- GNSS
- Barometer
- Magnetometer
- Airspeed sensor

### 4. Navigation Sensors

Navigation sensors help the UAV estimate its position, movement, and flight condition.

Examples:

- GNSS receiver
- IMU
- Airspeed sensor
- Magnetometer
- Barometer

### 5. Communication System

The communication system connects the UAV with the ground station or operator.

It may include:

- Telemetry link
- Video link
- Remote control receiver
- Ground control station software

### 6. Payload

Payload is the useful equipment carried by the UAV for its mission.

For wildfire detection, payload may include:

- RGB camera
- Thermal camera
- Gimbal
- Onboard computer
- Sensors

### 7. Power System

The power system supplies energy to all UAV subsystems.

Important concepts:

- Voltage
- Current
- Power
- Battery capacity
- Power distribution
- Connectors and wiring

## Key Takeaway

A UAV is not just a flying platform. It is a system of mechanical, electrical, electronic, software, and operational subsystems that must work together reliably.
