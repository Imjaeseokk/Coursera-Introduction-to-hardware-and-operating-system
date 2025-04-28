# Introduction to Hardware and Operating System

Coursera - IBM

Link to [Course](https://www.coursera.org/learn/introduction-to-hardware-and-operating-systems/)

Module 4

## Internal Computer Components

### Learning Objectives
- Recognize **internal components** of a computer  
- Understand the role of the **motherboard**  
- Evaluate how **data flows** among internal systems

---

### Motherboard Overview

- The **motherboard** is the main printed circuit board (PCB)
- Hosts:
  - **CPU socket**
  - **RAM slots**
  - **Chipset (northbridge & southbridge)**
  - **I/O and peripheral connectors**
- Acts as the **communication backbone** of the computer

---

### Chipset Architecture

| Component     | Function |
|---------------|----------|
| **Northbridge** | High-speed communication (CPU ↔ RAM, GPU); directly connected to CPU |
| **Southbridge** | Slower components (USB, audio, BIOS); **not** directly connected to CPU |

- Together, the **chipset** manages data flow between CPU, memory, and peripherals

---

### Buses and Data Flow

- A **bus** is a high-speed pathway (printed circuitry) on the motherboard
- Transmits:
  - **Control signals**
  - **Addresses**
  - **Data**
- Example: **Front-Side Bus (FSB)**  
  - Connects CPU ↔ Northbridge (memory controller)

---

### CPU Socket Types

- **Socket**: Interface that connects CPU to motherboard
- Types of socket architecture:
  - **PGA (Pin Grid Array)**:
    - Pins on CPU, holes on socket
    - Align and insert carefully (no force)
  - **LGA (Land Grid Array)**:
    - Pins on motherboard, flat contact pads on CPU
    - Newer Intel CPUs typically use LGA

---

### Power Connectors

- Provide **electrical current** to motherboard and components
- **ATX connector**: A common large connector from power supply to motherboard
- Other connectors vary depending on form factor and power needs

---

### Summary of Key Points

- Internal components are all elements **attached to the motherboard**
- The **motherboard** facilitates communication between CPU, memory, and peripherals
- **Chipsets** (northbridge and southbridge) manage data flow across key areas
- **Buses** are internal highways for data/control signals
- **Sockets** allow CPUs to connect to the motherboard and vary by CPU generation
- **Power connectors** supply electricity to the board and its components

---




## Data Processing and Storage

### Learning Objectives
- Recognize the **role of memory** in a computing system  
- Distinguish between **memory slots** and **expansion slots**  
- Understand the functions of the **BIOS** and **CMOS**

---

### Central Processing Unit (CPU)

- CPU is a silicon chip with **billions of transistors**
- Executes calculations using data stored in memory
- **32-bit CPU**: 2-lane data bus  
- **64-bit CPU**: 4-lane bus → double the data per clock cycle  
- Found in laptops, desktops, and servers

---

### RAM and Memory Slots

- **RAM (Random Access Memory)**: Temporarily stores working data  
- Volatile → data lost when power is off  
- Installed in **memory slots** on the motherboard
- RAM is **cold pluggable** (must be powered off to install)

#### RAM Types:
| Type      | Description |
|-----------|-------------|
| **DRAM**       | Uses capacitors and transistors to store each bit |
| **SDRAM**      | Synchronous DRAM; faster than standard DRAM |
| **DDR / DDR3 / DDR4** | Double Data Rate; each generation is faster and more power-efficient |
| **SO-DIMM**    | Compact RAM used in laptops; smaller but uses more power |

- RAM speed: Measured in **MHz** (e.g., 1333–2133 MHz)

---

### Expansion Slots

- **Memory slots**: Only accept RAM  
- **Expansion slots** (e.g., **PCI / PCIe**):
  - Used for graphics cards, sound cards, network adapters
  - Add features and capabilities to the system
  - Number and type depend on **motherboard model**

---

### Disk Controller

- Allows CPU to communicate with storage devices
- Example: **IDE controller**
  - Chip-based circuit that manages hard drive read/write
  - Often includes cache memory for performance boost

---

### BIOS and CMOS

| Term    | Function |
|---------|----------|
| **BIOS** | Firmware that handles input/output processes during startup |
| **CMOS** | Memory chip that stores BIOS configuration settings |

- BIOS is **preprogrammed** on the motherboard
- Can be **updated ("flashed")** with correct version (check with manufacturer)
- CMOS powered by **coin-sized battery**
- When CMOS battery dies:
  - System clock resets
  - Hardware settings are lost

---

### Summary of Key Points

- Internal components like **CPU, RAM, BIOS, expansion cards** connect via the **motherboard**  
- RAM is stored in **memory slots** and varies by type, size, and speed  
- Expansion slots (PCI/PCIe) allow feature upgrades (e.g., graphics)  
- **BIOS** controls startup and I/O functions; **CMOS** stores its settings  
- **CMOS battery** must be replaced when expired to retain BIOS configuration

---


## Internal Storage

### Learning Objectives
- Describe **hard drive architecture** and data flow  
- Compare characteristics of **PATA, IDE, SATA, SCSI, SSD** drives  
- Understand **optical drive technologies**  
- Identify the role of **expansion slots** in storage

---

### Traditional Internal Hard Drives

- Introduced by **IBM in 1956**
- Provide **non-volatile**, long-term data storage
- Use **spinning platters** and **actuator arms** with read/write heads
- Key components:
  - **Power connector**: Supplies power
  - **Data connector**: Transfers data
  - **Jumpers**: Configures specific drive settings

---

### ATA, IDE, and PATA Drives

| Type   | Description |
|--------|-------------|
| **IDE / ATA**  | Popular from 1980s–2003 |
| **PATA**       | Parallel version of ATA |
| **Speed**      | Ranged from **33 Mbps to 133 Mbps** |

- Used **ribbon cables** for data connection

---

### SATA Drives

- Introduced in **2003**, using **serial bus**
- **Much faster** than ATA: up to **6 Gbps**
- **Common RPMs**: 5400 / 7200
- **Capacity**: 250 GB to 30+ TB
- Standard for **modern desktops and laptops**
- **Each SATA port supports one drive**

---

### SCSI Drives

- Known as "**scuzzy**"
- Introduced in **1986**
- Fast (10,000–15,000 RPM)
- Discontinued around **1994**

---

### Solid-State Drives (SSD)

- Introduced in **1989**
- Store data on **non-volatile flash memory**
- Faster than HDDs (up to **10–12 GB/s**)
- **Capacity**: 120 GB to 2 TB (typically)
- **More reliable** but more expensive than SATA
- Also used in:
  - **External drives**
  - **Hybrid drives** (SSD as cache + SATA as storage)

---

### Optical Drives

- Use **CDs, DVDs, Blu-ray Discs**
- Write/read via **low-powered laser beam**
- Store data in **tiny pits on spiral tracks**

#### Formats and Capacities

| Format     | Storage             | Notes                        |
|------------|---------------------|------------------------------|
| **CD**     | Up to 750 MB        | Single-sided                 |
| **DVD**    | 4.7–17.1 GB         | Single or dual-sided         |
| **Blu-ray**| 25–128 GB (per layer) | High-res video/audio, DRM by region |

- **BD-XL** drives needed for triple/quad-layer Blu-rays

---

### Expansion Slots

- On the motherboard, used for:
  - **Adding storage controllers**
  - **Supporting additional drives**

---

### Summary of Key Points

- **Internal hard drives** offer fast access and long-term, non-volatile storage
- **SATA** drives are standard today due to cost-efficiency and capacity
- **SSDs** are faster and more reliable but costlier
- **Optical drives** offer portable storage and are still used for media
- **Blu-ray Discs** support high-resolution content and regional protection
- **Expansion slots** allow extending storage capabilities via add-on cards

---

## Display Cards and Sound Cards

### Learning Objectives
- Define the function of a **video card (GPU)**  
- Understand how **sound cards** handle audio signals  
- Evaluate the role of **MIDI controllers** in audio production

---

### Video Cards (Graphics Cards)

- Also called:
  - **Display adapter**, **Graphics card**, **Video adapter**, **GPU**
- May be:
  - **Integrated** (on the motherboard)
  - **Dedicated** (plugged into an expansion slot)

#### Functions:
- Sends **graphical data** to:
  - **Monitors**, **TVs**, **Projectors**
- Uses a **Graphics Processing Unit (GPU)** to:
  - Accelerate **graphics rendering**
  - Perform **parallel processing** for:
    - Gaming
    - Video editing
    - Machine learning

---

### Sound Cards (Audio Cards)

- Generate and process **audio signals**
- Functions:
  - **Analog-to-digital conversion (ADC)**:
    - E.g., Microphone → Digital file
  - **Digital-to-analog conversion (DAC)**:
    - E.g., MP3 → Speaker output
- Can be:
  - **Integrated** on the motherboard (common in most PCs)
  - **Dedicated** expansion cards (for higher quality sound)

---

### MIDI Controllers

- **MIDI (Musical Instrument Digital Interface)**: Standard for digital musical instruments
- MIDI Controller:
  - Sends digital signals to PC or synthesizer
  - Allows sequencing, recording, and virtual instrument control
- Commonly used by **musicians** for composing and producing music

---

### Summary of Key Points

- **Video cards (GPUs)** process and send image data to displays  
- **Sound cards** convert audio signals between analog and digital  
- Integrated audio is usually sufficient for general users  
- **Dedicated sound cards** are preferred for audio production  
- **MIDI controllers** are essential tools for digital musicians, sending control signals to PCs and sound modules

---



## Cooling and Fans

### Learning Objectives
- Define **system cooling**
- Compare **air cooling**, **passive cooling**, and **liquid cooling**
- Evaluate the **efficiency and trade-offs** of liquid cooling

---

### What Is System Cooling?

- Computers generate heat during operation
- **System cooling** prevents **overheating** of internal components
- Without proper cooling, parts like the **CPU** can be **damaged**

---

### Cooling Methods

#### 1. Passive Cooling
- Slows down the **component's operating speed** to reduce heat
- No moving parts (e.g., simple heatsinks without fans)

#### 2. Active Cooling (Air Cooling)
- Uses **powered fans** to move air through the case
- Cool air drawn in from **front vents**, hot air expelled out the **back**
- **Forced convection** with **heatsink + fan** setup:
  - **Thermal paste** fills microscopic gaps for better heat transfer
  - Fan blows air over **heatsink fins** to dissipate heat

#### 3. Liquid Cooling
- Similar to **radiator systems** in cars
- Circulates **liquid through water blocks** placed on hot chips (e.g., CPU, GPU)
- Heated liquid → **radiator** → cooled via **fans** → recirculates
- **Quieter and more efficient**, especially for:
  - **High-performance PCs**
  - **Hot environments**

---

### Advantages and Disadvantages of Liquid Cooling

| Advantage                 | Disadvantage                        |
|--------------------------|-------------------------------------|
| Quiet operation           | Higher cost                         |
| Efficient heat transfer   | Risk of **leakage** inside system   |
| Effective in **high-heat** setups | Requires more maintenance        |

---

### Summary of Key Points

- **System cooling** is essential to protect components from heat damage  
- **Air cooling** uses heatsinks, thermal paste, and fans  
- **Passive cooling** slows down performance to reduce heat  
- **Liquid cooling** is quieter and more effective, but costly and riskier  
- Best choice depends on **system use**, **heat level**, and **budget**

---





