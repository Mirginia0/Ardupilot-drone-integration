# Drone Integration and Mission Planning with ArduPilot

A team project combining hands-on quadcopter assembly, flight-system configuration and mission planning. We integrated the drone hardware, configured the radio-control connection and carried out a short indoor flight test under manual RC control.

**Authors:** Martyna Rydczak, Dawid Zieliński and Szymon Rybka  
**Project supervisor:** Iman Esfandyiar  
**Poznan University of Technology**

**ArduPilot · Mission Planner · Linux · RC configuration · Hardware integration**

![Assembled quadcopter during hardware integration](media/images/assembled-drone.jpg)

## Goal and scope

The goal was to become familiar with the ArduPilot platform and prepare a drone for testing. Our work covered manual assembly, component integration, software setup, wireless communication and mission planning in Mission Planner.

We planned the autonomous mission in Mission Planner and tested the physical drone indoors under manual RC control. We did not carry out outdoor tests or execute the planned autonomous mission on the physical drone.

## Team contribution

> **Shared development**  
> We worked together on assembly, configuration, integration and testing, sharing responsibilities throughout the project.

## Assembly and integration

We manually assembled the drone and connected the flight controller, GPS, wireless modules, ESCs and battery. We checked the component connections and prepared the assembled platform for configuration and testing.

<table>
<tr><th>Component integration</th><th>Assembly and connection checks</th></tr>
<tr><td><img src="media/images/component-integration.jpg" alt="Close-up of the integrated drone components" width="420"></td><td><img src="media/images/assembly-checks.jpg" alt="Hands-on assembly and checking connections" width="420"></td></tr>
</table>

## Configuration and mission planning

### ArduPilot and Mission Planner

We set up Linux, configured ArduPilot and planned a mission in Mission Planner. The presentation includes a SITL demonstration showing takeoff, waypoints and landing, with a map view and telemetry display.

![Mission planning in Mission Planner](media/images/mission-planning.jpg)

<details>
<summary><strong>SITL demonstration</strong></summary>

![Mission Planner and SITL demonstration shown in the presentation](media/images/sitl-demonstration.jpg)

The screenshot illustrates mission planning and simulated flight in Mission Planner.

</details>

### Radio-control connection

We configured the physical radio transmitter, checked its connection to the drone and verified the drone's response to control inputs before the indoor flight test.

<img src="media/images/radio-transmitter.jpg" alt="RadioMaster TX12 radio transmitter used for manual drone control" width="300">

We used a **RadioMaster TX12** transmitter for manual RC control.

We also configured WiFi modules and a router for remote communication.

## Testing and results

Our assembled drone successfully took off during a short indoor test under manual RC control. We checked the radio connection and the drone's response to commands.

| Recording | Link |
|---|---|
| Short indoor test recording | [Open MP4](media/videos/indoor-test-short.mp4?raw=true) |
| Longer indoor test recording | [Open MP4](media/videos/indoor-test-long.mp4?raw=true) |

The recordings show our indoor tests of the physical prototype.

Through this project, we gained experience in integrating electronics and propulsion components, configuring a flight system and troubleshooting communication between hardware and software.

## Project materials

- [Project presentation](docs/project-presentation.pdf)
- [Image and recording index](media/README.md)

