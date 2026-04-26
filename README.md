# Neuron/IC Controlled Line Follower Car

A hardware-based neural network robot that follows a line without using any microcontroller or software.

## 🚀 Overview

This project demonstrates how a simple **analog neural network** can control a mobile robot in real time. Instead of using traditional programming or digital algorithms, the system mimics the behavior of biological neurons using electronic components.

The result is a fast, responsive, and reliable **line-following robot** controlled entirely by hardware.

---

## 🧠 Key Idea

The control system is inspired by **biological neurons**:

- Inputs (sensors) → act like dendrites  
- Signal integration → performed by analog circuits  
- Threshold behavior → implemented using Schmitt triggers  
- Outputs → control motors directly  

No software. No microcontroller. Just physics and electronics.

---

## ⚙️ Features

- 🔌 Fully analog control system (no programming)
- ⚡ Real-time response with minimal latency
- 🧩 Simple and understandable architecture
- 🔄 Smooth and continuous motor control (no discrete switching)
- 🛠️ Built from commonly available components

---

## 🧱 Hardware Components

Main components used:

- IR sensors (TCRT5000) – line detection
- NPN transistor (2N3904)
- MOSFET (BS170)
- Schottky diode (1N5819)
- Optocoupler (LTV816) – synapse simulation
- Schmitt trigger inverter (74HC14)
- Resistors (synaptic weights)
- Capacitors
- DC motors with gearbox
- Custom PCB

---

## 🧬 Neural Network Architecture

- **5 input neurons** (IR sensors)
- **2 output neurons** (left & right motor)
- Fully connected structure
- Synaptic weights implemented with resistors

### Behavior:

- Center sensor → forward movement
- Left sensors → adjust right motor
- Right sensors → adjust left motor
- Cross-wiring enables automatic steering

---

## 🔧 How It Works

1. Sensors detect reflected IR light from the surface
2. Analog voltage signals are generated
3. Signals are processed by neuron circuits
4. Threshold logic (Schmitt trigger) determines activation
5. Output neurons control motor speed directly

The robot naturally follows the line without any calculations or code.

---

## 🧪 Development Process

- Studied biological neuron behavior
- Designed analog neuron circuits
- Built and tested on breadboard
- Tuned resistor values for stability
- Designed and etched custom PCB
- Iterated design multiple times (7 versions)

---

## 📊 Results

- Stable and smooth line following
- Fast response to direction changes
- No software delays or computation overhead
- Reliable operation after tuning

---

## 💡 Advantages

- No software bugs
- Very fast response time
- Low complexity
- High reliability
- Educational value for electronics and neuroscience

---

## 🔮 Future Improvements

- More complex neural architectures
- Adaptive or learning circuits
- Integration with hybrid (analog + digital) systems
- Miniaturization

---

## 📚 References

- The Art of Electronics – Horowitz & Hill
- Neuroscience – Dale Purves
- Analog VLSI and Neural Systems – Carver Mead
- Medical Physiology – Otomar Kittnar

---

## 👨‍💻 Author

**Lóránt Majer**  
Electrotechnics student  
Specialization: Power Engineering  

---

## 📸 Project Preview

(Add photos or videos here)**

---

## 📌 Summary

This project proves that **complex behavior does not always require complex code**.  
A well-designed analog system can be just as effective, faster, and more elegant.
