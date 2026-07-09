# fabrication-tech

Unified repository for drone technology and CNC machine work, including shared packages, scripts, documentation, and firmware utilities.

## Scope
- Drone hardware configs, flight stacks, telemetry, and mission planning
- CNC toolpaths, post-processors, CAM helpers, and machine interfaces
- Shared libraries for motion control, G-code parsing, sensor fusion, and telemetry
- Build/test scripts and example projects

## Structure
- `drones/` — drone-specific flight software, configs, and missions
- `cnc/` — CNC-specific toolpaths, post-processors, and control scripts
- `packages/` — shared reusable libraries and CLI tools
- `docs/` — hardware guides, wiring diagrams, and API references
- `scripts/` — setup, deploy, and calibration helpers

## Safety
- Always validate toolpaths before running on real hardware
- Keep machine firmware and configs versioned
- No flight logs or machine telemetry containing identifiable data in public repo
