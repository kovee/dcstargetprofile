# T.A.R.G.E.T. Profile for DCS:World.

A complex T.A.R.G.E.T. profile for DCS:World. At the moment it is meant to
be used with the Thrustmaster Warthog HOTAS.

## Features

Complete control mapping profile for the following DCS modules:
- [PLANNED] A-10A Thunderbolt II
- [PLANNED] A-10C Thunderbolt II
- [PLANNED] F-14A Tomcat
- [PLANNED] F-14B Tomcat
- [PLANNED] F-15C Eagle
- [PLANNED] F-16C Viper
- [WORK IN PROGRESS] F/A-18C Hornet
- [PLANNED] MiG-21BiS Fishbed
- [PLANNED] MiG-29A Fulcrum
- [PLANNED] MiG 29S Fulcrum
- [PLANNED] Su-25 Frogfoot
- [PLANNED] Su-27 Flanker B
- [PLANNED] Su-33 Flanker D
- [PLANNED] T-45 Goshawk

Beside the Thrustmaster Warthog HOTAS it is possible to use the Thrustmaster
T.Flight or Pendular rudders as flight controllers. For additional buttons
Thrustmaster Cougar MFDs can be used. The default T.A.R.G.E.T. environment
is extended to use a maximum of three MFDs.

## Requirements and Supported Hardware

To use this profile when playing DCS the TARGET Script Editor needs to be
installed on the host system.

At the moment the profile is written to support the Warthog HOTAS, so 
having that one connected to the host system is required. 

## Installation and Usage

Save the profile somewhere on the host system, set any desired custom 
options in configuration.tmh, then load profile.tmc in the TARGET Script
Editor and run the script.

The controller layouts can be found in the documentation folder.

## Layers

This profile uses all layers configurable in T.A.R.G.E.T., meaning that all 
buttons/switches can have a maximum of six different functionality. There
are three different main layers, out of which only once can be active at a
given time. The active layer is defined by the state of the Pinkie switch
on the Warthog throttle.

Each layer has two sublayers meaning that every button/switch can have a
primary function, and a secondary function that is accessible by holding
down the PADDLE SWITCH on the Warthog joystick.

### MIDDLE Layer

This is the default layer and it is active when the Pinkie switch is in the
MIDDLE position. This layer is meant to be used for navigation/free flight.

### UP Layer

This is the combat layer and it is active when the Pinkie switch is in the
FORWARD position. It is meant to be used during combat when the MASTER ARM
switch is on.

### DOWN Layer

This is the control layer and it is active when the Pinkie switch is in the
BACKWARD position. It is meant to be used for control options that are not
directly tied to the controls of the airplane but to controlling the game
itself, or various external tools.

The DOWN layer is common between all supported aircrafts.
