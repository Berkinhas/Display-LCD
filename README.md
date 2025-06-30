# Arduino LCD Display

---

## 🚀 Project overview

This project demonstrates how to control a 16x2 LCD display with an Arduino microcontroller. The main goal is to display predefined text and optionally interact with the user or sensors to display dynamic information.

---

## ✨ Features

* Static text display on LCD display.

---

## 🛠️ Required Materials

* **Arduino:** Uno
* **Display LCD:** LCD 16x2
* **Protoboard**
* **Jumper cables**
* **Resistor**
* **USB cable** for Arduino
* **Optional: Linear Potentiometer 10K** For contrast adjust

---

## ⚙️ Circuit Assembly

Below is a simplified diagram of how to connect the components.

![display lcd](https://github.com/user-attachments/assets/04c145bc-b20b-4865-ac3b-9825ee0a5f43)


**Common Connections**

* **LCD Paralel (no I2C):**
    * LCD GND pin → Protoboard negative (-) power rail
    * LCD VCC pin → Protoboard positive (+) power rail
    * LCD VO pin → Protoboard 38A
    * LCD R5 pin → Arduino 12
    * LCD RW pin → Protoboard negative (-) power rail
    * LCD E pin → Arduino -11
    * LCD D4 pin → Arduino -5
    * LCD D5 pin → Arduino 4
    * LCD D6 pin → Arduino -3
    * LCD D7 pin → Arduino 2
    * LCD BLA pin → Protoboard positive (+) power rail (Resistor)
    * LCD BLK pin → Protoboard negative (-) power rail
    * Resistor → connected A36 to Protoboard negative (-) power rail
    * Linear Potentiometer 10K → E37, E38, E39


---

## 💻 Code

The code for this project is located at `display.ino`.

**Library:**

* **LiquidCrystal.h**

---

## 🚀 How to Use

1. **Connect** the components according to the assembly diagram.
2. **Open** the `.ino` file in the Arduino IDE.
3. **Make sure** you have the necessary libraries installed.
4. **Select** the correct Arduino board in `Tools > Board`.
5. **Select** the correct serial port in `Tools > Port`.
6. **Upload** the code to your Arduino.
7. **Adjust the Potentiometer** (if applicable) to obtain the ideal contrast on the display.

---

## 🤝 Contributions

Feel free to **open issues** if you find any problems or have suggestions for improvements. Pull requests are always welcome!

---

## 📝 Licence

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## 📧 Contact

If you have any questions or suggestions, you can find me at:

* **GitHub:** [@Berkinhas](https://github.com/Berkinhas)
