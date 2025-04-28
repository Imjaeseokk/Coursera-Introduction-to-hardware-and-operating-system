# Introduction to Hardware and Operating System

Coursera - IBM

Link to [Course](https://www.coursera.org/learn/introduction-to-hardware-and-operating-systems/)

Module 5

## Evaluating Computing Performance and Storage

### Learning Objectives
- Identify the **four key processor performance factors**
- Evaluate **RAM availability and usage**
- Assess **storage capacity** and device types
- Understand **network speed** metrics and troubleshooting methods

---

### Processor Performance Criteria

1. **Processor Speed (Clock Speed)**
   - Measured in **GHz** (Gigahertz)
   - Higher speeds → faster task execution

2. **Number of Cores**
   - CPUs may have **2 to 64 cores**
   - More cores allow **parallel task execution**
   - Related to **Symmetric Multiprocessing (SMP)**

3. **Bus Types and Speeds**
   - **Address bus**: sends memory addresses
   - **Data bus**: carries data
   - **Control bus**: sends control signals
   - New standards: **PCIe**, **HyperTransport**, **QPI**

4. **Cache Memory**
   - Stores frequently used data for quick access
   - Helps offset slower processing speeds

---

### RAM (Random Access Memory)

- Temporary memory used to run apps, load websites, and edit files
- Measured in **GB (Gigabytes)**
- When RAM is full:
  - Freezing, app crashes, blue screen, corrupted files

#### How to Check RAM in Windows:
- Open **Task Manager → Performance → Memory**
- Run **Windows Memory Diagnostic** for hardware issues

---

### Storage Devices

| Type            | Speed      | Notes                                   |
|------------------|------------|------------------------------------------|
| **SSD**          | Fastest    | Flash-based, expensive but reliable      |
| **HDD**          | Moderate   | Traditional spinning disks               |
| **Hybrid Drives**| Balanced   | SSD for cache + HDD for storage          |
| **Flash Memory** | Varies     | Portable (e.g., USB, SD cards)           |

#### How to Check Disk Space:
- Open **This PC** from taskbar search → View under "Devices and Drives"

---

### Network Speed & Connectivity

- Measured in **Mbps** or **Gbps**
- Use tools like **speedtest.net** to evaluate performance

#### How to Check Link Speed:
- **Wi-Fi**:
  - Click **Wi-Fi icon → Properties → Link Speed**
- **Ethernet**:
  - Search **Ethernet Settings** in Windows → View under Properties

---

### Summary of Key Points

- **Processor performance** depends on speed, cores, bus type, and cache  
- **RAM availability** impacts stability and multitasking  
- **SSD > Hybrid > HDD** in terms of speed  
- **Check storage and RAM** usage directly in Windows tools  
- Use **speed tests and network settings** to assess connectivity issues

---


## Workstation Evaluation and Setup

### Learning Objectives
- Identify a user’s **computing environment and requirements**
- Evaluate computers based on **hardware specifications**
- Perform **basic workstation setup tasks**

---

### Step 1: Understanding the User’s Needs

#### Location
- **Office**, **home**, **mobile**, or **multi-site**

#### Physical Conditions
- Desk, chair, **lighting**, **outlets**, **security options**, **accessibility accommodations**

#### Connectivity
- **Wired** for secure/confidential work  
- **Wi-Fi** for general office/home use  
- **Cellular** for mobile users

#### Data Storage Strategy
- **Local**, **onsite network**, or **hybrid cloud**

---

### Step 2: Hardware & Peripheral Needs

| Component     | Considerations                         |
|---------------|----------------------------------------|
| **RAM**        | 8 GB (web-based users), 16 GB (standard), upgradeable (power users) |
| **GPU**        | Required for graphics, big data tasks  |
| **Storage**    | Adequate for local files or cache use  |
| **Peripherals**| Keyboard, mouse, monitor, speakers, scanner, etc. |

- Understand the **connection type** for each peripheral (USB, Bluetooth, etc.)

---

### Step 3: Device Selection Considerations

- **Desktops**: Best performance, expandability
- **Laptops/2-in-1s**: Mobility, space-saving
- Evaluate:
  - **User needs**
  - **Business requirements**
  - **Available technology**
  - **Budget constraints**

---

### Step 4: 6-Step Setup Process

1. **Reassess physical environment**
2. **Unbox devices** safely and read documentation
3. **Cable management**
   - Use short cables
   - Bundle and label
4. **Electrical management**
   - Use labeled power cables
   - Verify outlet amperage and accessibility
5. **Check ergonomics**
   - Monitor and chair height, arm and foot position, lighting
6. **Configure workstation**
   - OS settings: user login, keyboard, resolution
   - Printer, audio, network, browser
   - Remove bloatware
   - Install productivity software
   - Set up backup and security

---

### Summary of Key Points

- A user’s **job function, location, and accessibility** guide the device decision
- The **right hardware** depends on task intensity (e.g., big data vs. email)
- A proper **workstation setup** involves:
  - **Environment check**
  - **Unboxing and cable setup**
  - **Ergonomic adjustments**
  - **System configuration**

---

## Introduction to Troubleshooting

### Learning Objectives
- Understand basic **computer support concepts**
- Apply **troubleshooting procedures**
- Use **online and manufacturer support resources**
- Summarize the **CompTIA Troubleshooting Model**

---

### Basic Troubleshooting Concepts

1. **Determine the Problem**
   - Ask the user about recent changes
   - Reproduce the issue
   - Separate multiple problems

2. **Examine the Problem**
   - Check for **simple causes** (e.g., unplugged cable)
   - Try multiple solutions
   - If needed, escalate the issue

3. **Solve the Problem**
   - Create a plan, document steps
   - Repair, replace, or combine both
   - Confirm system functionality and finalize documentation

---

### Common Computer Issues
- Loose cables, power issues
- BIOS or POST boot errors
- Blue/black screen
- OS problems or software crashes
- Monitor/display not working

---

### Diagnostic Checklist
- Check for **LEDs, power sounds**
- **Beep codes** (use internet for decoding)
- **Monitor connections**
- **Peripheral cables**

---

### Support Resources
- **Search engines**: Google, Bing, DuckDuckGo
- **Online forums**, community knowledge bases
- **Manufacturer support pages and manuals**
- Prepare:
  - Device model, serial number
  - Purchase date
  - Issue description

---

### CompTIA Troubleshooting Model

1. **Identify the Problem**
   - Gather info, duplicate, ask users, isolate issues

2. **Research**
   - Use knowledge bases or the internet

3. **Establish a Theory**
   - Question the obvious, divide & conquer

4. **Test the Theory**
   - Confirm or refine the theory

5. **Establish a Plan**
   - Consider all potential side effects

6. **Implement the Solution**
   - Escalate if necessary

7. **Verify Full System Functionality**
   - Apply **preventive measures**

8. **Document Everything**
   - Findings, steps, and outcomes

---

### Summary of Key Points

- **Troubleshooting** is a step-by-step support method  
- Start by identifying **common, simple issues**  
- Use **online and manufacturer** resources for help  
- Follow the **CompTIA model** for industry-standard troubleshooting

---

## Advanced Microsoft Windows 10 Management and Utilities

### Learning Objectives
- Perform **advanced workstation management tasks**
- Understand the role of **drivers** and how to update them
- Identify and use **five essential Windows utilities**

---

### 1. Policy Management
- Applies **rules** for:
  - Passwords & retry limits
  - Allowed programs
  - User configurations
- Access via:
  - Search “Group Policy” in Taskbar
  - Edit group policy > User Configuration

---

### 2. Windows Task Manager
- Monitor **apps and background processes**
- Force quit with **End Task**
- Useful when software is **frozen** or unresponsive

---

### 3. Device Manager
- View and manage:
  - **Hardware components**
  - Interfaces (e.g., Intel ME Interface)
- Check status, update drivers, view resource use
- Useful for:
  - **Driver issues**
  - **Firmware checks**

---

### 4. Virtual Memory Management
- Use Task Manager to check **RAM usage**
- Open: **Settings > Performance > Virtual Memory**
- Adjust manually for **high-memory apps**
- Use **Windows Memory Diagnostic** for error checking

---

### 5. Service Management
- For advanced control of background services:
  - **Stop, restart**, run, or **ignore** a service
  - Optionally **restart** the system
- Helps resolve:
  - Unresponsive software
  - Resource bottlenecks

---

### 6. Drivers
- Enable communication between **hardware and OS**
- Symptoms of outdated drivers:
  - Devices not working
- Use **Device Manager > Right-click > Update Driver**

---

### 7. Key Windows Utilities

| Utility               | Function                                               |
|-----------------------|--------------------------------------------------------|
| **Memory Diagnostics**| Detect hardware memory errors                          |
| **Performance Monitor**| Monitor hardware and software performance            |
| **Event Viewer**      | Log system activity, errors, and install issues        |
| **Registry Editor**   | Modify program registration and disk location data     |
| **Task Manager**      | View and manage running tasks and processes            |

---

### Summary of Key Points
- **Group Policy** improves device and data security
- **Task Manager** and **Device Manager** are core tools for diagnosis
- **Drivers** must be current for proper hardware communication
- Windows provides **built-in utilities** for diagnostics and system management
```

---


## Introduction to Business Continuity Principles

### Learning Objectives
- Understand the importance of **business continuity**
- Evaluate a **fault tolerance** system
- Explain the importance of **disaster recovery** planning

---

### What is Business Continuity?
- Business continuity: a plan to **minimize disruption** and **maintain operations** during difficult events
- Built upon **fault tolerance**, which enables systems to run even if some components fail
- Aims to **prevent single points of failure**

---

### Redundancy: The Key to Continuity
Redundancy = Extra capacity or backup that protects against failure

#### Types of Redundancy:
1. **Data Redundancy**
   - Same data exists in multiple locations (e.g., backups)
   - Risk: **inconsistency**
   - Solution: real-time syncing

2. **RAID (Redundant Array of Independent Disks)**
   - **RAID 0**: Improved performance, no fault tolerance
   - **RAID 1**: Mirroring data for fault tolerance
   - **RAID 5**: Secure, requires minimum 3 HDDs

3. **Network Redundancy**
   - Multiple paths and adapters
   - **Load balancing** across servers

4. **Site Redundancy**
   - Entire backup **site** in case of total loss (e.g., natural disaster)
   - Uses **replication** to sync data across locations

5. **Power Redundancy**
   - Two independent power sources
   - **UPS (Uninterruptable Power Supply)** as cost-effective fallback

---

### Backup Strategies

#### Backup Methods:
- **Full**: All files
- **Incremental**: Files changed since last full/incremental
- **Differential**: Files changed since last full
- **Daily**: Only today's changes

#### Backup Devices:
- USB drives
- External HDDs
- LAN servers
- Tape storage
- Cloud-based storage

#### Key Considerations:
- **Cost**: Hardware, software, training
- **Location**: Cloud + additional physical site
- **Storage/time** balance for effective recovery

---

### Disaster Recovery
- Plan to **restore IT functionality** after disruption
- Must include:
  - **Clear procedures**
  - **Scenario-specific** strategies
  - **Rapid execution** and response

---

### Summary of Key Points
- Business continuity requires **planning, redundancy, and disaster recovery**
- **Fault tolerance** systems avoid single-point failures
- **Backup strategies** should align with business needs and resources
- **Disaster recovery** plans restore IT operations after outages

---


















