# OpenDrone VTOL

Open, modular, and sovereign aerial infrastructure platform.

## 🚀 Overview
OpenDrone VTOL is an open-source platform for building interoperable drone-based services for:
- Emergency response (AED delivery)
- Infrastructure monitoring
- Logistics

## 🧩 Architecture
- VTOL Drone (PX4 / ArduPilot)
- Edge AI (Jetson / Raspberry Pi)
- Backend API (FastAPI)
- Ground Control (React)
- Federation Layer (multi-node drone networks)
- 
  ## Core components
- **Flight layer**: PX4 / ArduPilot-compatible configuration
- **Companion computing**: Raspberry Pi / Jetson class devices
- **Backend API**: FastAPI
- **Ground control UI**: React dashboard
- **AI module**: vision + routing
- **Hardware layer**: modular frame, payload bay, and BOM

 ## Repository structure
```text
backend/            FastAPI backend
frontend/           React dashboard
ai-module/          Vision and routing services
simulator/          Telemetry simulator
hardware/           CAD, STL, wiring, BOM
firmware/           Flight-controller config
docs/               Architecture, use cases, federation
elementor/          Landing page scaffold
.github/workflows/  CI automation

## 🌍 Why it matters
Current drone ecosystems are closed and vendor-locked.

OpenDrone provides:
- Open hardware (CERN-OHL)
- Open software (AGPL)
- Interoperability (MQTT, REST)
- EU digital sovereignty

## 🔗 Features
- Modular payload system
- Real-time telemetry (WebSocket)
- Mission API
- Federated drone networks

## 🧪 MVP
This repository contains:
- Backend API
- Telemetry simulator
- AI routing module
- Hardware concept (OpenSCAD)

## 🛰️ Federation
Multiple deployments can interconnect to form distributed drone networks across regions.

## 📦 License
- Software: AGPL-3.0
- Hardware: CERN-OHL-S

## 🤝 Contributing
We welcome contributions from developers, researchers, and public organizations.

## 📡 Vision
A European open drone infrastructure layer.
