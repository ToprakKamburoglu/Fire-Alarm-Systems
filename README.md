# Fire Alarm System Design Project

<div align="center">

<br></br>

![Honeywell](images/Honeywell.png)

*Industry Partner - Honeywell*

<br></br>

</div>

## 🚨 Project Overview

This repository contains the final project for the **Computer Architecture** course, developed in collaboration with **Honeywell**. The project focuses on designing and simulating fire alarm systems and their propagation patterns across different rooms and zones in a building.

## 🎯 Project Objectives

The main goal of this project is to create a comprehensive fire alarm system that can:
- **Detect fire incidents** in various rooms and zones
- **Simulate fire propagation** patterns between interconnected spaces
- **Coordinate alarm responses** across multiple detection points
- **Provide real-time monitoring** and control capabilities
- **Ensure safety compliance** with fire safety regulations

## 🏗️ System Architecture

### Core Components

#### 1. **Detection System**
- **Smoke Detectors**: Optical and ionization-based detection
- **Heat Sensors**: Fixed temperature and rate-of-rise detection
- **Manual Call Points**: Emergency activation stations
- **Gas Detection**: Specialized sensors for specific environments

#### 2. **Control Panel**
- **Central Processing Unit**: Main system controller
- **Zone Management**: Individual room/area control
- **Display Interface**: Status monitoring and system information
- **Communication Module**: Network connectivity and data transmission

#### 3. **Alarm & Notification System**
- **Audio Devices**: Sirens, horns, and voice evacuation systems
- **Visual Indicators**: Strobe lights and LED status displays
- **Zone-Specific Alerts**: Targeted alarm activation
- **Building-Wide Coordination**: Integrated response system

#### 4. **Room-to-Room Propagation Simulation**
- **Fire Spread Modeling**: Physics-based propagation algorithms
- **Ventilation System Integration**: HVAC impact on fire/smoke spread
- **Compartment Analysis**: Room-by-room fire behavior simulation
- **Evacuation Route Planning**: Dynamic exit strategy optimization

## 🔧 Key Features

### Fire Detection & Monitoring
- **Multi-Zone Detection**: Independent monitoring of different building areas
- **Intelligent Sensors**: Advanced detection algorithms with false alarm reduction
- **Real-Time Status**: Continuous monitoring and immediate alert generation
- **Historical Data**: Event logging and trend analysis

### Propagation Simulation
- **Room Connectivity Mapping**: 3D building layout integration
- **Fire Behavior Modeling**: Temperature, smoke, and toxic gas spread
- **Time-Based Analysis**: Propagation timeline and critical evacuation windows
- **Environmental Factors**: Wind, temperature, and humidity considerations

### Control & Response
- **Automated Response**: Pre-programmed emergency procedures
- **Manual Override**: Emergency personnel control capabilities
- **System Integration**: HVAC, lighting, and security system coordination
- **Remote Monitoring**: Off-site supervision and control

## 📁 Project Structure

```
Fire-Alarm-System/
├── Honeywell.etb               # Main Honeywell system configuration
├── README.md                   # Project documentation
├── images/                     # Project images and diagrams
│   └── Honeywell.png          # Honeywell company logo
├── src/                        # Source code and algorithms
│   ├── detection/              # Fire detection modules
│   ├── propagation/            # Fire spread simulation
│   ├── control/                # System control logic
│   └── interface/              # User interface components
├── config/                     # System configuration files
│   ├── zones.cfg              # Zone definitions and mappings
│   ├── devices.cfg            # Device configuration
│   └── thresholds.cfg         # Detection thresholds
├── simulation/                 # Propagation simulation models
│   ├── room_models/           # Individual room characteristics
│   ├── building_layout/       # Overall building structure
│   └── scenarios/             # Fire scenario simulations
└── documentation/             # Technical documentation
    ├── system_specs/          # Technical specifications
    ├── user_manual/           # Operation guidelines
    └── compliance/            # Safety regulation compliance
```

## 🚀 Getting Started

### Prerequisites
- **Honeywell Fire System Software** (Version compatible with .etb files)
- **Building Management System** integration capabilities
- **Network Infrastructure** for system communication
- **Backup Power Systems** for emergency operation

### Installation & Configuration

