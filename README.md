# 🚗 Automotive ECU Thermal Management System

An automotive engine thermal management system designed using MATLAB/Simulink and Stateflow for ECU-based closed-loop temperature control.

The system dynamically regulates engine cooling using a finite state machine (FSM) and multi-level fan control strategy to maintain optimal engine operating temperature under varying conditions.

---

## 🚀 Features

- Closed-loop thermal control system
- ECU-oriented control logic
- Stateflow-based finite state machine (FSM)
- Multi-level cooling fan control
- Dynamic temperature regulation
- Stable thermal response
- Real-time state transitions
- Automotive control system modeling

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| MATLAB | System Modeling |
| Simulink | Dynamic Simulation |
| Stateflow | FSM Control Logic |

---

## ⚙️ System Working

1. Engine temperature is continuously monitored.
2. Temperature feedback is provided to the control system.
3. Stateflow FSM determines the operating state.
4. Cooling fan speed changes dynamically:
   - OFF
   - MEDIUM
   - HIGH
5. The controller maintains engine temperature within safe operating limits.

---

## 🔄 Control Strategy

### Closed-Loop Feedback Control
The controller continuously adjusts cooling behavior based on real-time temperature feedback.

### Finite State Machine (FSM)
The cooling system transitions between multiple operating states depending on engine temperature thresholds.

### Multi-Level Fan Logic
Different fan speed levels improve thermal stability and reduce unnecessary power consumption.

---

## 📊 System Outputs

- Temperature vs Time Response
- State Transition Behavior
- Stable Thermal Regulation
- Smooth Fan Speed Switching

---

## 📷 Project Preview

Add simulation screenshots here.

Example:

![Simulink Model](images/simulink-model.png)

---

## 📂 Repository Contents

- Simulink Models
- Stateflow Charts
- Simulation Results
- Documentation
- Images

---

## 🚘 Applications

- Automotive ECU Systems
- Engine Cooling Systems
- Electric Vehicle Thermal Systems
- Embedded Control Systems
- Smart Automotive Electronics

---

## 📈 Engineering Concepts Demonstrated

- Closed-Loop Control Systems
- Automotive ECU Logic
- State Machine Design
- Thermal System Modeling
- Control Stability
- Dynamic System Simulation
- Model-Based Design (MBD)

---

## 🔮 Future Improvements

- PID-Based Adaptive Cooling
- CAN Bus Integration
- Sensor Fault Detection
- AI-Based Thermal Prediction
- Hardware-in-the-Loop (HIL) Testing
- EV Battery Thermal Management

---

## 👨‍💻 Author

Ravi Jangra
