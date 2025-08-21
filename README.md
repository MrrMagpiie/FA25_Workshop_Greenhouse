# UC Greenhouse Environmental Control System Repair & Upgrade
## Background

In a previous COSC Workshop, I worked on a smart greenhouse project and completed a functional prototype for environmental monitoring and automation. This prototype was centered around a laptop running Home Assistant and a microcontroller-based sensor array, interfacing via ESPHome.

During development, we discovered that the UC Greenhouse is no longer in use due to a failure in its environmental control system. This project proposes building a new system to restore functionality and allow the greenhouse to be used again.

## Project Overview

The goal of this project is to:

- Rebuild and expand on the existing prototype system
- Interface the system with the existing greenhouse infrastructure
- Replace the current prototype's use of ServiceNow with a more suitable local database and front-end solution
- Repair or replace mechanical components as needed
- Document the system for use by both technically inclined students and non-technical staff
## Skills & Knowledge Areas

This project will involve the following areas of expertise:

- Embedded Systems Design – Programming and deploying microcontrollers for sensor control and automation
- Internet of Things (IoT) – Integrating hardware with networked control systems using protocols like ESPHome
- System Design & Integration – Rebuilding and adapting the previous prototype to fit the specific needs of the greenhouse
- Technical Diagnostics & Mechanical Repair – Troubleshooting and repairing hardware components such as actuators, fans, vents, or wiring
- User Interface Design – Creating a simple, usable control interface for non-technical users
- Documentation & Knowledge Transfer – Writing clear, accessible guides for future students and greenhouse staff

## Hardware Requirements

- Core system components from the previous prototype will be reused
- Additional hardware (e.g., motors, relays, new sensors) may be required to fully integrate with the greenhouse infrastructure
- Networking hardware or edge devices may be needed for reliable connectivity and local control
  
## Minimum Viable Product (MVP)
A working greenhouse control system that replicates the original functionality (e.g., controlling temperature, humidity, and lighting), with a user-friendly interface for non-technical staff.

## Stretch Goals & Additional Functionality
Once the core system is operational, additional automation and monitoring features may be developed:

### Data Collection

- Monitoring light levels, power consumption, temperature, humidity, and soil moisture
- Logging and visualizing data for analysis

### Automation

- Scheduling and environmental feedback-based control for:
  - Watering systems
  - Grow lights
  - Heating/cooling (airflow and temperature)
- Optional: Fine-grained control per plant, if per-plant sensors and actuators are feasible

### Plant-Specific Optimization
- Integration with resources like OpenPlantBook to provide optimal environmental conditions for specific plant species

## Collaboration & Stakeholder Input

To maximize the project's value to the school, collaboration with the Biology Department and other relevant programs will be essential. Their input will help identify greenhouse usage needs and prioritize feature development.
