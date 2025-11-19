# Controls

The UI includes intuitive controls designed for education and data logging.

---

## ▶️ Start Recording

Begins logging all sensor data into memory.

- Sampling rate: device-dependent  
- Data includes all force, pressure, AOA, and airflow values  
- Recording continues until manually stopped

Ideal for:
- Sweep tests (AOA sweeps)
- Student data capture for lab reports

---

## ⏹ Stop Recording

Ends the logging session.

Stopping does NOT erase data — it simply finalizes the dataset for export.

---

## 📥 Download CSV

Exports the captured data into a CSV file for use in:

- Excel
- MATLAB
- Python (NumPy/Pandas)
- Jupyter notebooks

CSV columns include:
- Lift, Drag
- Pressures
- AOA
- Wind speed
- Timestamp

---

## ⚖️ Zero Scales

Tares all load cells and pressure sensors.

This sends the command: "tare"

Use this:
- Before every test  
- After mounting a new model  
- If readings drift slightly  

Zeroing ensures fair and repeatable results across student groups.


