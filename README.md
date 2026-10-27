# AJ-ORBIT Gas Safety Alarm System 🚨

**An Arduino-Based Gas Leak Detection and Safety Alert Project**

Developed under **AJ-ORBIT | Electronics • IoT • Embedded Systems**

## 📌 Overview

The AJ-ORBIT Gas Safety Alarm System is an electronics project designed to detect potentially dangerous gas concentrations and provide audible and remote alerts.

The proposed system uses an Arduino Uno as its main controller, MQ-5 gas sensors for gas detection, a thermal sensor for temperature monitoring, a buzzer for local warnings, and a GSM module for remote notifications or calls.

An optional relay and servo mechanism can be explored for controlling a suitable regulator actuator. Any automatic shutoff mechanism requires independent safety validation before real-world use.

## 🎯 Objectives

- Detect potentially hazardous gas concentrations.
- Provide an audible warning through a buzzer.
- Send remote alerts using a compatible GSM module.
- Monitor temperature using a suitable thermal sensor.
- Explore automated safety responses through a relay or servo mechanism.
- Develop an affordable educational electronics prototype.

## ⚙️ Main Components

- Arduino Uno
- MQ-5 gas sensor module(s)
- Compatible thermal sensor
- Active buzzer or alarm module
- Compatible GSM module and SIM
- Relay module, if required
- Servo motor, for an optional mechanical prototype
- Suitable regulated power supply
- Jumper wires and breadboard or PCB

## 🔄 Working Principle

1. The MQ-5 sensor monitors the surrounding air for gases it can detect.
2. The Arduino reads sensor signals and compares them against configured thresholds.
3. If a threshold is exceeded, the system activates the local alarm.
4. When configured and connected to a compatible cellular network, the GSM module can send an alert or initiate a call.
5. The thermal sensor provides additional temperature information.
6. Optional actuator control can be tested separately under supervised, safe conditions.

## 📂 Repository Structure

- `src/` — Arduino source code
- `circuit/` — Circuit and wiring diagrams
- `docs/` — Block diagram, flowchart and documentation
- `images/` — Project photographs and illustrations
- `README.md` — Project overview and instructions

## 🧪 Testing

Test the prototype using safe, controlled sensor-test methods and simulated input signals where possible. Verify sensor readings, alarm activation, GSM communication and power stability independently.

## ⚠️ Safety Disclaimer

This project is an educational prototype and is not a certified gas detector or life-safety system. MQ-series sensors require appropriate calibration and are affected by environmental conditions. Do not test by deliberately releasing flammable gas or exposing electronics to a leaking gas supply.

Do not rely on this prototype to protect people or property. Use a certified gas detector and professionally installed, approved gas shutoff equipment. Never connect an experimental relay or servo directly to a household gas regulator without qualified engineering review.

## 👨‍💻 Developer

**AJ-ORBIT**

Electronics | IoT | Arduino | Embedded Systems

Instagram: [@ajorbit.in](https://www.instagram.com/ajorbit.in)
