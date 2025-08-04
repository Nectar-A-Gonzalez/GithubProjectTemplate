# ⚡ Electronics Documentation

This file documents the electrical layout, circuit interfaces, power management, and custom PCB notes.

---

## 📋 System Overview

| Subsystem          | Description                       |
|--------------------|-----------------------------------|
| Power Distribution | [e.g., Battery to ESC to motors]  |
| Signal Logic       | [e.g., PWM to ESC, I2C to sensors]|
| Protection         | [e.g., Fuses, TVS diodes]         |

---

## 🔌 Wiring Diagram

- [Insert image from /docs or describe wiring path]
- [Include cable gauge, connector types]

---

## 📦 Components List

| Component        | Model / Value    | Quantity | Notes                 |
|------------------|------------------|----------|------------------------|
| [Battery]        | 4S LiPo 2200mAh  |    1     | [Main power source]    |
| [ESC]            | 30A Brushless    |    2     | [For drive motors]     |
| [...]            | [...]            |   ...    | [...]                  |

---

## 🛠 Assembly & Testing

1. [Connect ESCs to motors and receiver]
2. [Test continuity before powering]
3. [Check LED indicators and voltages]

---

## 🐞 Troubleshooting

| Issue             | Possible Cause             | Fix                          |
|-------------------|----------------------------|-------------------------------|
| No power to ESC   | Loose battery connector    | Check XT60 plug or fuse       |
| Signal not received| Incorrect PWM wiring      | Confirm channel and polarity  |