1. **System Setup**
   ```bash
   # Load the Honeywell configuration
   load_config('Honeywell.etb')
   
   # Initialize detection zones
   initialize_zones()
   
   # Configure device parameters
   configure_devices()
   ```

2. **Zone Configuration**
   - Define individual room/area boundaries
   - Set detection sensitivity levels
   - Configure alarm response protocols
   - Establish inter-zone communication

3. **Simulation Setup**
   - Input building layout and dimensions
   - Define room connectivity and ventilation
   - Set environmental parameters
   - Configure fire scenario parameters

## 🔥 Fire Propagation Simulation

### Room-to-Room Analysis
The system simulates fire spread through:

#### **Physical Propagation**
- **Conduction**: Heat transfer through walls and structures
- **Convection**: Hot gas movement through openings
- **Radiation**: Heat transfer across spaces
- **Ventilation Impact**: HVAC system influence on spread

#### **Detection Timeline**
- **Initial Detection**: First sensor activation
- **Confirmation Period**: Multi-sensor verification
- **Propagation Prediction**: Estimated spread patterns
- **Evacuation Windows**: Safe egress time calculations

#### **Response Coordination**
- **Zone Isolation**: Compartmentalization strategies
- **Alarm Sequencing**: Phased evacuation procedures
- **System Integration**: Emergency lighting and HVAC control
- **Communication**: Emergency services notification

## 📊 System Specifications

| Component | Specifications |
|-----------|---------------|
| Detection Zones | Up to 200 individual zones |
| Device Capacity | 2000+ connected devices |
| Response Time | < 30 seconds from detection |
| Communication | RS-485, Ethernet, Wireless |
| Power Backup | 24-hour emergency operation |
| Temperature Range | -10°C to +70°C operation |

## 🧪 Testing & Validation

The system includes comprehensive testing for:
- ✅ **Sensor Functionality**: Individual device operation
- ✅ **Zone Communication**: Inter-zone data exchange
- ✅ **Alarm Coordination**: System-wide response testing
- ✅ **Propagation Accuracy**: Simulation model validation
- ✅ **Emergency Procedures**: Complete system response
- ✅ **False Alarm Prevention**: Intelligent detection algorithms

## 🤝 Industry Partnership

This project was developed in collaboration with:
- **Honeywell** - Industry expertise and system integration
- **Fire Safety Engineers** - Professional design consultation
- **Building Architects** - Structural integration requirements
- **Emergency Services** - Response protocol development

## 📚 Learning Outcomes

Through this project, we demonstrated expertise in:
- **Fire Safety Engineering**: Professional-grade system design
- **Computer Architecture**: Real-time system implementation
- **Simulation Modeling**: Physics-based fire propagation
- **System Integration**: Multi-component coordination
- **Safety Compliance**: Regulatory requirement adherence

## 🛠️ Technologies Used

- **Honeywell Fire System Platform** - Core detection and control
- **Building Information Modeling (BIM)** - 3D layout integration
- **Physics Simulation Engines** - Fire propagation modeling
- **Real-Time Operating Systems** - Time-critical response handling
- **Network Communication Protocols** - System interconnectivity

## 🔮 Future Enhancements

Potential improvements for this system:
- **AI-Powered Detection**: Machine learning for improved accuracy
- **IoT Integration**: Smart building connectivity
- **Mobile Applications**: Smartphone-based monitoring and control
- **Advanced Simulation**: CFD-based fire modeling
- **Predictive Analytics**: Risk assessment and prevention

## 📄 Compliance & Standards

This system complies with:
- **NFPA Standards**: National Fire Protection Association guidelines
- **EN Standards**: European fire safety requirements
- **Local Building Codes**: Regional safety regulations
- **Insurance Requirements**: Risk management standards

## 🙏 Acknowledgments

Special thanks to:
- **Honeywell** for their industry expertise and technology platform
- **Course Professors** for their guidance in computer architecture principles
- **Fire Safety Professionals** for their practical insights
- **Testing Facilities** for validation and compliance verification

---

**Course**: Computer Architecture  

**Institution**: Kadir Has University 

**Industry Partner**: Honeywell

**Project Focus**: Fire alarm system design with room-to-room propagation simulation for enhanced building safety and emergency response coordination.

For technical support or collaboration opportunities, please contact toprakkamburoglu@gmail.com
