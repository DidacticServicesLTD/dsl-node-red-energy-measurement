# DSL Node-RED Energy Measurement

A comprehensive Node-RED project developed by **Omid Teimoori** at **Didactic Services Ltd (DSL)**, focused on real-time energy monitoring and optimisation within a Cyber-Physical System (CPS) environment. The system communicates via OPC UA with a Siemens ET200SP PLC and a Festo EMB (Energy Measurement Box).

## Features

- Real-time dashboards for:
  - **Active Power**
  - **Compressed Air Flow**
  - **Compressed Air Pressure**
- Energy consumption analysis with historical tracking
- Dynamic electricity billing using configurable **day/night rates**
- Tree-based visualisation of carbon offset from energy savings
- Logging to local **SQLite** database
- OPC UA communication with:
  - Siemens ET200SP PLC
  - Festo EMB at `172.21.0.60/18`

## Network & Access Info

- **Festo EMB IP Address:** `172.21.0.60`  
- **Network Subnet:** `255.255.192.0 (/18)`  
- **Node-RED Port:** `18891`  
- **Node-RED Login:**
  - **Username:** `admin`
  - **Password:** `Festo4.0`

Ensure your device is connected to the same subnet to access the OPC UA server and Node-RED interface.

## Project Structure

- `dsl-node-red-energy-measurement.json` / `dsl-node-red-energy-measurement_cred.json`: Flow configurations
- `settings.js`: Custom Node-RED settings
- `package.json`: Node dependencies
- `public/`: Static assets including DSL branding
- SQLite data logging handled within flows

## Developed By

**Omid Teimoori**  
**Didactic Services Ltd (DSL)**  
<https://www.didacticservices.co.uk>

---

For questions or issues, feel free to contact: **support@didacticservices.co.uk**
