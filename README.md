# ⚙️ Servo Motor Control System using MATLAB Simulink

📌 This project models and simulates a **servo motor control system** using MATLAB Simulink with a **PI controller**.

---

## 🚀 Project Overview

🎯 Objective of this project:

- ⚡ Model a DC motor using differential equations  
- 🎛 Design a PI controller  
- 📊 Simulate system performance  
- 📈 Analyze system response  

💡 This project demonstrates concepts from **Control Systems & Electrical Engineering**.

---

## 🧠 System Components

### 🔹 ⚡ DC Motor Model

The DC motor is modeled using:

📘 **Electrical Equation:**
L(di/dt) + Ri = V(t) − K(dθ/dt)

📘 **Mechanical Equation:**
J(d²θ/dt²) + b(dθ/dt) = Ki

---

### 🔹 🎛 PI Controller

The controller is implemented using difference equations:

yₚ(k) = kₚ · e(k)  
yᵢ(k) = yᵢ(k−1) + kᵢ · Tₛ · e(k)  
y(k) = yₚ(k) + yᵢ(k)

---

## ⚙️ Parameters Used

### ⚡ Motor Parameters

| Parameter | Value |
|----------|------|
| J | 5e-5 |
| K | 0.2 |
| L | 0.01 |
| R | 4 |
| V | 7.4 |
| b | 0.0005 |

### 🎛 Controller Parameters

| Parameter | Value |
|----------|------|
| kp | 9.39 |
| ki | 7.33 |
| Ts | 0.01 |

---

## ⚙️ Modeling Steps

1️⃣ Rearrange differential equations  
2️⃣ Add integrator blocks  
3️⃣ Label signals  
4️⃣ Construct system model  
5️⃣ Set initial conditions  

---

## 📊 Features

- ⚡ DC motor mathematical modeling  
- 🎛 PI controller implementation  
- 📉 Simulink-based simulation  
- 📈 Control system analysis  

---


---

## 🛠️ Tools Used

- 🧮 MATLAB  
- 🔗 Simulink  

---

## 🚀 Future Improvements

- 🔁 Add PID controller  
- 🧪 Hardware implementation  
- ⏱ Real-time control  
- 🚗 EV motor control application  

---

## 👨‍💻 Author

**Dhruv Suthar**  
⚡ Electrical Engineering Student  
🤖 AI | 🚗 EV | 🎛 Control Systems Enthusiast  

---

⭐ If you found this project useful, give it a **star** on GitHub!


