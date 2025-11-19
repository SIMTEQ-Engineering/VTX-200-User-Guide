# VTX-200 Wind Tunnel UI – User Manual

[![Docs Status](https://img.shields.io/badge/docs-stable-success)](#)
[![Docs Version](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2FSIMTEQ-Engineering%2FVTX-200-User-Guide%2Fmain%2Fdocs%2Fversion.json&label=docs%20version&query=%24.version&prefix=v)](CHANGELOG.md)
[![Issues](https://img.shields.io/github/issues/SIMTEQ-Engineering/VTX-200-User-Guide)](https://github.com/SIMTEQ-Engineering/VTX-200-User-Guide/issues)
[![Discussions](https://img.shields.io/github/discussions/SIMTEQ-Engineering/VTX-200-User-Guide)](https://github.com/SIMTEQ-Engineering/VTX-200-User-Guide/discussions)
[![License](https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-informational)](LICENSE)

---

This repository contains the **official user manual** for the **VTX-200 Wind Tunnel Web App**, developed and maintained by **Simteq Engineering**.

> ⚠️ **Note:**  
> This repository contains **documentation only**.  
> The VTX-200 UI software is **proprietary** and is distributed only with authorized hardware.

---

## Overview

The VTX-200 UI is a browser-based dashboard for:

- Real-time lift & drag measurement  
- Pressure readings (pitot/static)  
- Angle-of-attack monitoring  
- Wind speed visualization  
- Data logging and CSV export  
- Zeroing/tare functions  

The user interface is **pre-installed** on your VTX-200 wind tunnel controller—no software installation is required.

---

## Accessing the Web App

1. Power on your VTX-200 wind tunnel controller.  
2. Connect your device to the controller’s Wi-Fi network:

   - **SSID:** `WindTunnel_AP`  
   - **Password:** `12345678`

3. Open a browser and go to:

   ```
   http://192.168.4.1
   ```

---

## Dashboard Layout

### **Lift & Drag Card**
- Displays real-time load cell data.
- Toggle between **Wall** and **Floor** balance readings.

### **Pressure Card**
- Shows pitot/static pressure readings.

### **Angle of Attack**
- Displays the current AOA (degrees).

### **Wind Speed**
- Shows real-time airspeed derived from pressure.

---

## Controls

### **Start Recording**
Begins logging all incoming sensor data.

### **Stop Recording**
Ends the logging session.

### **Download CSV**
Exports the recorded session for Excel, MATLAB, Python, etc.

### **Zero Scales**
Tares the balance system.

**Command sent to controller:**  
```
"tare"
```

---

## Interpreting Data

### **Lift & Drag**
Displayed in either:
- grams (g), or  
- Newtons (N)  

(based on device configuration)

### **Pressure**
Raw and derived pressure values from built-in sensors.

### **Angle of Attack**
Reported in degrees (°).

### **Wind Speed**
Reported in meters per second (m/s).

---

## Best Practices

- Always **zero/tare** the balance before each test.  
- Allow readings to stabilize before recording.  
- Download your CSV **after each session** to avoid data loss.  
- Ensure the VTX-200 controller has a stable power supply during tests.

---

## Troubleshooting

### Web App Not Loading
- Confirm connection to `WindTunnel_AP`
- Try refreshing the browser
- Ensure the controller is powered on
- Test using a different phone/tablet/laptop

### No Live Data
- Confirm sensors are correctly connected
- Verify wiring to load cells and pressure sensors
- Try using **Zero Scales** to reinitialize

---

## Changelog & Versioning

- The **docs version badge** at the top reads from:

  ```
  docs/version.json
  ```

- `CHANGELOG.md` contains all user-visible changes across releases.

👉 See: [`CHANGELOG.md`](CHANGELOG.md)

---

## Community & Support

### Issues
Use GitHub Issues for:
- Bug reports  
- Clarification questions  
- Documentation errors  

👉 https://github.com/SIMTEQ-Engineering/VTX-200-User-Guide/issues

### Discussions
Use Discussions for:
- Q&A  
- Feature ideas  
- Announcements  

👉 https://github.com/SIMTEQ-Engineering/VTX-200-User-Guide/discussions

---

## Contact

**Simteq Engineering**  
📧 info@simteq.co.za  
🌐 https://www.simteq.co.za

---

## License (Documentation Only)

This documentation is licensed under:

**Creative Commons CC BY-NC-SA 4.0**  

The **VTX-200 software** is *not* open source and is only distributed with official hardware.
