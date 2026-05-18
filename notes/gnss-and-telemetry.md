# GNSS and Telemetry Basics

This note explains two important UAV concepts: GNSS and telemetry.

## GNSS

GNSS stands for Global Navigation Satellite System.

It is the general term for satellite positioning systems.

Examples:

- GPS
- Galileo
- GLONASS
- BeiDou

GPS is one type of GNSS.

## Why GNSS Matters in UAVs

GNSS helps a UAV estimate its location.

It is useful for:

- Position hold
- Waypoint navigation
- Return-to-home
- Mission planning
- Geotagging detected events
- Ground station tracking

## Limitations of GNSS

GNSS can be affected by:

- Weak signal
- Buildings
- Trees
- Multipath reflections
- Interference
- Poor satellite visibility

For this reason, UAVs usually combine GNSS with other sensors such as IMU, barometer, magnetometer, and airspeed sensor.

## Telemetry

Telemetry is the data communication link between the UAV and the ground station.

It allows the operator or ground system to monitor UAV data.

Telemetry may include:

- Position
- Altitude
- Speed
- Battery status
- Flight mode
- GNSS status
- Warnings
- Mission information

## Telemetry vs Video Link

Telemetry is mainly for flight data and commands.

Video link is mainly for transmitting camera image or video.

They can be separate systems.

## Key Takeaway

GNSS helps the UAV know where it is. Telemetry helps the operator or ground station know what the UAV is doing.
