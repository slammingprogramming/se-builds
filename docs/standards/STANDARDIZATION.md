# Standardization Guidelines for SE-Builds

## Overview
To ensure all builds are well-documented, functional, and compatible across platforms, the following guidelines define the structure, naming conventions, and documentation standards for submitting builds to SE-Builds. Please adhere to these standards to maintain quality and usability.

---

## Build Documentation Standards

Each build should include a `README.md` within its directory, documenting essential details about the build. The following sections and guidelines will ensure a consistent format for all submissions.

### Required README Sections

1. **Build Name and Thumbnail**
   - Provide the name of the build as the main title in the README.
   - Include a thumbnail or main image at the top for quick visual identification.

2. **Summary**
   - A brief description of the build, covering its primary function, purpose, and intended use case.

3. **Vessel Type**
   - Define the type of vessel using the following categories:
     - **Rover**: Ground-based vehicles designed for planetary exploration.
     - **Station/Base**: Fixed structures used for living, resource gathering, or production.
     - **Ship**: Space-faring or atmospheric vehicles designed for exploration, combat, transport, or utility.
   - If a build has multiple functions, list the primary function first (e.g., "Ship – Combat").

4. **Environment Compatibility**
   - Specify which environment(s) the build is compatible with:
     - **Atmospheric**: Designed for operation within planetary atmospheres.
     - **Space**: Designed for zero-gravity and vacuum environments.
     - **Hybrid**: Capable of operating both in atmosphere and in space.
   - Include any additional environmental specifications, such as "works only on planets with low gravity."

5. **Vessel Size and Class**
   - Use standardized size classifications:
     - **Small**: Compact, often lightly armed or specialized (e.g., small drill rig, scout ship).
     - **Medium**: Moderately sized, capable of multi-role operations.
     - **Large**: Heavily armed or utility-focused, suitable for extended missions.
   - Example format:
     - **Atmospheric** – **Miner** – **Medium**

6. **Key Features**
   - List core features of the build, using bullet points. Include:
     - **Functional Aspects**: Drills, welders, cargo space, oxygen generators, etc.
     - **Armament**: Weaponry, turrets, or defensive systems (if applicable).
     - **Automation/Scripts**: Any custom scripts or automation functions.
     - **Performance Metrics**: Thrust-to-weight ratios, fuel efficiency, power requirements, etc. (optional).

7. **Survival Readiness**
   - State if the build is survival-ready and list any adjustments required for survival mode (e.g., resource limits, cargo storage).

8. **Cross-Platform Compatibility**
   - Confirm that the build is functional on PC, Xbox, and PlayStation, noting any platform-specific limitations.

9. **Additional Notes**
   - Include any miscellaneous information or tips on operating or modifying the build.

---

## Directory and File Naming Conventions

- **Directory Names**: Use clear, descriptive names that categorize builds, such as `Atmospheric-Miners`, `Combat-Ships`, or `Bases-Stations`.
- **File Names**: 
   - Blueprint file: `blueprint.sbc`
   - Documentation: `README.md`
   - Changelog: `CHANGELOG.md`

### Example Directory Structure
Each build should follow this directory structure:

SE-Builds/
├── Atmospheric-Miners/
│   └── Small-Miner/
│       ├── blueprint.sbc
│       ├── README.md
│       └── CHANGELOG.md
└── Space-Combat/
    └── Large-Destroyer/
        ├── blueprint.sbc
        ├── README.md
        └── CHANGELOG.md

---

## Standards for Describing Features

To ensure consistent detail across all submissions, adhere to these formatting standards when describing features in the README:

1. **Functional Components**:
   - Describe key systems like power (battery, solar, reactor), storage capacity, conveyor systems, and life support.
   - Example: “**Power Supply**: 4 Large Reactors, 12 Batteries, and solar panels for backup.”

2. **Armament**:
   - List weapons and defensive systems with quantities and types (e.g., Gatling Turrets, Missile Launchers).
   - Specify coverage, angles, or automated targeting if relevant.

3. **Automation and Scripts**:
   - Describe any integrated scripts, including setup and usage notes.
   - Include references to creators if using third-party scripts, and give setup instructions if required.

4. **Performance Metrics**:
   - Optional but recommended: List relevant stats such as thrust-to-weight ratio, fuel efficiency, or speed.

---

## Blueprint Standards

### Cross-Platform Compatibility
All builds should be functional across PC, Xbox, and PlayStation. Avoid platform-specific mods and scripts. Builds should be available on both [Steam Workshop](https://steamcommunity.com/workshop/browse/?appid=244850) and [mod.io](https://mod.io/g/spaceengineers) for console users.

### Survival Mode Compliance
Ensure all builds are functional in survival mode. Components should be readily available or easy to replace in a survival scenario.

### Performance Optimization
Optimize builds to avoid excessive block counts, complex scripts, or any unnecessary complexity that may affect performance.

---

## Documentation Example Template

Here’s a sample structure for documenting your builds.

