# Autonomous Drone Control Station

An open-source, web-based Ground Control Station for autonomous drones. This project enables full mission control, from configuration and calibration to flight execution, providing a centralized interface for drone operations. It exists to simplify and democratize advanced drone piloting and automation.

## Key Features
*   **Mission Planning & Control:** Plan autonomous flight paths and execute missions via a web interface.
*   **FC Configuration & Calibration:** Configure flight controllers and calibrate onboard sensors.
*   **MAVLink Integration:** Communicate with drones using the standard MAVLink protocol.
*   **Manual Flight Override:** Take direct manual control of the drone when needed.

## Tech Stack
*   **Backend:** Node.js, Express
*   **Frontend:** React, WebSockets
*   **Protocol:** MAVLink
*   **Tooling:** Webpack, Babel

## Getting Started
1.  Clone the repo: `git clone https://github.com/zoreanuj/autonomous-drone-control.git`
2.  Install dependencies: `npm install`
3.  Start the development server: `npm start`