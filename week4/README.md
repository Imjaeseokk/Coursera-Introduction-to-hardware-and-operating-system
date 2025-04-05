# Introduction to Hardware and Operating System

Coursera - IBM

Link to [Course](https://www.coursera.org/learn/introduction-to-hardware-and-operating-systems/)

Module 2

## Identifying Hardware Components and Peripherals 

### Learning Objectives
- Explain the difference between **internal** and **external components**
- Describe what a **peripheral device** is and what it does
- Understand and contrast the concepts of **interface**, **port**, and **connector**

---

### What is a Computer Component?

- A **component** is a physical part of the computer, also known as **hardware**
- Each component performs a specific function
- Components are classified as either:
  - **Internal** (inside the computer)
  - **External** (connected via ports)

#### Examples of Internal Components
- **RAM (Random Access Memory)**:
  - Temporary memory, used while power is on
  - Data is lost when power is shut off
- **Hard Drive**:
  - Permanent storage for files
  - Data is retained even when power is off
- **CPU (Central Processing Unit)**:
  - Performs mathematical calculations
  - Known as the "brain" of the computer
  - Faster CPU = more operations handled simultaneously

---

### What is a Peripheral?

- A **peripheral** is a device that connects to a computer to extend functionality
- Used for **data input**, **output**, or **storage**
- Can be easily connected and disconnected
- Connected through a **connector**

#### Types of Peripherals
1. **Input Devices**: send data to the computer  
   - e.g., Mouse, Keyboard
2. **Output Devices**: receive data from the computer  
   - e.g., Monitor, Printer
3. **Storage Devices**: store data permanently  
   - e.g., External Hard Drive, USB Flash Drive

---

### Connector vs. Port

- **Connector**: the end of a plug, jack, or card that connects into a port
  - Internal Example: Expansion card’s edge connecting to motherboard slot
  - External Example: USB plug at the end of a cable
- **Port**: the physical opening (jack/receptacle) on a computer where a connector is inserted
  - Ports are standardized
  - Common types include:
    - **USB (Universal Serial Bus)**
    - **HDMI (High-Definition Multimedia Interface)**

---

### Summary of Key Points

- A **component** is any physical hardware part necessary for computer operation
- **Internal components** include RAM, CPU, and hard drive
- **External components** include **ports** and **connectors**
- A **connector** fits into a **port**, and both enable communication between the computer and peripherals
- A **peripheral device** can connect either externally (e.g., USB printer) or internally (e.g., expansion card)



## Input and Pointing Devices

### Learning Objectives
- Compare various **input devices**
- Identify which devices use a **touchpad**
- Define a **pointing device**

---

### What is a Pointing Device?

- A **pointing device** is used to move the cursor and interact with objects on the screen
- All pointing devices send commands (as data) to the computer

#### Examples of Pointing Devices:
- **Mouse**  
- **Keyboard**  
- **Joystick**  
- **Touchpad**  
- **Trackball**  
- **Stylus / Pointing Stick**

---

### Input Devices Overview

#### Keyboard
- Primarily used for typing and data input
- Connects via **USB** or older **PS/2** port
- To add a new keyboard layout in Windows 10:
  1. Open **Settings**
  2. Go to **Time & Language → Language**
  3. Choose your preferred language → **Options**
  4. Under "Keyboards", click **Add a keyboard**

#### Mouse
- Most common pointing device
- Connects via **USB** or **Bluetooth**
- Cursor and sensitivity settings adjustable in Windows Settings

#### Touchpad
- Built-in pointing device on most laptops
- Can also be used externally via **USB** or **Wi-Fi**

#### Camera
- Captures digital images (also considered an input device)
- Usually built-in on laptops
- External cameras connect via **USB** or **Bluetooth**

#### Joystick
- Used for gaming, moves cursor and sends commands
- Connects via **USB** or **Bluetooth**

#### Trackball
- Stationary input device (alternative to mouse)
- Suitable for users with mobility limitations

#### Stylus / Pointing Stick
- Often used on tablets for navigation
- Works using **capacitive sensing** (detects heat and pressure)

---

### Summary of Key Points

- **Input devices** send data to the computer and move the cursor
- Common input devices: **keyboard, mouse, touchpad, joystick, trackball**
- **Touchpad** functions like a mouse and is typically built into laptops
- **Pointing devices** include any tool (mouse, stylus, etc.) that allows user interaction through cursor movement and command input

---


## Hard Drives

### Learning Objectives
- Identify an **internal storage device**
- Describe the **characteristics** of a hard drive
- Apply performance knowledge to choose the best hard drive

---

### What is a Storage Device?

- **Storage devices** store digital data (images, videos, audio, text)
- Two types of internal storage:
  - **ROM (Read-Only Memory)**:
    - **Non-volatile** (retains data without power)
    - Used for booting the computer and storing permanent data
  - **RAM (Random Access Memory)**:
    - **Volatile** (temporary memory)
    - Data is lost when power is off

---

### Hard Drive Overview

- **Hard drive = HDD (Hard Disk Drive)**: terms used interchangeably
- Stores data on **magnetic platters** using a **drive head**
- Form factors:
  - **2.5”**: Used in laptops and mobile devices
  - **3.5”**: Used in desktop computers (higher capacity)
- Common storage sizes:
  - From **500GB** to several **TB (terabytes)**

---

### Types of Hard Drives

- **SATA (Serial ATA)**: Most common interface, faster
- **PATA (Parallel ATA)**: Older, slower interface

---

### Performance Characteristics

| Metric          | Description                                   |
|-----------------|-----------------------------------------------|
| **Spin speed**  | Measured in **RPM**, common values: 5400 / 7200 |
| **Access time** | Time to locate data (typically 5–10 ms)        |
| **Transfer rate** | Speed of data transfer (in **MBps**)         |

---

### How to Check Disk Space (Windows 10)

1. Type **This PC** in the taskbar → Press **Enter**
2. Click **Open**
3. Under **Devices and drives**, view disk space availability

---

### How to Install an Internal Hard Drive

1. **Backup** data before installation
2. Transfer or remove **drive enclosure** if needed
3. Insert new HDD into the slot, secure with screws (2 per side recommended)
4. Connect HDD to motherboard via **SATA** or **PATA** cables
5. Connect **power supply** to the hard drive

---

### How to Configure Hard Drives (Windows)

1. Log in as **Administrator**
2. Right-click **My Computer** → Select **Manage**
3. Go to **Disk Management** in the console tree
4. Use **View menu** to customize layout (Top or Bottom panes)

---

### Summary of Key Points

- Hard drives store all types of digital media
- HDDs are considered **ROM** (non-volatile, permanent storage)
- Performance is determined by **RPM, access time, transfer rate**
- Choose your HDD based on required **capacity and speed**
- Follow correct installation steps and back up your data
- Configure HDD settings via **Disk Management** in Windows

---

## Optical Drives and External Storage

### Learning Objectives
- Understand how an **optical drive** records data
- Describe an **external storage device**
- Apply knowledge of **expansion devices** to choose the right option for your needs

---

### Optical Drives

- Use a **laser** to “burn” or press data onto a reflective disc surface  
- Create **pits** (recessed areas) and **lands** (raised areas)  
- **Single-sided** discs: one data layer  
  - DVD: ~4.7 GB  
  - CD: ~700 MB  
- **Double-sided** discs: two data layers → twice the capacity  
- Types of Optical Drives:
  - CD-ROM, CD-RW
  - DVD-ROM, DVD-RW
  - **Blu-ray**: up to 50 GB
- Writers (CD-R/DVD-R) use lasers for reading/writing

---

### Solid-State Drive (SSD)

- Uses **flash memory**, with **no moving parts**  
- Faster and more durable than HDDs  
- Serves as permanent secondary storage

---

### External Hard Drives

- Ideal for **backups and file transfers**  
- Store documents, music, videos, presentations, etc.  
- Connect via **USB** or **eSATA**  
  - eSATA: signal only (requires external power supply)
- Plug-and-play with Windows  
- File Explorer usually opens automatically

---

### Expansion Drives

- Provide **extra storage**  
- Connect via **USB**  
- Automatically recognized by Windows OS  
- Examples:
  - **USB flash drives**:
    - Flash memory with USB interface
    - Removable, rewritable
    - Storage up to **2 TB**
  - **Memory cards**:
    - Common formats: SD, MicroSD
    - Capacities: 32 GB, 64 GB, 128 GB, up to 512 GB

---

### Mobile Storage Devices

- **Portable media players** and **smartphones** handle digital media  
- File types: music, audiobooks, videos  
- **Internal memory**:
  - Fixed storage (e.g., 16GB, 32GB, 64GB)  
  - OS and pre-installed apps consume part of it
- **Expandable memory**:
  - Via **microSD cards** (if supported)
  - Important for users who store lots of files

---

### Summary of Key Points

- Optical drives use a **laser** to write data to discs
- External hard drives and USB drives are **solid-state** (no moving parts)
- SSDs are faster but more expensive than HDDs
- **Expansion storage** increases overall capacity via USB or memory cards
- Consider your **storage needs and budget** when selecting a device
- Mobile devices also serve as **portable media storage solutions**

---


## Display Devices

### Learning Objectives
- Define what a **display device** is  
- Identify different types of display devices (e.g., **CRT**, **LCD**, **touchscreen**, **projector**)  
- Adjust **screen resolution** and manage devices in **Windows Device Manager**

---

### What is a Display Device?

- A **hardware component** for the **visual output** of information
- Used in computers, televisions, mobile devices
- **Tactile monitors** are available for visually impaired users (fingertip-readable output)

---

### Types of Display Devices

#### CRT (Cathode Ray Tube)
- Analog display using **electron beams** to light up **phosphor dots**
- Common in older TVs and computer monitors (mid–late 1900s)
- Resolution: up to **800×600** or **1024×768**

#### LCD / TFT (Flat Screens)
- **Digital displays**, replacing CRT
- Use **pixels** controlled by electrical signals
- Lighter, thinner, sharper than CRT

#### Touchscreen
- Input + Output device
- Detects **heat and pressure** (capacitive technology)
- Used in **smartphones, tablets, laptops**

#### Projector
- Projects still or moving images from a computer onto a surface (e.g., wall, whiteboard)

---

### Resolution and Display Settings

- **Resolution** = clarity/sharpness of text and images  
  - Higher resolution (e.g., **1600×1200**) = sharper display
- Change in **Windows 10**:
  - Settings → System → Display → Adjust Resolution

---

### Device Installation and Management

- Windows supports **Plug-and-Play**
  - No restart needed for **hot-swappable** devices (e.g., monitors)
  - Windows auto-installs drivers when a display device is connected
- To **manually install drivers**:
  - Download from vendor website → Run setup program
- To **uninstall a display device**:
  1. Open **Device Manager**
  2. View → Show Hidden Devices
  3. Find device type → Right-click → Uninstall
  4. Optionally: **Delete the driver software**
  5. Click OK to complete

---

### Multiple Monitors (Windows 10)

- Connect monitors → Press **Windows + P**
- Choose:
  - **Duplicate**: same screen on both
  - **Extend**: extend display across monitors

---

### Summary of Key Points

- Display devices include **CRT**, **LCD/TFT**, **touchscreens**, and **projectors**
- CRTs are analog; LCDs and touchscreens are digital
- **Screen resolution** can be adjusted in Display Settings
- Plug-and-play makes device connection easy
- Use **Device Manager** to uninstall or manage display hardware

---

## Printers and Scanners

### Learning Objectives
- Describe the function of an **output device**
- Learn how to **install a printer** in Windows
- Identify different **types of printers**
- Understand what a **scanner** and **multifunction device (MFD)** do

---

### What is an Output Device?

- Hardware that converts processed data into **human-readable form**
- Output can be:
  - **Text**
  - **Graphics**
  - **Tactile (e.g., braille)**
  - **Audio**
  - **Video**

#### Examples of Output Devices:
- **Monitors**, **Printers**, **Speakers**, **Headphones**, **Projectors**
- Others: GPS devices, sound/video cards, optical mark readers, braille readers
- **Speech synthesizers**: produce verbal output (e.g., text-to-speech)

> A computer can run without an output device, but **you won’t be able to see or hear what it’s doing**.

---

### Printer Types

| Printer Type | Description |
|--------------|-------------|
| **Laser** | Uses heated unit to fuse toner on paper |
| **LED** | Similar to laser; uses a photoreceptive drum |
| **Inkjet** | Sprays microscopic ink droplets using thousands of tiny nozzles |
| **Thermal** | Heats special coated paper to create black text/images (used in POS, fax machines) |

#### Printer Connection Types
- **Local printer**: directly cabled to the device
- **Network printer**: accessed via **Wi-Fi** or **Ethernet**
- **IP-based printer**: used in networks (e.g., UNIX)
- **Web-based printer**: receives print jobs via Internet

---

### How to Install a Printer in Windows 10

1. Go to **Start → Settings**
2. Click **Devices → Printers & scanners**
3. Click **Add a printer or scanner**
4. Wait for available printers to appear
5. Select desired printer → Click **Add device**

---

### What is a Scanner?

- A **scanner** converts **analog input** (e.g., paper) into **digital images**
- Output formats include **PDF**, **JPEG**, etc.
- **Flatbed scanners** (place document on glass) were common
- Now often replaced by **Multifunction Devices (MFDs)**

---

### What is a Multifunction Device (MFD)?

- Combines:
  - **Printer**
  - **Scanner**
  - **Copier**
  - **Fax machine**
- Saves space and cost by integrating functions

---

### Summary of Key Points

- Output devices translate data into formats we can understand
- Printer types: **Inkjet, Laser, LED, Thermal**
- **Windows 10** printer installation is simple via Settings
- **Scanners** digitize documents for editing or archiving
- **MFDs** offer an all-in-one solution for offices and homes

---


## Audio and Visual Devices

### Learning Objectives
- Understand what **audio** and **visual devices** are
- Configure and use **speakers**, **microphones**, **headsets**, and **webcams** in Windows
- Learn connection methods and setup procedures for multimedia peripherals

---

### Audio Devices

Audio devices **reproduce, record, or process sound**.  
These include:

- **Speakers** (output device)
- **Microphones** (input device)
- **Headsets**
- Amplifiers, mixing consoles, CD players, effects units

#### Speaker Setup (Windows 10)
1. Right-click the **speaker icon** in the taskbar  
2. Click **Open Sound Settings**  
3. Under **Output**, choose your desired output device from the dropdown

#### Microphone Setup (Windows 10)
1. Connect your microphone  
2. Go to **Start → Settings → System → Sound**  
3. Scroll to **Input** and choose your microphone

#### Headphones / Headsets
- **Output device** used for private listening
- Connection methods:
  - **3.5mm analog jack** (green for audio out, pink for mic)
  - **USB** (for advanced audio features)
  - **Bluetooth** (wireless, tangle-free)

---

### Visual Devices

Devices that **display images electronically**.  
Examples include:

- **Monitors**
- **Laptops**
- **Smartphones**
- **Projectors**
- **Webcams**

#### Webcam Setup (Windows 10)
1. Press **Windows key** or click **Start**
2. Type `camera` in search bar and open **Camera app**
3. Webcam activates and shows a **live preview**

---

### Summary of Key Points

- **Audio/visual devices** enhance a computer's multimedia functionality  
- **Sound quality** of speakers depends on the **sound card**  
- **Headsets** come in various types: wired (3.5mm, USB) and wireless (Bluetooth)  
- **Modern webcams** offer **HD or 1080p** resolution and are essential for video conferencing  
- Devices can be easily configured via Windows **Sound** or **Camera** settings

---
































