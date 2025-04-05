# Introduction to Hardware and Operating System

Coursera - IBM

Link to [Course](https://www.coursera.org/learn/introduction-to-hardware-and-operating-systems/)

Module 3

## Identifying Ports and Connectors

### Learning Objectives
- Define what a **port** and **connector** are
- Differentiate between a **port** and an **interface**
- Identify **common ports and connectors** used in computing

---

### Definitions

- **Port**: A hole or slot on a computer that receives a connector to establish a physical link  
- **Connector**: The plug at the end of a cable or card that fits into a port  
- **Interface**: A point of communication between two entities, can be **hardware** or **software**  

---

### Common Interfaces and Ports

#### USB (Universal Serial Bus)
- Designed to standardize and simplify device connections
- Major versions:
  - **USB 1.0** (1996): 1.5–12 Mbps
  - **USB 2.0** (2001): 480 Mbps
  - **USB 3.0/3.1/3.2** (2008–2017): Up to 20 Gbps
  - **USB4** (2019): Up to 40 Gbps using **Type-C**
- Connector types:
  - **Type A**: Rectangular (keyboards, mice)
  - **Type B**: Square with beveled corners (printers, scanners)
  - **Mini USB**: Small, 9-pin (older mobile devices)
  - **Micro USB**: Smaller, 5-pin (newer small devices)
  - **Type-C**: Reversible 24-pin, supports high-speed data and power

#### Thunderbolt
- Developed by **Intel and Apple**
- Versions 1 & 2 use **Mini DisplayPort (MDP)** connector  
- Versions 3 & 4 use **USB-C** connector  
- Combines **data, display, and power** in one cable  
- **Supports daisy chaining up to 6 devices**  
- Thunderbolt 4 supports:
  - USB4 protocol
  - Dual 4K displays
  - Alternate hubs (not just daisy chaining)

#### FireWire (IEEE 1394)
- Legacy interface used on **Macintosh computers**
- Versions:
  - **FireWire 400**: Slim with one rounded edge  
  - **FireWire 800**: Looks similar to USB but thicker  
- Replaced by USB and Thunderbolt, but still in use in legacy/industrial systems

#### PS/2 Ports
- Introduced by IBM for connecting **keyboards and mice**
- Round with **6 pins**
- Color-coded and **not interchangeable**
- Still used in some industrial and gaming systems

#### eSATA / eSATAp
- Used for connecting **external storage devices**
- **Supports hot swapping**
- eSATAp supports **USB and eSATA** in one port
- Three generations, each doubling in data speed

---

### Summary of Key Points

- **Port** = physical slot for device connection  
- **Connector** = plug inserted into the port  
- **Interface** = communication link (hardware or software)  
- Key interfaces: **USB**, **Thunderbolt**, **FireWire**, **PS/2**, **eSATA**  
- **Type-C** and **Thunderbolt** are replacing older standards due to higher speed and flexibility

---


## Identifying Graphic Devices

### Learning Objectives
- Understand how **graphic devices (GPUs)** operate on a computer
- Recognize key characteristics of the **display system**
- Identify different types of **display connectors** and their uses

---

### Graphics Devices and GPUs

- **Graphics Processing Unit (GPU)** handles display communication
- **Integrated GPUs**: built into the motherboard, suitable for everyday tasks
- **Dedicated GPUs**: needed for 3D gaming, multimedia editing  
  - Popular chipsets: AMD Radeon, NVIDIA GeForce/nForce, Intel, SiS, VIA

---

### Display Quality Factors

| Factor         | Description |
|----------------|-------------|
| **Resolution** | Number of horizontal × vertical pixels (e.g., 1920×1080) |
| **Refresh Rate** | How fast screen updates (e.g., 60Hz, 120Hz) |
| **Bit/Color Depth** | Number of colors supported (e.g., 16-bit, 32-bit) |

- Higher values = sharper images, smoother video, more realistic colors  
- More processing power is required for higher display quality

---

### Display Types and Standards

- **CRT (Cathode Ray Tube)**:
  - 4:3 aspect ratio
  - VGA (640×480), SVGA (800×600), XGA (1024×768)

- **Modern LED displays**:
  - 16:9 widescreen
  - Resolutions:  
    - HD: 1280×720  
    - Full HD: 1920×1080  
    - 4K UHD: 3840×2160  
    - 8K: 7680×4320

---

### Display Connectors

#### HDMI (High Definition Multimedia Interface)
- Most widely used for audio/video
- Supports **CEC**, **HDCP**
- **19-pin** connector:
  - HDMI (standard)
  - HDMI Mini
  - HDMI Micro
- HDMI 2.1 supports **up to 8K resolution**

#### DisplayPort (by VESA)
- Royalty-free alternative to HDMI
- Uses **packetized data** for efficient transmission
- 20-pin connector; supports 7 transmission modes
- Common in high-end monitors and graphics cards

#### Thunderbolt (Intel + Apple)
- Combines display, data, and power in one cable
- Thunderbolt 1 & 2: Mini DisplayPort
- Thunderbolt 3 & 4: USB-C
- **Thunderbolt cables are not interchangeable** with regular USB-C

#### DVI (Digital Visual Interface)
- Uncompressed digital video; supports analog + digital
- Types:
  - **DVI-I**: integrated
  - **DVI-A**: analog only
  - **DVI-D**: digital only
- Single-link and dual-link formats (for higher resolutions)

#### VGA (Video Graphics Array)
- Legacy analog interface with **15-pin** connector
- Still supported on some devices, but outdated

---

### Other Connectors

- **Mini DisplayPort**: used by Apple, supports up to 4K
- **USB**: Some monitors/cameras use USB Type A or C
- **S-Video**: Used by old TVs and VCRs (analog)
- **Component RGB**: Splits analog video into 3 color signals, plus audio

---

### Summary of Key Points

- Computers need GPUs to render visuals on a display
- Display quality depends on **resolution, refresh rate, and bit depth**
- CRTs used 4:3 aspect ratio; modern displays use **16:9 LED screens**
- Connectors like **HDMI, DisplayPort, Thunderbolt, DVI, VGA** each offer unique advantages

---

## Identifying Audio Connectors

### Learning Objectives
- Understand how **audio devices** connect to a computer  
- List different types of **audio connectors**  
- Identify connectors by type: **TRS**, **Bluetooth**, **USB**, etc.

---

### Audio Devices and Sound Cards

- Computers use **internal expansion cards** (a.k.a. **sound cards**) to process audio  
- **Digital-to-Analog Converters (DACs)** allow analog devices to connect to computers  
- Use cases:
  - Listening to music
  - Recording/editing audio/video
  - Gaming
  - Presentations
  - Teleconferencing

---

### Common Audio Connection Types

| Connector Type        | Description |
|-----------------------|-------------|
| **Sound card ports**  | 3.5mm or 6.35mm TRS jacks |
| **Bluetooth**         | Wireless audio interface |
| **Game port (legacy)**| 15-pin MIDI/audio port, now obsolete |
| **USB**               | For headsets, microphones, interfaces |
| **External audio interface** | High-quality, multi-device professional use |

---

### Sound Card Ports

- Common labels and color codes:
  - **Light blue**: Line-in
  - **Pink**: Microphone-in
  - **Lime green**: Line-out (speakers/headphones)
  - **Black**: Rear speakers (surround)
  - **Orange**: Mid-surround (center/subwoofer)
- Accept:
  - **6.35mm TRS jack** (professional equipment)
  - **3.5mm TRS mini-jack** (consumer use)

---

### Bluetooth Connections

- Built-in on most modern laptops/desktops
- Can connect:
  - **Wireless headsets**
  - **Bluetooth speakers**
- USB Bluetooth **dongles** available for older systems

---

### Game Ports (Legacy)

- MIDI interface with **15-pin connector**
- Used for older gaming controllers and audio
- Now replaced by **USB-based controllers**

---

### External Audio Interfaces

- Connect **multiple devices** (mics, amps, speakers)
- Used in professional/studio settings
- Connect via:
  - **USB**
  - **FireWire**
  - **Thunderbolt**
- Require **specific drivers** for operation

---

### Summary of Key Points

- **Sound cards** process audio in/out with analog and digital signals  
- Audio devices connect via:
  - **TRS jacks**
  - **Bluetooth**
  - **USB**
  - **External interfaces**
- Older **game ports** are now obsolete  
- **External interfaces** offer high-quality multi-channel audio for professionals

---

### 스크립트 한국어 번역

**Identifying Audio Connectors** 강의에 오신 것을 환영합니다.  
이 영상을 시청한 후, 여러분은 오디오 장치가 컴퓨터에 어떻게 연결되는지 설명하고,  
다양한 오디오 커넥터의 유형을 나열하며,  
연결 방식에 따른 오디오 커넥터를 식별할 수 있게 됩니다.

---



## Wired and Wireless Connections

### Learning Objectives
- Understand how **devices communicate** through networks  
- Identify **wired vs. wireless** connections  
- Recognize key **connectors and technologies** (RJ-11, RJ-45, Wi-Fi, Bluetooth, RFID, NFC)

---

### Overview of Network Connections

- Devices communicate via **data packets**, similar to labeled envelopes  
- Networks can be:
  - **Closed (limited devices)** or  
  - **Open (e.g., the Internet)**  
- Connections are either:
  - **Wired** (Ethernet)
  - **Wireless** (Bluetooth, Wi-Fi, NFC, RFID)

---

### Wired Connections

#### RJ Connectors
| Type    | Use Case                      |
|---------|-------------------------------|
| RJ-11   | Telephones, handsets          |
| RJ-45   | Computers, modems, routers, POS terminals, gaming consoles |

- RJ connectors include a **plastic locking tab**  
- RJ-45 supports **Ethernet LANs**

#### Advantages of Wired Connections
- Faster: Up to **5 Gbps**
- **Stable & secure**: not affected by weather, no signal drop
- Less **interference** → fewer retransmissions
- More difficult to **hack**

---

### Wireless Connections

#### Wi-Fi
- Connects phones, computers, TVs to **Internet**
- Uses **wireless router** connected to modem
- Routers often **built-in** to modems now

#### Bluetooth
- Since 1998  
- Short-range (e.g., ~10m), uses **UHF radio**
- Devices connect via **pairing** with passkeys

#### RFID (Radio Frequency Identification)
- Uses **tags** and **readers**
- Range: **several hundred meters**
- Common uses:
  - **Toll booths**
  - **Pet/livestock ID**
  - **Retail checkout**
  - **Pharma tracking**

#### NFC (Near Field Communication)
- Evolution of RFID
- **Extremely short range** (a few cm)
- Requires **both devices to have NFC chips**
- More **secure and power-efficient**
- Use cases:
  - Hotel keycards, mobile payments, office access

---

### Wireless vs. Wired Networks

| Category          | Wired                       | Wireless                              |
|------------------|-----------------------------|---------------------------------------|
| Speed            | Faster                      | Slower, but improving                 |
| Setup            | Complex (cabling required)  | Easy and quick                        |
| Mobility         | Limited                     | **High mobility**                     |
| Scalability      | Costly, limited by wiring   | **Easy to expand**                    |
| Cost             | Higher                      | **More economical**                   |

---

### Summary of Key Points

- Devices connect via **wired (RJ-11, RJ-45)** or **wireless (Wi-Fi, Bluetooth, RFID, NFC)** technologies  
- Wired connections are **faster and more secure**, but less flexible  
- Wireless connections offer **mobility, easy setup, and scalability**  
- **NFC** is a secure, short-range evolution of RFID, used in tap-to-pay, access cards, etc.

---


## Peripheral and Printer Connections

### Learning Objectives
- List **common connection methods** for printers and peripherals  
- Understand how to connect via **serial, parallel, USB, and network** ports  
- Use **Windows Settings** to install and configure printers

---

### Recognizing Peripheral Devices

- Computers use **Plug and Play (PnP)** software to auto-detect peripherals  
- If PnP fails:
  - Visit **manufacturer’s website** to download drivers  
- **Generic drivers** may offer basic functionality  
- For advanced features (e.g., scan, fax), install **manufacturer-specific application software**

---

### Connection Methods

| Type                  | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| **USB**               | Most common wired connection (fast, simple)                                 |
| **Wi-Fi / Bluetooth / NFC** | Common wireless methods for peripherals                               |
| **Serial Port (RS232)**| Slow, older connection using 9-pin cable; long distance, noise-resistant   |
| **Parallel Port**      | Faster than serial; 25-pin cable; supports multiple bits simultaneously     |
| **Network**           | Wired (Ethernet) or wireless (Wi-Fi); allows multi-device access             |

---

### Serial & Parallel Ports

- **Serial Port (RS232)**:
  - 9-pin connector
  - Slower but long-distance capable
  - Screws used to secure connection

- **Parallel Port**:
  - 25-pin connector
  - Sends multiple bits at once
  - Also secured with side screws

---

### Network Printer Installation (Windows)

1. **Verify network connection**
2. Go to: `Settings > Devices > Printers & scanners`
3. Click: `+ Add a printer or scanner`
4. Let Windows detect or click:
   - `"The printer that I want isn't listed"` for manual setup
5. Select options for:
   - Older printers
   - Bluetooth printers
   - Network printers

---

### Summary of Key Points

- **Drivers** enable printer/computer communication  
- Basic features may work with generic drivers, but **full features need manufacturer software**  
- Serial (9-pin) and parallel (25-pin) connections are older but still in use  
- Use **Windows Settings** to detect or manually install printers  
- **Network printers** require active network connectivity and can be installed wirelessly or via Ethernet

---

## Installation Types

### Learning Objectives
- Define **hardware and software installation**
- Compare **Plug and Play (PnP)** vs. **manual driver installation**
- Understand **IP-based** and **web-based configuration**

---

### What Is Installation?

- **Installation**: Preparing hardware/software for use  
- Can vary by complexity:
  - Simple: Performed by general users
  - Complex: May require technical expertise

---

### Plug and Play (PnP)

- **PnP**: Automatically recognized and installed by OS  
- No need for user to manually install drivers  
- Common PnP devices: **Mouse, Keyboard, USB drives**  
- If not working:
  - Check **Device Manager** for issues (yellow warning icons)
  - Update the **driver** if outdated or malfunctioning

#### Steps to Update a Driver (Windows 10):
1. Search and open **Device Manager**
2. Expand device category
3. Right-click device → Select **Update driver**

---

### Manual Driver Installation

- Necessary when:
  - Device is not supported by default drivers
  - PnP fails
- Requires downloading driver from **manufacturer website**
- Sometimes needed to access **advanced features**

---

### IP-Based Peripherals

- Hardware that connects over **TCP/IP** network  
- Examples:
  - Wireless access points
  - IP security cameras
  - Network printers or print servers  
- Must be connected to **LAN or Internet** to operate

---

### Web-Based Configuration

- Common for **networking devices** (e.g., routers)  
- Setup is done via a **web interface** (e.g., http://192.168.0.1)
- Configuration options include:
  - Network name (SSID)
  - Passwords
  - IP settings

---

### Summary of Key Points

- Installation is required before use; **configuration** customizes settings  
- **PnP** offers faster setup than manual driver installs  
- **Driver installation** is sometimes needed for full device functionality  
- **IP-based** and **web-based** setups require **network/internet access**

---



## Practice Assigment & Graded Assignment
- 100점, 90점으로 pass

![image1](../images/week5_practice_assignment.png)

![image1](../images/week5_graded_assignment.png)


















