# Water-4.0
# Water4.aasx – AAS Models of the Integrated Urban Water System

This repository contains the `Water4.aasx` file, a package of Asset Administration Shell (AAS) models developed to digitally represent the infrastructures of the **urban water system**, in line with the **Industry 4.0** paradigm and the **RAMI 4.0** reference architecture.

## 🧭 Purpose

The project aims to support the digitalization of water networks through the adoption of **modular, interoperable, and traceable digital twins**, implemented using the official tool **AASX Package Explorer**. The models in this repository can be used for:

- representing physical and logical components (pumps, valves, tanks, pipes, plants)
- integrating digital operations (e.g., startPump, quality monitoring, remote control)
- enabling distributed architectures based on OPC UA and MQTT
- reusing components within **Eclipse BaSyx**, **AASX Package Explorer**

## 📁 Contents of `Water4.aasx`

The `.aasx` file includes models of the following types:

### 🔧 **Basic Models**
- `PumpDriver_Type`
- `WaterPump_Type`
- `Valve_Type`
- `Tank_Type`
- `Pipe_Type`
- `ModularComputingSystem_Type`
- `CommunicationSystem_Type`
- `ProtocolComunication_Type`

### 🧩 **Composite Models**
- `PumpingSystem_Type`
- `WaterSupplySystem_Type`
- `WaterDistributionSystem_Type`
- `RawWaterStorage_Type`
- `WaterTreatmentFacility_Type`
- `WaterTransmissionSystem_Type`
- `RawWaterPumpingFacility_Type`
- `WasteWaterCollectionSystem_Type`
- `WasteWaterTreatmentSystem_Type`
- `WasteWaterManagement_Type`
- `IntegratedUrbanWaterManagementSystem_Type`


Each model includes:
- `Identification`, `TechnicalData`, `Documentation`
- `Operations` (callable via REST or delegation)
- `Capabilities`, `Sensors`, `Maintenance`
- `Components` and `ReferenceElements` for hierarchical structuring

## 🛠️ Requirements

- [AASX Package Explorer v2024-05-08](https://github.com/eclipse-aaspe/package-explorer/releases/tag/v2024-05-08.alpha)


