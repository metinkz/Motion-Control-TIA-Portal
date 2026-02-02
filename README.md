# Motion Control System with HMI (Manual & Automatic)

A motion control project developed in **Siemens TIA Portal** for learning purposes through a course.
The project demonstrates commissioning, manual control, and automatic motion of a single axis using standard Siemens motion control function blocks and an HMI interface.

## System Overview
- Single-axis motion control using Siemens motion control FBs
- Axis commissioning, enabling, homing, and error handling
- Manual and automatic operation modes selectable via HMI
- Position and velocity feedback displayed in real time

## Motion Functions Implemented
- Drive enable and power control (`MC_Power`)
- Homing to reference position (`MC_Home`)
- Manual jogging (CW / CCW) (`MC_MoveJog`)
- Absolute positioning (`MC_MoveAbsolute`)
- Relative positioning (`MC_MoveRelative`)
- Velocity-based motion (`MC_MoveVelocity`)
- Motion table execution (`MC_CommandTable`)
- Controlled stop and reset (`MC_Halt`, `MC_Reset`)

## HMI Features
- Start/stop and system reset controls
- Manual jogging buttons (CW / CCW)
- Absolute and relative position input
- Velocity and position display
- Automatic motion execution via movement table
- Separate manual and automatic control screens

## Control Logic Highlights
- Axis state and error handling using motion FB status outputs
- Conversion between HMI distance input and drive resolution
- Safe interlocking between motion commands
- Timed system stop and command reset logic

## Tools & Technologies
- Siemens TIA Portal
- Siemens WinCC Advanced
- Siemens Motion Control Function Blocks

## What I Learned
- Commissioning and controlling motion axes in TIA Portal
- Using Siemens motion control FBs correctly
- Implementing manual and automatic motion modes
- Linking motion commands to HMI controls
- Handling position, velocity, and error feedback

## Possible Improvements
- Multi-axis coordination
- Alarm and diagnostic screens
- Jog speed selection from HMI
