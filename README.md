# Mini CNC Plotter from Old CD Drives 🖊️💿

This project turns old CD/DVD drives into a compact, low-cost **CNC Plotter** using an Arduino. It can draw basic shapes, logos, and text using G-code commands and is perfect for hobbyists and makers looking to upcycle electronics.

---

## 🔩 Components

- Arduino Uno
- 2× CD/DVD drive stepper motors (X & Y axes)
- 1× Servo motor (for pen up/down – Z-axis)
- CNC Shield + A4988 stepper drivers (optional but recommended)
- External 12V power supply
- Breadboard, wires, pen holder
- Basic frame (acrylic, cardboard, or 3D printed)

---

## 🛠️ How It Works

- CD drive stepper motors provide 2-axis movement
- Servo motor lifts and drops the pen
- G-code commands tell the machine what to draw
- Arduino (with GRBL firmware) processes instructions and drives the motors

---

## 🧪 Setup Instructions

1. **Assemble the hardware:**
   - Mount both CD drive sleds in X and Y configuration
   - Fix a pen with a servo for vertical movement
2. **Upload GRBL:**
   - Flash GRBL firmware to Arduino using Arduino IDE
3. **Wiring:**
   - Connect stepper motors to CNC shield or directly to drivers
   - Connect servo to a PWM pin on Arduino
4. **Software:**
   - Generate G-code using Inkscape (with G-code extension)
   - Send G-code to Arduino using Universal G-code Sender (UGS)

---

## 📂 Project Structure

