## ⚡ Vending Machine - Digital Design

Vending Machine is a digital design project implemented in **VHDL**, focusing on simulating the behavior of an automated vending system.  
The design models item selection, coin insertion, change calculation, and product dispensing through modular hardware components.


## 📌 Project Description

This project represents a modular **vending machine system** using VHDL.  
It simulates a real-world vending process where a user can insert coins, select products, and receive either the product or change depending on the balance.  

The repository serves as an **educational demonstration** of applying digital design principles to model a **finite state machine (FSM)** for vending logic.


## 📚 Used Modules

🔄 **Finite State Machine (FSM)** – Controls the overall vending process (idle, waiting for coins, dispensing, giving change)  
💰 **Coin Input Module** – Accepts and validates inserted coins  
🛒 **Product Selection Module** – Handles product requests from the user  
📖 **Price & Balance Register** – Tracks inserted money and compares it with product price  
⚖️ **Comparator Module** – Determines if enough balance exists for product dispensing  
📤 **Dispensing Unit** – Delivers the selected product when conditions are met  
💵 **Change Return Module** – Returns excess coins if balance exceeds product price  
🧪 **Testbench** – Provides simulation scenarios to verify vending machine behavior  


## 🛠️ Technologies Used

📜 **VHDL** – Hardware description and system design  
🧩 **Simulation Tools** – ModelSim / Vivado (for testing and verifying behavior)  
